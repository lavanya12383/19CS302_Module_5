# EX 25 C program to check whether a given character is a vowel or consonant using pointer
## DATE:17/3/26
## AIM:
To write a C program to check whether a given character is a vowel or consonant using pointer

## Algorithm
Start.
Declare a variable value of type char.
Prompt the user to enter a value.
Read the value using scanf.
Find vowel and consonants
End.

## Program:
```
/*
C program to check whether a given character is a vowel or consonant using pointer
Developed by: ARIGALA LAVANYA
RegisterNumber:212222060019
#include <stdio.h>
int main() {
 char str[100];
 char *p;
 int vowels = 0, consonants = 0;
 scanf(" %[^\n]", str); 
 p = str; 
 while (*p != '\0') {
 if ((*p >= 'A' && *p <= 'Z') || (*p >= 'a' && *p <= 'z')) {
 char ch = (*p >= 'A' && *p <= 'Z') ? *p + 32 : *p;
 if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u') {
 vowels++;
 } else {
 consonants++;
 }
 }
 p++;
 }
 printf("Vowels: %d\n", vowels);
 printf("Consonants: %d\n", consonants);
 return 0;
}
*/
```

## Output:

<img width="468" height="192" alt="image" src="https://github.com/user-attachments/assets/4afde3a8-f94d-4e84-b1f8-04bd0721a330" />


## Result:
Thus the program was executed and the output was verified successfully.
