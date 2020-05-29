# food-items-to-order-
New repository 
#include <stdio.h>

int main()
{
	int n;
	printf("enter any number from 1-5\n");
	scanf("%d",&n);
	switch(n)
	{
		case 1:
		printf("pizza, rs 239\n");
		break;
		case 2:
		printf("burger, rs 129\n");
		break;
		case 3 :
		printf("pasta, rs 179\n");
		break;
		case 4 :
		printf("friench fries, rs 99");
		break;
		case 5 :
		printf("sandwich, rs 149");
		break;
		default:
		printf("enter a valid num");
	}
	return 0;
}
