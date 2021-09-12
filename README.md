
#include <stdio.h>
int main(){
int num=0;
printf("Enter your order number:");
scanf("%d",&num );
printf("You entered %d\n",num);
switch (num )
{
case 1:
   printf("Food item - Pizza \n price - Rs 239."); 
break;
case 2 :
printf(" Food item - Burger \n Prise - Rs 129. ");
break;
case 3:
printf(" Food item - Pasta \n Prise - Rs 179. "); 
break;
case 4:
printf(" Food item - French Fries \n Prise - Rs 99. "); 
break;
case 5:
     printf ("Food item - Sandwich \n Prise - Rs 149. ");
break ;
    default:
    printf ("use the default case.\n");
    }
}
