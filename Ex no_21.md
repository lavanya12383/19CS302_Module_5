# EX 21 C program to calculate the area of a triangle using pointer.
## DATE:17/03/26
## AIM:
To write a C program to calculate the area of a triangle using pointer.

## Algorithm
Start.
Declare three variable value of type float.
Prompt the user to enter values.
Read the values using scanf.
Find the area of triangle using formula
End.


## Program:
```
/*
C program to calculate the area of a triangle using pointer.
Developed by:   ARIGALA LAVANYA
RegisterNumber:212222060019
#include <stdio.h>
int main() {
 float base, height, area;
 float *pBase = &base, *pHeight = &height;
 scanf("%f", pBase);
 scanf("%f", pHeight);
 area = 0.5 * (*pBase) * (*pHeight);
 printf("%.2f\n", area);
}
*/
```

## Output:

<img width="462" height="172" alt="image" src="https://github.com/user-attachments/assets/cd0f3fe0-6261-492d-a4aa-3d5dad396b7c" />


## Result:
Thus the program was executed and the output was verified successfully.
