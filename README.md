//To find number is a odd number or even number
#include<stdio.h>
#include<conio.h>
void main()
{
int ch,number;
do{
int number;
printf("enter the number");
scanf("%d",&number);
if(number%2==0)
{
printf("%d is an even number");
}
else
{
printf("%d" is an odd number");
}
printf("do you need to check for another number");
ch=getche();
}while(ch=='Y'||ch=='y');
getch();
}

