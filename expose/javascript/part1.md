<h2 align="center">Part 1:</h2>

## Question 1
**What is printed by line 9? If the code returns an error, explain why.**

*Answer:* 

`values added: 20`

## Question 2
**What is printed by line 13? If the code returns an error, explain why.**

*Answer:*

`final result: 20`

## Question 3
**What is printed by line 9? If the code returns an error, explain why.**

*Answer:*

`values added: 20`

## Question 4
**What is printed by line 13? If the code returns an error, explain why.**

*Answers:*

*Error:*
`ReferenceError - result is not defined`

*Explanation:*
Line 13 is outside of the block so that 'result' isn't accessible because it is only available inside the '{ }' where it was created because of 'let'

## Question 5
**What is printed by line 9? If the code returns an error, explain why.**

*Answers:*

*Error:*
`TypeError - Assignment to constant variable.`

*Explanation:*
The 'result' is a constant and can't be changed after it's set and it was attempted to be reassigned.

## Question 6
**What is printed by line 13? If the code returns an error, explain why.**

*Answers:*

*Error:*
`ReferenceError - result is not defined`

*Explanation:*
`result` declared with `const` is not accessible outside the block it was defined in. Line 13 is outside that block and cannot reference `result`.
