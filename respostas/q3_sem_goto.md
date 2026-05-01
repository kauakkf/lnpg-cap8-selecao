// Python
j = -3
for i in range(3):
    val = j + 2
    if val == 3:
        pass
        j -= 1
    elif val == 2:
        j -= 1
    elif val == 0:
        j += 2
    else:
        j = 0
        
    if j <= 0:
        j = 3 - i
    else:
        break

// Java
int j = -3;
int i = 0;
boolean continuar = true;

while (i < 3 && continuar) {
    int cond = j + 2;
    if (cond == 3 || cond == 2) {
        j--;
    } else if (cond == 0) {
        j += 2;
    } else {
        j = 0;
    }
    
    if (j > 0) {
        continuar = false;
    } else {
        j = 3 - i;
    }
    i++;
}

// JavaScript
let j = -3;
for (let i = 0; i < 3; i++) {
    let check = j + 2;
    if (check === 3 || check === 2) j--;
    else if (check === 0) j += 2;
    else j = 0;

    if (j > 0) i = 3;
    else j = 3 - i;
}
