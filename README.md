# Lab-1
Adding the odd numbers from 1 to N.  


 #include <stdio.h>
int main() {
    int n, i , sum=0;
    printf ("Enter a number: ");
    scanf ("%d", &n );
    for (i=1;i<=n;i++){
        if (i%2!=0){
            sum = sum+i;
        }
    }
    printf("Sum of odd numbers from 1 to %d = %d\n ",n,sum);
 

    return 0;
}
