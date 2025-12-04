  
#include <stdio.h>
 
int main() {
	int maths, english, physics, fpl, bet;
    float average;
 
   printf("Enter marks in Maths: ");
    scanf("%d", &maths);
 
   printf("Enter marks in English: ");
    scanf("%d", &english);
 
  printf("Enter marks in Physics: ");
    scanf("%d", &physics);
    
  printf("Enter marks in fpl: ");
    scanf("%d", &fpl);
    
   printf("Enter marks in bet: ");  
    scanf("%d", &bet);
 
   average = (maths + english + physics+fpl+bet) / 5.0;
 
  printf("\n--- Student Result ---\n");
   printf("Maths   : %d\n", maths);
    printf("English : %d\n", english);
    printf("Physics : %d\n", physics);
    printf("fpl : %d\n", fpl);
    printf("bet: %d\n", bet);
   	if (maths < 35 || english < 35 || physics < 35 || fpl < 35 || bet < 35) {
        printf("Final Result: Fail  (One or more subjects below 35)\n");
	}
	 else if (average >= 90){
        printf(" Congratulations Merit GRADE A++\n");
	 }
    else if (average >= 75) {
        printf("Final Result:Congratulations Merit GRADE A \n"); 
	}
	    return 0;
}
