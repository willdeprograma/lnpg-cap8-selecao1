1. Python
i = 0
j = 17
n = 100
sum = 0

while i < n:
    sum += i * j + 3
    i += 1
    j -= 1
    
2. JavaScript
let sum = 0;

for (let i = 0, j = 17, n = 100; i < n; i++, j--) {
    sum += i * j + 3;
}

3. C++
int sum = 0;
for (int i = 0, j = 17, n = 100; i < n; i++, j--) {
    sum += i * j + 3;
}

4. Go
sum := 0
n := 100

for i, j := 0, 17; i < n; i, j = i+1, j-1 {
    sum += i*j + 3
}

5. Kotlin
var sum = 0
var j = 17
val n = 100

for (i in 0 until n) {
    sum += i * j + 3
    j--
}
