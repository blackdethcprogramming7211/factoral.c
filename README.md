#include<stdio.h>

#include<math.h>
int fact(int);
int fact(int n){
    int factorial=1;
    for(int i=n;i>=1;i--){
        factorial=factorial*i;
    }
    return factorial;
}
int main(){
    int num,fact1;
    printf("enter a num=");
    scanf("%d" ,&num);
    fact1=fact(num);
    printf("the factorial of %d =%d" ,num,fact1);
    
    return 0;
}
