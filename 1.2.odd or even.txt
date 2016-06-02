#include<stdio.h>
#include<conio.h>
int main()
{
int n;
printf("Enter the number");
scanf("%d",&n);
if(n%2==0&&n!=0)
{
printf("The given number %d is even",n);
}
else
{
printf("The given number %d is odd",n);
}
getch();
return(0);
}