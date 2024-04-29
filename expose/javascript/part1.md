# Part 1:

### Question 1
**What is printed by line 9?**

*Answer:* `values added: 20`

*Explanation:* `result` is defined with `var` which has function scope, so it's accessible inside the `if` block.

### Question 2
**What is printed by line 13?**

*Answer:* `final result: 20`

*Explanation:* `result` is defined with `var` which has function scope, so it's accessible after the `if` block as well.

### Question 3
**What is printed by line 9?**

*Answer:* `values added: 20`

*Explanation:* `result` is defined with `let` inside the `if` block and is accessible there.

### Question 4
**What is printed by line 13? If the code returns an error, explain why.**

*Answer:*
*Error:* `ReferenceError - result is not defined`

*Explanation:* `result` is defined with `let` inside the `if` block, making it inaccessible outside of that block.

### Question 5
**What is printed by line 9? If the code returns an error, explain why.**

*Answer:*
*Error:* `TypeError - Assignment to constant variable.`

*Explanation:* `result` is declared with `const` and cannot be reassigned within the `if` block.

### Question 6
**What is printed by line 13? If the code returns an error, explain why.**

*Answer:*
*Error:* `ReferenceError - result is not defined`

*Explanation:* `result` is declared with `const` inside the `if` block and cannot be accessed outside of that block.
