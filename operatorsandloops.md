# COMPPARISON OPERATORS SUMMARY :


**EVALUATING CONDITIONS :**

 You can evaluate a situation by comparing one value in the script to what you expect it might be> the result will be a Boolean: true or false> .
- ***1- (==) IS EQUAL 
TO :***

    This operator compares tow values (numbers, string, or Booleans) to see if they are the same.

- 2- ***(!=) IS NOT EQUAL TO:***

    The operator compares tow values (numbers, sting, or Booleans) to see if they are not the same.

- 3- ***(===) STRICT EQUAL TO :***

    The operator compares tow values to check that both the type and value are the same.

- 4- ***(!==) STRICT NOT EQUAL TO:***

  The operator compares tow values to check that both the type and value are not the same.

- 5- ***(>) GREATER THAN :***

  The operator checks if the number on the left is great than the number on the right.

- 6- ***(<) LESS THAN :***

    The operator checks if the number on the left is less than the number on the right.

- 7- ***(>=) GREATER THAN OR EQUAL TO :***

    The operator checks if the number on the left is greater than or equal to the number on the right.

- 8- ***(<=) LESS THAN OR EQUAL TO :***

    The operator checks if the number on the left is less than or equal to the number on the right.

---

# LOGICAL OPERATORS :

Comparison operators usually return single values of true or false.
Logical operators allow you to compares the results of more than one comparison operator.

- 1- ***(!) LOGICAL NOT :***

    This operator takes a single Boolean value and inverts it.

- 2- ***`(||)` LOGICAL OR :***

    This operator test at least one condition.

- 3- ***(&&) LOGICAL AND :***

    This operator test more than one condition.

---

# SHORT-CIRCUIT EVALUATION :

Logical expressions evaluation left to right 
If the first condition can provide enough information to get the answer, then there is no need to evaluate second condition.


1-  ( *False && anything^It has found a false .* )

 2- *True `(||)`  anything 
^
It has found a true .* 




# LOOPS :

- Loops check a condition. If it returns true, a code block will run . Then the condition will be chacked again and if it still returns true , the code block will run again. It repeats until the coditions returns false .

**There are three common types of loops :**

1 - ***FOR :*** 

 If you need to run the code a specific number o times, use a for loops (It is the most common loop.) here the condition is usually a counter which is used to tell how many times the loop should run .

2-  ***WHILE :***

If you dint know how manytimes the code should run, you can use a while loop. Here the condition can be something other than a counter, and the code will continue to loop for as long as condition is true .

3- ***DO WHILE :***

The do..while loop is very similar to the while loop, but has one key difference. it will always run the statements inside the curly barces at least once, even if the condition evaluates to false.


