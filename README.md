# linear-search-program-in-c
#include<stdio.h>
int main()
{
 int arr[]={70,80,30,20,50};
 int element=80;
 int size=4;
 int searchindex=linersearch(arr,size,element);
  printf("the element%d was found at index%d\n",element,searchindex);
 return 0;
}
int linersearch(int arr[],int element,int size)
{
    for(int i=0;i<size;i++)
    {
        if(arr[i]==element)
        {
            return 1;
            }
    }
    return -1;
}
