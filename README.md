# BINARY-GAS-LEAK-SENSOR
predicting a gas leakage inputting binary codes.

// A program to predict gas leakage in the help of stimulation of electrical switch

    #include <stdio.h>
     int main()
    {
        printf("WELCOME TO THE LPG CUSTOMER CARE SERVICE \n our service enables you to check whether the LPG received at your end is safe or not. \n" );
       int alrt;
       printf ("\n \n  ENTER 1 incase of some issue in the LPG or else ENTER 0   \n\n\n\n");
       scanf ("%d" , &alrt);
                      if(alrt==1)
                   {
                        printf("GAS LEAKAGE ALERT!! \n PLEASE TAKE THE PRECAUTIONS NEEDED");
                    }
                       else
                      {
                           printf("GAS IS SAFE TO USE");
                       }
    return 0;
    }

