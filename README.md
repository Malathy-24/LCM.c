#include<stdio.h>
#include<stdlib.h>
int main()
{
  int n1,n2,max;
  printf("enter first and second number:\n");
  scanf("\n%d\t%d",&n1,&n2);
  if(n1>n2)
         max=n1;
  else
        maxn=n2;
  while(1)
  {
    if(max % n1==0 && max % n2==0)
    {
              printf("\nLCM is:%d" , max);
              break;
     }
     ++max;
   }
   return 0;
  } 

