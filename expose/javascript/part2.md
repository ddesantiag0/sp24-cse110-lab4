# Part 2

### Question 1
**What will happen at line 12 and why?**

*Answer:* `3`

*Explanation:* The `length` variable is accessible within the function's scope.

### Question 2
**What will happen at line 13 and why?**

*Answer:* `150`

*Explanation:* `finalPrice` retains the last computed value which is accessible within the function's scope.

### Question 3
**What will happen at line 14 and why?**

*Answer:* Prints `150`, the finalPrice from the last loop iteration.

*Explanation:* Since `finalPrice` is within the function's scope, it's accessible after the loop.

### Question 4
**What will this function return?**

*Answer:* `[50, 100, 150]`

*Explanation:* It computes half of each original price due to the 50% discount.

### Question 5
**What will happen at line 11 and why?**

*Answer:*
*Error:* `ReferenceError - i is not defined`

*Explanation:* `i` is block-scoped to the `for` loop and is not accessible outside it.

### Question 6
**What will happen at line 13 and why?**

*Answer:*
*Error:* `ReferenceError - discountedPrice is not defined`

*Explanation:* `discountedPrice` is block-scoped to the `for` loop and is not accessible outside it.

### Question 7
**What will happen at line 14 and why?**

*Answer:* Prints `150`, the finalPrice for the last item after the discount.

*Explanation:* `finalPrice` is declared at the function level and is accessible at line 14.

### Question 8
**What will this function return?**

*Answer:* `[50, 100, 150]`

*Explanation:* The function halves each price in the array and returns the discounted prices.

### Question 9
**What will happen at line 11 and why?**

*Answer:*
*Error:* `ReferenceError - i is not defined`

*Explanation:* `i` is block-scoped to the `for` loop and is not accessible outside it.

### Question 10
**What will happen at line 12 and why?**
*Answer:* `3`


*Explanation:* `length` is a constant within the function scope and accessible at line 12.

### Question 11
**What will this function return?**

*Answer:* `[50, 100, 150]`

*Explanation:* The function halves each price in the array due to the discount and returns the new values.
