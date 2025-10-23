# Day-2
#include <stdio.h>
int main()
{
    float meal_cost,tax,tip,total_bill,friend1_payment,friend2_payment,friend3_payment,each_payment;
    printf("ENTER MEAL PRICE :\n");
    scanf("%f",&meal_cost);
    tax = 5/100*meal_cost;
    tip = 10/100*meal_cost;
    total_bill = meal_cost+tax+tip;
    each_payment=total_bill/3;
    friend1_payment = each_payment+(each_payment/2);
    friend2_payment = friend1_payment;
    friend3_payment = 0;
    printf("total bill=%f\n",total_bill);
    printf("each person should pay as follows :\n");
    printf("you=%f",&friend1_payment);
    printf("friend2=%f\n",friend2_payment);
    printf("friend3 = %f\n",friend3_payment);
    return 0;
}
