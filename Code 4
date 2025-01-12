#include <stdio.h>

// Function declarations
void printNumberTriangle(int n);
void printStarPattern(int n);
void calculateSumOfSquares(int n);

int main() {
    int n = 5;

    // Printing a number triangle
    printf("Number Triangle:\n");
    printNumberTriangle(n);

    // Printing a star pattern
    printf("\nStar Pattern:\n");
    printStarPattern(n);

    // Calculating the sum of squares of numbers
    printf("\nSum of Squares Calculation:\n");
    calculateSumOfSquares(n);

    return 0;
}

// Function to print a number triangle
void printNumberTriangle(int n) {
    for (int i = 1; i <= n; i++) {
        for (int j = 1; j <= i; j++) {
            printf("%d ", j);
        }
        printf("\n");
    }
}

// Function to print a star pattern
void printStarPattern(int n) {
    for (int i = 1; i <= n; i++) {
        for (int j = 1; j <= i; j++) {
            printf("* ");
        }
        printf("\n");
    }
}

// Function to calculate the sum of squares of the first n numbers
void calculateSumOfSquares(int n) {
    int sum = 0;
    for (int i = 1; i <= n; i++) {
        sum += i * i;
    }
    printf("Sum of squares from 1 to %d is: %d\n", n, sum);
}

// Extra functionality to fill 100 lines
void printMultiplicationTable(int max) {
    printf("\nMultiplication Table:\n");
    for (int i = 1; i <= max; i++) {
        for (int j = 1; j <= max; j++) {
            printf("%3d ", i * j);
        }
        printf("\n");
    }
}

void numberGrid(int size) {
    printf("\nNumber Grid:\n");
    for (int i = 1; i <= size; i++) {
        for (int j = 1; j <= size; j++) {
            printf("%2d ", (i - 1) * size + j);
        }
        printf("\n");
    }
}

// Call additional patterns (uncomment these calls in main if you'd like):
// printMultiplicationTable(5);
// numberGrid(4);
