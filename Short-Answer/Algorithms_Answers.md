#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n): No matter how big "A" becomes the while loop only does one operation of True or False. Arithmetic operations
have a time complecity of O(n).


b)O(n^2): There is a while loop nested in a for loop. The while loop needs to run for every element in the for loop the
of operations increases expotentially. 


c)O(n): No matter how may times it does a call stack the highest cost operation is arithmatic which has a time complexity of  O(n).

## Exercise II
I would impliment a binary search. start in at the middle most floor level. if the egg breaks then im too high. I can 
eliminate all the higher floors as well.
Then I find the new mid floor of the lower floors. If the egg does not break im no low and eliminate the rest of the
lower levels. repeat until i have 2 floors left. I start at the lower floor if the egg breaks then thats 'F' if the egg
does not break then there only 1 floor left so that has to be "F" by elimnation

