#include <stdio.h>

int main() {
    int t;
    scanf("%d", &t);
    while (t--) {
        int x, y,sum=0;
        scanf("%d %d", &x, &y);
        sum=x+y;
        if(sum>6){
            printf("\nYES");
        }else{
            printf("\nNO");
        }
    }
}
