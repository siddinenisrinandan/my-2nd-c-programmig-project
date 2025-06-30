# my-2nd-c-programmig-project
#include <stdio.h>

int main()
{
   int num;
   printf("(select 0 to 3_)select=");
   scanf("%d",&num);
   switch(num){
       case 0:printf("zero");
       break;
       case 1:printf("one");
       break;
       case 2: printf("two");
       break;
       case 3:printf("three");
       break;
   }
  
   
    return 0;
}
