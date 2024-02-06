#include<stdio.h>
int main()
{
	int n, i, j;
	for (n = 1; n <= 5; n++)
	{
		for (i = 2 * n - 1; i > 0; i++)
			putchar('*');
		for (j = 0; j <= n - 1; j++)
			putchar(' ');
		putchar('\n');
	}
}
