# EX-03 Program to Perform Addition and Subtraction Using Functions

## AIM:
To write a C program that performs addition and subtraction of two numbers a and b using user-defined functions.

## ALGORITHM:

1. Start
2. Declare two integer variables a and b to store the input numbers.
3. Create two user-defined functions:
4. int add(int x, int y) → returns the sum of x and y.
5. int subtract(int x, int y) → returns the difference between x and y.
6. In the main() function:
7. Read the values of a and b from the user.
8. Call the add() and subtract() functions.
8. Display the results.
10. Stop

## PROGRAM:
```
#include <stdio.h>

void AddSub();

int main()
{
	printf("Enter the two numbers: ");
    AddSub();
    return 0;
}

void AddSub()
{
    int num1,num2;
    scanf("%d %d",&num1,&num2);
    printf("Addition: %d\n",num1+num2);
    printf("Subtraction: %d",num1-num2);
}
```

## OUTPUT:

<img width="656" height="155" alt="image" src="https://github.com/user-attachments/assets/701978a5-d7f8-4ceb-bdea-70004656f819" />


## RESULT:

The program successfully performs addition and subtraction of two numbers using user-defined functions and displays the results correctly.
