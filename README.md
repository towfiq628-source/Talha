#include <stdio.h>

int add(int a, int b) {
    return a + b;
}

int main() {
    int num1 = 10, num2 = 20;
    
    printf("Hello, GitHub!\n");
    printf("Sum of %d and %d is: %d\n", num1, num2, add(num1, num2));
    
    return 0;
}
