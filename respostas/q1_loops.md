q1_loops.md

a) Java
int k = (j + 13) / 27;

while (k <= 10) {
    k = k + 1;
    int i = 3 * k - 1;
}

b) Python
k = (j + 13) // 27

while k <= 10:
    k = k + 1
    i = 3 * k - 1
    
c) Haskell
loop k
  | k > 10    = ()
  | otherwise =
      let k' = k + 1
          i  = 3 * k' - 1
      in loop k'

main = loop ((j + 13) `div` 27)

d) Swift
var k = (j + 13) / 27

while k <= 10 {
    k = k + 1
    let i = 3 * k - 1
}
