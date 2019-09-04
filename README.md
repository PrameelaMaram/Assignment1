# missing element in array->1
#include<stdio.h>
void main()
{

   int a[100],b[100],n=0,n1=0,i,j,temp=0,temp1=0;
  
   a[0]=5; //5,4,9,8,6
    a[1]=4;
    a[2]=9;
    a[3]=8;
    a[4]=6;
    a[5]='\0';
    b[0]=9; //4,9,8,6
    b[1]=6;
    b[2]=4;
    b[3]=8;
  b[4]='\0';
 
for(i=0;a[i]!='\0';i++)
    temp=temp+a[i];
 for(i=0;b[i]!='\0';i++)
    temp1=temp1+b[i];
 printf("\nthe missing element is %d ",abs(temp1-temp));

}

