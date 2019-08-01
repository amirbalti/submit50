# submit50
#include <cs50.h>
#include <stdio.h>
#include<stdio.h>
#include<cs50.h>
int input_n(int);
void print_mario(int);
int main(void)
{
    int n = 0;
    n = input_n(n);
    print_mario(n);
}
int input_n(int m){
    do{
    m = get_int("Height: ");
}while(m<1 || m>8);
    return m;
}
void print_mario(int l){
        int n = l;
    for(int i=0; i<n; i++){
        while(i<l){
            printf(" ");
            l--;
        }
        l = n;
        for(int j=0; j<=i; j++){
            printf("#");
        }
        printf("\n");
    }
}
