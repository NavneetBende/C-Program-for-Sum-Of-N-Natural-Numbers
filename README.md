# C-Program-for-Sum-Of-N-Natural-Numbers


Find the Sum of N Natural Numbers in C
Given an integer input num, the objective is to write a code to find the Sum of N Natural Numbers in C. To do so we iterate and add all the numbers until num.

Example:
Input : 5
Output : 1 + 2 + 3 + 4 + 5 = 15
While loop in C
Algorithm
The Algorithm for the above problem is as follows,

Step 1. Start
Step 2. Enter a number (N).
Step 3. Use “For loop” to iterate  upto the user inserted value. 
Step 4. The “For loop” will calculate the sum of the user inserted value. 
Step 5. Stop
Let’s try and understand it better using the Image given below.

C Program for Sum Of N Natural Numbers
#include <stdio.h>
int main() 
{ 
    //for initialize variable
    int Number, i, Sum = 0;
    //to take user input
    printf ("\n Kindly Insert an Integer Variable\n");
    scanf ("%d", &Number);

    //use for loop for these condition
    for(i = 1; i <= Number; i++)
    {
         Sum = Sum + i;
    }

    //display
    printf ("Sum of Natural Numbers = %d", Sum);

    return 0;
}
Output
Kindly Insert an Integer Variable : 3 
Sum of Natural Numbers = 6
