# The-factoral of all numbers.-between any-two-numbers
#include<stdio.h>
int main()
{   
    int n,i,prod,a,b;
    printf("enter two number for factorial:");
    scanf("%d%d",&a,&b);
    for(n=a; n<=b; n++)
    {   
        prod=1;
        for (i=1; i<=n; i++)
        {
         prod= prod*i;   
        }
        printf("the factorial of %d is: %d\n ",n,prod);
 
    }
return 0;
}
