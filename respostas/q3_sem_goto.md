🔹 1. C
int j = -3;

for (int i = 0; i < 3 && j <= 0; i++) {

    int val = j + 2;

    if (val == 3 || val == 2) {
        j--;
    } else if (val == 0) {
        j += 2;
    } else {
        j = 0;
    }

    if (j <= 0) {
        j = 3 - i;
    }
}

🔹 2. Python
j = -3
i = 0

while i < 3 and j <= 0:
    val = j + 2

    if val == 3 or val == 2:
        j -= 1
    elif val == 0:
        j += 2
    else:
        j = 0

    if j <= 0:
        j = 3 - i

    i += 1
    
🔹 3. Java
int j = -3;

for (int i = 0; i < 3 && j <= 0; i++) {

    int val = j + 2;

    if (val == 3 || val == 2) {
        j--;
    } else if (val == 0) {
        j += 2;
    } else {
        j = 0;
    }

    if (j <= 0) {
        j = 3 - i;
    }
}
