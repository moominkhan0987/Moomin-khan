#include <stdio.h>

int main() {
    int n, i;
    float num, largest;

    printf("Enter how many numbers: ");
    scanf("%d", &n);

    printf("Enter number 1: ");
    scanf("%f", &largest);   // assume first number is largest

    for (i = 2; i <= n; i++) {
        printf("Enter number %d: ", i);
        scanf("%f", &num);

        if (num > largest) {
            largest = num;
        }
    }

    printf("Largest number = %.2f\n", largest);

    return 0;
}
