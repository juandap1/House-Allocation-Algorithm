# House-Allocation-Algorithm
# Google KickStart Round A allocation problem
# Problem

There are N houses for sale. The i-th house costs Ai dollars to buy. You have a budget of B dollars to spend.
What is the maximum number of houses you can buy?

# Solution
Step 1
There are N number of Houses
Step2
There are A dollar to buy houses
step3
Budget B dollar to spend

To get the maximum amount of houses you can buy, the user must input the total number of houses, the individual prices of these house separated by space or comma
budgeted amount and number of test cases

Next split the prices and convert string to an array and convert prices to integers. Afterwards
Sort the elelments in the array in an increasing order.

Write a loop to check if the lowest isequal to or greater than B the budget.
Then add the next element of the array and check again.
Boom you get the maximum number of houses that can be purchased base on the budgeted amount.
