# Reverse-Integer
//reverse an integer

#include<stdio.h>
int main()
{
	int n,  remainder, reverse=0;
	printf("type the number:");
	scanf("%d",&n);
	
	while(n!=0)
	{
		remainder=n%10;
		reverse=reverse*10+ remainder;
		n=n/10;
		
	}
printf("Reverse no %d",reverse );
return 0;
	
	
	
}
