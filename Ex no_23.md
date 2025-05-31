# EX 23 C program to store and display the name, id, age and salary of an employee using structure(using array of structure).

## AIM:
To write a C program to store and display the name, id, age and salary of an employee using structure(using array of structure).

## Algorithm

Start.

Define a variables.

Write program to to store and display the name, id, age and salary of an employee using structure(using array of structure).

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End.

## Program:


#include<stdio.h> 

struct employee

{

int id,age,salary; 

char name[30];

}emp[100]; 

int main()

{

int i,n; 

scanf("%d",&n); 

for(i=0;i<n;i++)

{

scanf("%d %s %d %d",&emp[i].id,emp[i].name,&emp[i].age,&emp[i].salary);

}

printf("Employee Details\n"); 

for(i=0;i<n;i++)

printf("%d %s %d %d\n",emp[i].id,emp[i].name,emp[i].age,emp[i].salary);

}



## Output:

![Screenshot 2025-05-26 102913](https://github.com/user-attachments/assets/93884343-ae64-47dd-96f7-0a320ccd0029)


## Result:

Thus the program was executed and the output was verified successfully.
