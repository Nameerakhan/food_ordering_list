# food_ordering_list#include <stdio.h>
#include <stdlib.h>

int main()
{
    int p=0,i=0,q=0;
    char name;
    puts("                                                  Cafe Matcha Food odering OS ");
    puts("                                                  1.  Menu");
    puts("                                                  2.  Status");
    puts("                                                  3.  Records");
    puts("                                                  4.  Quit\n\n");
    puts("Please choose from the above number");
    scanf("%d",&p);
    switch(p){
        case 1:{

    puts("                                   _________________________________________________________________________");
    puts("                                                     Cafe Matcha Food & Beverages Menu");
    puts("                                   _________________________________________________________________________");
    puts("                                   | S.no |        Item           |   Code    |  Serving Size  |   Price  |");
    puts("                                   |______|_______________________|___________|________________|__________|");
    puts("                                   |      |   Breakfast           |           |                |          |");
    puts("                                   |  1.  |   French Toast        |     1     |     250gram    |   349Rs  |");
    puts("                                   |  2.  |   Pancakes Platter    |     2     |     200gram    |   399Rs  |");
    puts("                                   |  3.  |   B.L.T Sandwich      |     3     |     280gram    |   299Rs  |");
    puts("                                   |      |   Lunch & Dinner      |           |                |          |");
    puts("                                   |______|_______________________|___________|________________|__________|");
    puts("                                   |  1.  |   Fettuccine-Alfredo  |     4     |     300gram    |   449Rs  |");
    puts("                                   |  2.  |   Burger Meal         |     5     |     350gram    |   499Rs  |");
    puts("                                   |  3.  |   Meatloaf            |     6     |     330gram    |   599Rs  |");
    puts("                                   |  4.  |   Steak               |     7     |     485gram    |   799Rs  |");
    puts("                                   |______|_______________________|___________|________________|__________|");
    puts("                                   |      |   Beverages           |           |                |          |");
    puts("                                   |      |                       |           |                |          |");
    puts("                                   |  1.  |   Hot Chocolates      |     8     |     200ml      |   199Rs  |");
    puts("                                   |  2.  |   Matcha Tea          |     9     |     225ml      |   249Rs  |");
    puts("                                   |  3.  |   Energy Drink        |     10    |     150ml      |   110Rs  |");
    puts("                                   |______|_______________________|___________|________________|__________|");
    printf("Enter the code for the item u wanna order");
    scanf("%d",&i);
    switch(i)
    {
        case 1:
            {
                printf("Please enter quantity for French Toast SERVING-SIZE=250gram Price-349Rs");
                scanf("%d",&q);
                printf("%d French Toast. Total Cost- %d",q,q*349);
            }
        case 2:
            {
              printf("Please enter quantity for Pancake Platter SERVING-SIZE=200gram Price-399Rs");
                scanf("%d",&q);
                printf("%d Pancake Platter. Total Cost- %d",q,q*399);
            }
        case 3:
            {
                printf("Please enter quantity for B.L.T Sandwich SERVING-SIZE=280gram Price-299Rs");
                scanf("%d",&q);
                printf("%d B.L.T. Sandwich Total Cost- %d",q,q*299);
            }
        case 4:
            {
                printf("Please enter quantity for Fettuccine-Alfredo SERVING-SIZE=300gram Price-449Rs");
                scanf("%d",&q);
                printf("%d Fettuccine-Alfredo. Total Cost- %d",q,q*449);
            }
        case 5:
            {
                printf("Please enter quantity for Burger Meal SERVING-SIZE=350gram Price-499Rs");
                scanf("%d",&q);
                printf("%d Burger Meal. Total Cost- %d",q,q*499);
            }
        case 6:
            {
               printf("Please enter quantity for Meatloaf SERVING-SIZE=330gram Price-599Rs");
                scanf("%d",&q);
                printf("%d Meatloaf. Total Cost- %d",q,q*599);
            }
        case 7:
            {
                printf("Please enter quantity for Steak SERVING-SIZE=485gram Price-799Rs");
                scanf("%d",&q);
                printf("%d Steak. Total Cost- %d",q,q*799);
            }
        case 8:
            {
               printf("Please enter quantity for Hot Chocolates SERVING-SIZE=200ml Price-199Rs");
                scanf("%d",&q);
                printf("%d Hot Chocolates. Total Cost- %d",q,q*199);
            }
        case 9:
            {
                printf("Please enter quantity for Matcha Tea SERVING-SIZE=225ml Price-249Rs");
                scanf("%d",&q);
                printf("%d Matcha Tea. Total Cost- %d",q,q*249);
            }

        case 10:
            {
                printf("Please enter quantity for Energy Drink SERVING-SIZE=150ml Price-110Rs");
                scanf("%d",&q);
                printf("%d Energy Drink. Total Cost- %d",q,q*110);
            }
    }
    break;
    }
    case 2:
        {
            printf("Hello %s you order is being serverd thanks for your paitence",name);
        }
    }
    return 0;
}
