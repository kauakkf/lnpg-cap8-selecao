// Java
int k = (j + 13) / 27;

while (k <= 10) {
    k = k + 1;
    i = 3 * k - 1;
}

// Python
k = (j + 13) // 27
while k <= 10:
    k += 1
    i = 3 * k - 1

// Python
k = (j + 13) // 27
while k <= 10:
    k += 1
    i = 3 * k - 1

// Haskell
let k_inicial = (j + 13) `div` 27
let loop k = if k > 10 
             then k 
             else loop (k + 1)
let k_final = loop k_inicial
let i = 3 * k_final - 1

// Swift
var k = (j + 13) / 27
while k <= 10 {
    k += 1
    i = 3 * k - 1
}
