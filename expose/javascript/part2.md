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

### Question 12
**Given the above Object, write the notation for:**

A. *Accessing the value of the name property in the student object*

*Answer:* `student.name`

B. *Accessing the value of the Grad Year property in the student object*

*Answer:* `student['Grad Year']`

C. *Calling the function for the greeting property in the student object*

*Answer:* `student.greeting()`

D. *Accessing the name property of the object in the Favorite Teacher property in student*

*Answer:* `student['Favorite Teacher'].name`

E. *Access index zero in the array of the courseLoad property of the student object*

*Answer:* `student.courseLoad[0]`

### Question 13
**Arithmetic**

A. `'3' + 2`

*Answer:* `'32'`

*Explanation:* The string `'3'` is concatenated with the number `2`, resulting in the string `'32'`.

B. `'3' - 2`

*Answer:* `1`

*Explanation:* JavaScript converts the string `'3'` to a number for the subtraction operation, resulting in the number `1`.

C. `3 + null`

*Answer:* `3`

*Explanation:* `null` is treated as `0` in numeric operations, so `3 + 0` equals `3`.

D. `'3' + null`

*Answer:* `'3null'`

*Explanation:* `null` is converted to a string in concatenation operations, so `'3'` concatenated with `'null'` equals `'3null'`.

E. `true + 3`

*Answer:* `4`

*Explanation:* `true` is converted to `1` in numeric operations, so `1 + 3` equals `4`.

F. `false + null`

*Answer:* `0`

*Explanation:* Both `false` and `null` are treated as `0` in numeric operations, so `0 + 0` equals `0`.

G. `'3' + undefined`

*Answer:* `'3undefined'`

*Explanation:* `undefined` is converted to a string in concatenation operations, so `'3'` concatenated with `'undefined'` equals `'3undefined'`.

H. `'3' - undefined`

*Answer:* `NaN`

*Explanation:* When `undefined` is involved in a subtraction operation, the result is `NaN` (Not a Number).
