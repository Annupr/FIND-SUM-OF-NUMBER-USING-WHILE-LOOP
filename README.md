# FIND-SUM-OF-NUMBER-USING-WHILE-LOOP
Here is the program to find sum of number entered untill 0 is entered using while loop
#include<stdio.h>
int main()
{
	int n,i,sum=0;
		
		printf("\nEnter a number:");
		while(n!=0){
			scanf("%d",&n);
			sum=sum+n;
			
		}
		printf("Sum=%d",sum);
		return 0;
}
