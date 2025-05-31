# EX 25 C program to check whether a given character is a vowel or consonant using pointer

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



## Output:

![Screenshot 2025-05-26 103406](https://github.com/user-attachments/assets/ba1bf168-2b87-43cd-a58b-e88a7adffdc1)


## Result:

Thus the program was executed and the output was verified successfully.

