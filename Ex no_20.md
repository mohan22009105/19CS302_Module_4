# EX 20 C program to convert the given string to lowercase without using string functions.

## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm
Start.

Define the required variable.

Convert the string to lowercase.

Read the value using scanf.

Print out the answer.

End..

## Program:
```
#include <stdio.h>
#include <string.h>
int main()
{
  char str[30];
  
  scanf("%[^\n]", str);
  int i = 0;
  //convert capital letter string to small letter string
  while (str[i] != '\0')
  {
    if (str[i] > 64 && str[i] < 91) //or if(str[i]>='A' && str[i]<='Z')
      str[i] += 32;
    i++;
  }
  printf("Lower case String is:%s", str);
}
```

## Output:

<img width="1058" height="202" alt="image" src="https://github.com/user-attachments/assets/29130a05-4697-45cf-9ead-e1043f1904f3" />




## Result:
Thus the program was executed and the output was verified successfully.
