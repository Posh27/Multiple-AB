

    #include <stdio.h>
    #include <math.h>
    #include <stdlib.h>

    int main (void) {
        int a, b, multiplo;



        printf ("Enter a number A:");
            scanf ("%i", &a);
        printf ("Enter a number B");
            scanf ("%i", &b);

        multiplo = a % b ;


          if (multiplo == 0) {

                printf("There are multiples\n", multiplo);

        }else {


            printf("There are no multiples\n", multiplo);

        }



    }
