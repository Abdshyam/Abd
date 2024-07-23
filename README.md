# insert 20 elements in an 4*5 matrix array
#include <stdio.h>

int main() {
    int matrix[4][5];
    int count = 1; // Variable to insert elements starting from 1

    // Inserting elements into the 4x5 matrix
    for (int i = 0; i < 4; i++) {
        for (int j = 0; j < 5; j++) {
            matrix[i][j] = count++;
        }
    }

    // Printing the matrix
    printf("The 4x5 matrix is:\n");
    for (int i = 0; i < 4; i++) {
        for (int j = 0; j < 5; j++) {
            printf("%d\t", matrix[i][j]);
        }
        printf("\n");
    }

    return 0;
}
