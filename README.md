# the-pattern
it is a normal pattern program .
#include <stdio.h>

int main()
{
    int i , j , k;
    scanf("%d",&k);
    for(i=0;i<k;i++){
        for(j=0;j<=i;j++){
            printf("*");
        }printf("\n");
    }
    
}
