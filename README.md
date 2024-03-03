#include <stdio.h>
#include <stdlib.h>
int main()
{
	int input; //
	int a,b; //
	int sum = 0;//
	scanf_s("%d", &input); //
	a = input; //
	int i, j = 0; //
	while (a > 0) //
	{
			b = a%2; //
			a = a / 2; //
			for (i = 1; j >= i; i++)  //
			{
				b = b * 10;
			}
		
			sum = sum + b; // 
			j++; //
	}
	printf("%d",sum); //
	system("PAUSE");
}
