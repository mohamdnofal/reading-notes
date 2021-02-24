# ERROR HANDLING & DEBUGGING

**CHAPTER 10:**

- JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.

***THE CONSOLE & DEV TOOLS:***

- Tools built into the browser that help you hunt for errors.

***COMMON PROBLEMS:***

- Common sources of errors, and how to solve them.
HANDLING ERRORS
How code can deal with potential errors gracefully.

**THE STACK:**

- When a statement has to call some other code in order to do its job, the new task goes to the top of the pile of things to do.

- Once the new task has been performed, the interpreter can go back to the task in hand. 

- Each time a new item is added to the stack, it creates a new execution context. 

- Variables defined in a function (or execution context) are only available in that function.
If a function gets called a second time, the variables can have different values.

- So, getName () is staşked on top of the greetUser () function. You can see the stack starting to build up. When getName () has PI!ng done its job, a value is returned "dn back to the greetUser () function.

- Since getName () has done its job, it is removed from the stack. In turn, the greetUser () function can now finish its job and returna value to the greeting variable.

 - The greetUser() function has finished its work and it is removed from the stack and the value is finally assigned to the greeting variable.