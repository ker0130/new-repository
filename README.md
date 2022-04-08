#include<stdio.h>
int main()
{
int a[10][10],b[10][10],c[10][10];
int m,n,p,q,i,j;
scanf("%d %d %d %d",&m,&n,&p,&q);
if
{
for(i=0;i<m,i++)
{
for(j=0;j<n;j++)
{
scanf("%d",&a[i][j]);
}
}
for(i=0;i<p;i++)
{
for(j=0;j<q;j++)
{
scanf("%d",&b[i][j]);
}
}
for(i=0;i<m;i++)
{
for(j=0;j<n;j++)
{
c[i][j]=a[i][j]+b[i][j];
printf("%d\t",c[i][j]);
}
printf("\n");
}
}
else
{
printf("addition is not possible");
}
}
