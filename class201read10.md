# Error handling and debugging : #
Error handling, therefore, is a way to prevent a potentially disastrous error from halting program execution. Instead, if an error does occur, your program can inform the user in a much more user-friendly manner, and you can still retain control over the program. Debugging, on the other hand, involves finding errors and removing them from your program.

EXECUTION CONTEXT

* GLOBAL CONTEXT
Code that is in the script, but not in a function. There is only one global context on any page.
* FUNCTION CONTEXT:
Code that is being run within a function.Each function has its own function context.
* EVAL CONTEXT (NOT SHOWN):
Text is executed like code in an internal function called eval 

## (From the Duckett JS book:) ##
Error Handling & Debugging

Debugging is the process of finding errors. It involves a process of deduction.

The console helps narrow down the area in which the error is located, so you can try to find the exact error.

JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.

If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements.Use them to give your users helpful feedback.