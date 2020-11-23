# matrix
#include<stdio.h>
#include<conio.h>
void main()
{
	int a[10][10],sum=0,i,j,n,k ,x,y;
	printf("Enter the order of matrix\n");
	scanf("%d %d",&x,&y);
	printf("Enter the elements of matrix\n");
	if(x==y)
	{
	for(i=0;i<x;i++)
	{
		for(j=0;j<y;j++)
		{
			printf("element[%d] [%d]\t",i,j);
			scanf("%d",&a[i][j]);
		}
		
	}
	printf("matrix is\n");
for(i=0;i<x;i++)
{
	for(j=0;j<y;j++)
	{
		printf("%d",a[i][j]);
	}
	printf("\n");
}
for(i=0;i<x;i++)
{
		sum=sum+a[i][i];
	
}
	printf("the sum of diagonals are %d\n",sum);
}
else
printf("-------------------------------------");
}
