# JavaScript Call Stack

## - What is a ‘call’?

A call is a function invocation, and a call stack is a hierarchy and ordering of these calls.

## - How many ‘calls’ can happen at once?

JavaScript is single-threaded so the function execution is done one-at-a-time from top to bottom.

## - What does LIFO mean?

LIFO means `(last in, first out)` data structure. It means that whichever one was most recently added, will be the first one to leave the stack when the function returns.

## - Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.



## - What causes a Stack Overflow?

This happens when there is: "a recursive function without an exit point." A recursive functions means a function that calls itself. A function can only call itself so many times before the limit of the call size has been exceeded.


## Error Messages 
----------------------
1. ’refrence error’ : This happens if you accidentally try to do something with a variable that doesn't exist yet.

2. ‘syntax error’ :This happens when you try to parse an invalid object using json.parse for example, but means you should use a different syntax

3. ‘tyep error’:You will commonly see cannot read property variable of undefined. This will happen when one tries to access something that hasn't been defined.

4.  ‘range error’:
When you try to give an object some invalid length

5. breakpoint:
This allows easier debugging for the line you add it on, it will make your program stop running when it hits that point and you can 'fiddle' with it in the developer console.

6. What does the word ‘debugger’ do in your code?

You need this keyword for adding a breakpoint

