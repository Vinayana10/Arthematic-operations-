# Arthematic-operations-
#include<stdio.h>
int main(){
    int a,b,c;
    printf("Enter your option \n 1. Addition \n 2. Subtraction \n 3. Multiplication \n 4. Division \n");
    scanf("%d",&a);
    switch (a)
    {
    case 1:
        printf("Enter the two values: \n");
        scanf("%d%d",&b,&c);
        printf("addition(%d%d) = %d",b,c,b+c);
        break;
    case 2:
        printf("Enter the two values: \n");
        scanf("%d%d",&b,&c);
        printf("subtraction(%d%d) = %d",b,c,b-c);
        break;
    case 3:
        printf("Enter  the two values: \n");
        scanf("%d %d",&b,&c);
        printf("multipliccation(%d,%d)  = %d",b,c,b*c);
        break;
    case 4:
        printf("Enter the two values: \n");
        scanf("%d%d",&b,&c);
        printf("division(%d%d) = %d",b,c,b/c);
        break;
    default:
        printf("invalid input");
        break;
    }
    return 0;
}
