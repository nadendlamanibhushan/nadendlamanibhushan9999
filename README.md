#include <stdio.h>
void main()
{
    int i,n,a,sum=0;
    printf("Enter the number of elements\n");
    scanf("%d",&n);
    for(i=0;i<n*2;i++)
    {
        if(i%2==0)
        {
        if(i%3==0)
        {
            sum=sum+i;
        }
        }
    }
    printf("sum=%d",sum);
}
