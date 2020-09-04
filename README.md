# Beezlabs
// 2.Missing Number
#include <stdio.h>
int getMissingnumber(int arr[],int n)
{
int i,total;
total=(n+1)*(n+2)/2;
for(i=0;i<n;i++)
total -=arr[i]; 
return total;
}
int main()
{
int arr[]={1,2,4,5,6};
int missnum=getMissingnumber(a,5);
printf("The missing number from 1 to 8 is %d",missnum);
}
