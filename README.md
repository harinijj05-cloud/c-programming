#include<stdio.h>
#include<conio.h>
int main()
{
  int a,b,temp;
  clrscr();
  printf("enter the values of A and B: ");
  scanf("%d%d",&a,&b);
  temp = a;
  a = b;
  b = temp;
  printf("swapped value of A:%d\n",a);
  printf("swapped value of B:%d",b);
  getch();
  return 0;
}
