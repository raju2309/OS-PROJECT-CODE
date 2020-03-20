# OS-PROJECT-CODE
SOLUTION FOR QUESTTION NO.18
#include<stdio.h>
   int i,t,j,n; //Variable Declarion
   int A_T[10],p_no[10],bill[10];  //A_T=burst time,p_no=process no.
   float cost;
void billfn()           //bill generation
   {
     printf(" Student_No\t\tTotal Gifts Purchased\t\tBill\n\n");
         for(i= 0; i<n; i++)
             {
                  printf("Student No. = %d\t\t" ,p_no[i]);
                  printf("%d \t\t\t",A_T[i]);
                  bill[i]= cost * A_T[i];     //calculating cost
                  printf("%d \t\t\t",bill[i]);
                printf("\n");
              }
    }
 void get() //list of gifts taken by students  (Value entered by User)
   {
      printf("\n\n");
      printf("Entered Data\n\n");
         printf("\nStudent No.\t\tNo. Of Gifts Purchased \n");
           for(i = 0; i < n; i++)
            {
                printf("Student No. = %d \t\t",p_no[i]);  //process no
                printf("%d \t\t\t",B_T[i]);               //brust time
              printf("\n\n");
            }
       }
       
             
