#include <stdio.h>
#include <string.h>
#define MAX 1001
int main(void) 
{
	int i,test,j,k,count1;
	char a[MAX],b[MAX];
	scanf("%d", &test);
	for(i=1;i<=test;i++)
	{
		scanf("%s",&a);
		scanf("%s",&b);
		count1=0;
		for(j=0;j<strlen(a);j++)
		{
			for(k=0;k<strlen(b);k++)
			{
				if(a[j]==b[k])
				{
					count1++;
				}
			}
		}
		if(count1>0)
		{
			printf("Yes\n");
		}
		else
		{
			printf("No\n");
		}
	}
 
	return 0;
}
