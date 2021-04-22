This question involves computing factorials and using factorials to compute the number of possible ways that items can be selected from a group of choices. You will write two methods in the Combinatorics class that follows.

In mathematics, the factorial of a positive integer n, denoted as n! , is the product of all positive integers less than or equal to n.

The factorial of n can be computed using the following rules.

Case I: If n is 1, then the factorial of n is 1.
Case II: If n is greater than 1, then the factorial of n is equal to n times the factorial of (n - 1).
The factorial method returns the factorial of n, as determined by case I and case II.

(a) Write the factorial method. You are encouraged to implement this method recursively.

A combination is a selection of items from a group of choices when the order that the items are selected does not matter. For example, if there are four available choices (A, B, C, and D), there are six different ways that two items can be selected (A and B, A and C, A and D, B and C, B and D, C and D). The number of possible combinations of r items from a group of n choices can be calculated according to the following rules.

If r is greater than n, then the number of possible combinations is 0.
If r is not greater than n, then the number of possible combinations is equal to n!÷(r!(n−r)!).
The numCombinations method is intended to calculate the number of possible combinations of r items from a group of n choices and print the result.

(b) Write the numCombinations method below. Assume that factorial works as specified, regardless of what you wrote in part (a). You must use factorial appropriately to receive full credit.