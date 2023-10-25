# -3
#include <stdio.h>
int main()
{
	int a;
	char b;
	for (a = 0; a <= 26; a++)
	{
		for (b = 'A' + a; b < 'A' + 26; b++)

			printf("%c", b);
		printf("\n");
	}
	return 0;
}
