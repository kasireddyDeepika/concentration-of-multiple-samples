/*finding concentrations of multiple samples*/
#include<stdio.h>
int main()
{
int i,n;
float c,v,m;
printf("\n enter the number of samples:");
scanf("%d",&n);
for(i=1;i<=n;i++)
{
printf("\n sample %d",i);
printf("enter the value of m:");
scanf(" %f",&m);
printf("enter the value of v:");
scanf(" %f",&v);
if(v!=0)
{
c=m/v;
printf("\n concentration is %2f",c);
}
else
{
printf("\n error!! volume cannot be calculated");
}
}
return 0;
}


