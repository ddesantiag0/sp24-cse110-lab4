# Part 2

### Question 1
**What will happen at line 12 and why? If the code causes an error, explain why.**

*Answer:* `3`

### Question 2
**What will happen at line 13 and why? If the code causes an error, explain why.**

*Answer:* `150`

### Question 3
**What will happen at line 14 and why? If the code causes an error, explain why.**

*Answer:* Line 14 will print the finalPrice calculated from the last iteration of the for loop which the item in the array prices is 300 and given the 0.5 discount, which makes the final output `150`.

### Question 4
**What will this function return? Give a brief explanation why. If the code causes an error, explain why.**

*Answer:* The function will return the array `[50, 100, 150]`. It calculates the discounted price for each original price in the input array, applies a 50% discount, rounds the result to the nearest cent, and stores these final prices in the `discounted` array.

### Question 5
**What will happen at line 11 and why? If the code causes an error, explain why.**

*Answer:*

*Error:*
`ReferenceError - i is not defined`

*Explanation:*
`i` does not exist outside of the loop, so attempting to log it to the console after the loop has completed causes a reference error.
