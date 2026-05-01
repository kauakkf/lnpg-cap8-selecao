// Python
n = 100
j = 17
sum_val = 0
for i in range(n):
    sum_val += i * j + 3
    j -= 1

// Java
int i, j, n = 100, sum = 0;
for (i = 0, j = 17; i < n; i++, j--) {
    sum += i * j + 3;
}

// JavaScript
let n = 100, sum = 0;
for (let i = 0, j = 17; i < n; i++, j--) {
    sum += i * j + 3;
}

// C++
int n = 100, sum = 0;
for (int i = 0, j = 17; i < n; ++i, --j) {
    sum += i * j + 3;
}

// Swift
let n = 100
var j = 17
var sum = 0
for i in 0..<n {
    sum += i * j + 3
    j -= 1
}
