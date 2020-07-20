# hello-world
#include<stdio.h>
int main(){
int i,count=0,n,d=0;
printf("count the digit:");
scanf("%d",&n);
for(i=0;i<=n;i++){
d=i;
while(d>0)
{
d=d/10;
count++;
}}
printf("total digit=%d",count);
}
