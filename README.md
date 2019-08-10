#include<stdio.h>
int main()
{
int x,p,c;
scanf("%d%d",&x,&p);
if((0<=x)&&(x<=10000)&&(1<=p)&&(p<=1000))
{
c=x;
while(x>0)
{
x=x*((100-p)/100);
c=c+x;
}
}
else
{}
printf("%d\n",c);
return 0;
}
