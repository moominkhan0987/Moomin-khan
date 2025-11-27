#include <stdio.h>
#include <string.h>
#include <ctype.h>

int main() {
    char input[50];
    int i, dot = 0;

    printf("Enter a number: ");
    scanf("%s", input);

    // Check each character
    for (i = 0; input[i] != '\0'; i++) {
        if (input[i] == '.') {
            dot++;
        }
        // optional: check for invalid characters
        else if (!isdigit(input[i]) && input[i] != '-') {
            printf("Invalid input.\n");
            return 0;
        }
    }

    if (dot == 0)
        printf("Input is an INTEGER.\n");
    else if (dot == 1)
        printf("Input is a FLOAT.\n");
    else
        printf("Invalid number format.\n");

    return 0;
}
