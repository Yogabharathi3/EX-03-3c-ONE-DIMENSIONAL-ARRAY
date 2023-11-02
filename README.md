# EX-03-3c-ONE-DIMENSIONAL-ARRAY
## AIM 
To write a C program to read n elements as input and print the last element of the 
array. 
## ALGORITHM 
1. Start the program. 
2. Read a variable. 
3. Read the array values n number of times. 
4. Print the last element. 
5. Stop the program. 
## PROGRAM
```
#include<stdio.h> 
int main() 
{ 
 int n,i,a[10]; 
 scanf("%d",&n); 
 for(i=0;i<n;i++) 
 scanf("%d",&a[i]); 
 printf("%d",a[n-1]); 
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/EX-03-3c-ONE-DIMENSIONAL-ARRAY/assets/118899387/b598c5e7-022c-4f71-bf1f-e67f3c163473)
## RESULT 
Thus the program to read n elements as input and print the last element of the 
array has been executed successfully.
