#include <stdio.h>
 
int main()
{
	int a, b;
	
	printf("Enter a:\n");
	scanf("%d",&a);
	printf("Enter b:\n");
	scanf("%d",&b);
	printf("Before swapping a = %d \n",a);
	printf("Before swapping b = %d \n",b);
	a=a+b;
	b=a-b;
	a=a-b;
	printf("After swapping a = %d \n",a);
	printf("After swapping b = %d \n",b);
	return 0;
}
