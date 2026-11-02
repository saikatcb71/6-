#include<stdio.h>
int main () {
int num;
printf("enter the digit :");
scanf("%d" , &num);
if (0 <= num  && num <= 9){
printf(" single digit number");
}
else if (10<= num  && num <= 99){
printf(" double digit number");
}

else {
printf(" three digit number");
}

return 0;
}
