#include <stdio.h>

// Function to display the menu
void displayMenu() {
    printf("Welcome to the Multiplication Table Generator!\n");
    printf("-------------------------------------------------\n");
    printf("Choose an option:\n");
    printf("1. Generate multiplication table for a single number\n");
    printf("2. Generate multiplication tables for a range of numbers\n");
    printf("3. Exit\n");
}

// Function to generate a multiplication table for a single number
void generateSingleTable(int num) {
    printf("\nMultiplication Table for %d:\n", num);
    for (int i = 1; i <= 10; i++) {
        printf("%d x %d = %d\n", num, i, num * i);
    }
    printf("\n");
}

// Function to generate multiplication tables for a range of numbers
void generateRangeTables(int start, int end) {
    printf("\nMultiplication Tables from %d to %d:\n", start, end);
    for (int num = start; num <= end; num++) {
        generateSingleTable(num);
    }
}

int main() {
    int choice, number, start, end;

    while (1) {
        displayMenu();
        printf("Enter your choice: ");
        scanf("%d", &choice);

        switch (choice) {
        case 1:
            printf("\nEnter a number to generate its multiplication table: ");
            scanf("%d", &number);
            generateSingleTable(number);
            break;

        case 2:
            printf("\nEnter the starting number: ");
            scanf("%d", &start);
            printf("Enter the ending number: ");
            scanf("%d", &end);
            generateRangeTables(start, end);
            break;

        case 3:
            printf("\nExiting program. Thank you!\n");
            return 0;

        default:
            printf("\nInvalid choice! Please try again.\n");
            break;
        }
    }
        // 1. FOR LOOP: Print numbers 1 to 10
    printf("FOR LOOP: Numbers 1 to 10\n");
    for (int i = 1; i <= 10; i++) {
        printf("%d ", i);
    }
    printf("\n\n");

    // 2. FOR LOOP: Print multiplication table for 5
    printf("FOR LOOP: Multiplication table for 5\n");
    for (int i = 1; i <= 10; i++) {
        printf("5 x %d = %d\n", i, 5 * i);
    }
    printf("\n");

    // 3. WHILE LOOP: Sum of first 10 natural numbers
    int sum = 0, j = 1;
    printf("WHILE LOOP: Sum of first 10 natural numbers\n");
    while (j <= 10) {
        sum += j;
        j++;
    }
    printf("Sum = %d\n\n", sum);

    // 4. WHILE LOOP: Print even numbers from 1 to 20
    int n = 1;
    printf("WHILE LOOP: Even numbers from 1 to 20\n");
    while (n <= 20) {
        if (n % 2 == 0) {
            printf("%d ", n);
        }
        n++;
    }
    printf("\n\n");

    // 5. DO-WHILE LOOP: Print numbers in reverse from 10 to 1
    int k = 10;
    printf("DO-WHILE LOOP: Numbers in reverse from 10 to 1\n");
    do {
        printf("%d ", k);
        k--;
    } while (k > 0);
    printf("\n\n");

    // 6. DO-WHILE LOOP: Calculate the factorial of a number
    int num, factorial = 1, counter = 1;
    printf("DO-WHILE LOOP: Factorial of a number\n");
    printf("Enter a number: ");
    scanf("%d", &num);
    do {
        factorial *= counter;
        counter++;
    } while (counter <= num);
    printf("Factorial of %d = %d\n\n", num, factorial);

    // 7. NESTED FOR LOOPS: Print a 5x5 grid of stars
    printf("NESTED FOR LOOPS: 5x5 grid of stars\n");
    for (int row = 1; row <= 5; row++) {
        for (int col = 1; col <= 5; col++) {
            printf("* ");
        }
        printf("\n");
    }
    printf("\n");

    // 8. NESTED FOR LOOPS: Multiplication table up to 5x5
    printf("NESTED FOR LOOPS: Multiplication table up to 5x5\n");
    for (int i = 1; i <= 5; i++) {
        for (int j = 1; j <= 5; j++) {
            printf("%2d ", i * j);
        }
        printf("\n");
    }
    printf("\n");

    // 9. COMBINED LOOPS: Detect prime numbers from 1 to 50
    printf("COMBINED LOOPS: Prime numbers between 1 and 50\n");
    for (int i = 2; i <= 50; i++) {
        int isPrime = 1;
        for (int j = 2; j <= i / 2; j++) {
            if (i % j == 0) {
                isPrime = 0;
                break;
            }
        }
        if (isPrime) {
            printf("%d ", i);
        }
    }
    printf("\n\n");

    // 10. LOOP WITH BREAK: Find the first number divisible by 7 in 1 to 50
    printf("LOOP WITH BREAK: First number divisible by 7 in range 1 to 50\n");
    for (int i = 1; i <= 50; i++) {
        if (i % 7 == 0) {
            printf("First number divisible by 7: %d\n", i);
            break;
        }
    }
    printf("\n");

    return 0;
}
