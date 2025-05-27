# EX 13 To write a C program to read the elements and print only the odd elements in the 2D array.
## DATE:
## AIM:
To write a C program to read the elements and print only the odd elements in the 2D array.

## Algorithm
1. Start.
2. Define a variables i,j,n,a.
3. Write program to find n x n matrix.
4. Read the value using scanf.
5. Ask the user to make an input
6. Print out the answer.
7. End.  

## Program:
```c
#include<stdio.h> 
int main()
{
int i,j,n,a[10][10];
scanf("%d",&n); 
for(i=0;i<n;i++)
{
for(j=0;j<n;j++)
{
scanf("%d",&a[i][j]);
}
}for(i=0;i<n;i++)
{
for(j=0;j<=n;j++)
{
if(a[i][j]%2==1)
{
printf("a[%d][%d] is %d \n",i,j,a[i][j]);
}
}
printf("\n");
}
return 0;
SAVEETHA ENGINEERING COLLEGE
}
```

## Output:

![image](https://github.com/user-attachments/assets/5f9e3cd7-2fb0-493d-9f35-d3c4ad6eb51b)


## Result:
Thus the program was executed and the output was verified successfully.
