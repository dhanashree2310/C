# C
/* program for checking the largest of the two numbers: */
#include<stdio.h>    
#include<conio.h>
void main()
{
clrscr();
int a,b;
printf("enter two nos.");
scanf("%d %d",&a, &b);
if (a>b)
printf("a is greater than b");
else
printf("b is greater than a");
getch();
}
