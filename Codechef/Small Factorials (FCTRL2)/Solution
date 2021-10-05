#include <stdio.h>
 
int main(void) 
{
	int t, i, j, n;
	
	scanf("%d", &t);
	for(i=1; i<=t; i++)
	{
		scanf("%d", &n);
		int len=1;
		int ans[160] = {1};
		for(j=1; j<=n; j++)
		{
		  int k=0,carry=0;
		  while(k<len){
		      int temp=ans[k]*j+carry;
		      ans[k]=temp%10;
		      carry=temp/10;
		      k++;
		  }
		  while(carry>0){
		      ans[len]=carry%10;
		      carry=carry/10;
		      len++;
		  }
		}
		for(j=len-1;j>=0;j--){
		    printf("%d", ans[j]);    
		}
		printf("\n");
	}
	return 0;
}
