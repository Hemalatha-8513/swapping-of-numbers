# swapping-of-numbers

C program to swap two variables



#include<stdio.h>
int main ()
{
	int a,b;
	printf("Enter a,b values:");
	scanf("%d %d",a,b);
	printf("before swapping a,b values %d%d",a,b);
	a=a+b;
	b=a-b;
	a=a-b;
	printf("\n after swapping a,b values %d%d",a,b);
}



