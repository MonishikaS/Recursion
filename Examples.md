Factorial:
Calculate the factorial of a non-negative integer.
```c
#include <stdio.h>

int factorial(int n) {
    if (n == 0 || n == 1) {
        return 1;
    }
    return n * factorial(n - 1);
}

int main() {
    int num = 5;
    printf("Factorial of %d is %d\n", num, factorial(num));
    return 0;
}
```
Fibonacci Sequence:
Calculate the nth term in the Fibonacci sequence
```c
#include <stdio.h>

int fibonacci(int n) {
    if (n <= 1) {
        return n;
    }
    return fibonacci(n - 1) + fibonacci(n - 2);
}

int main() {
    int num = 6;
    printf("Fibonacci term at index %d is %d\n", num, fibonacci(num));
    return 0;
}


```
