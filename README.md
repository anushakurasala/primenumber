# primenumber
#include<stdio.h>
int main()
{
int num,i,count;
count=0;
scanf("%d",&num);
for(i=2;i<=num/2;i++)
{
 if(num%i==0)
{
count++;
}
else
{
continue;
}
}
if(count==1)
{
printf("yes");
}
else
{
printf("NO");
}
return 0;
}
