# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.

## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm

Start.

Define the required variable.

Write program to find frequency of a character.

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End.

## Program:
```
#include<stdio.h>
#include<string.h>
int main()
{
int i,count=0,len;
char str[100],val[100];
scanf("%s %s",str,val);
len=strlen(str);
for(i=0;i<len;i++){
if(str[i]==val[0])
count++;
}printf("%d",count);}
```

## Output:

<img width="262" height="273" alt="image" src="https://github.com/user-attachments/assets/d04088af-3bd8-4d4a-b309-b6092851e512" />




## Result:
Thus the program was executed and the output was verified successfully.
