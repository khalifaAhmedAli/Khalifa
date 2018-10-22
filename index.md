#include<stdio.h>
int main()
{
 int number[7]={11,12,13,14,15,16,17};
 int ans[7];
 int add,all=0;
 float avg;
 for(add=0;add<8;add++);
{
 all+=number[add];
}
avg=all/7;
printf("the sum is  %d",all);
printf("\n Average is %f",avg);
printf("\nVeriance for each number");
for(add=0;add<7;add++)
{
ans[6]=(number[add]-avg)*(numbe[add]-avg);
printf("\n %d",ans[6]);
}
return 0;
}
