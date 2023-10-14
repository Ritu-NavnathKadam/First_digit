# First_digit
#include<stdio.h>
void main()
{
int n,n1;
printf("enter a number :-");
scanf("%d",&n);
n1=n;
     while(n>10)
       {
         n=n/10;
       }
printf("First digit of %d =%d",n1,n);
}









