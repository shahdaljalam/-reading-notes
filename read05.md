<img src ="https://th.bing.com/th/id/OIP.JTREM9zNjM9lRayTo_dJ_QHaCV?w=301&h=110&c=7&o=5&dpr=1.25&pid=1.7">

# COMPARISON OPERATORS: #
- Less than ``` (<) — ```  returns true if the value on the left is less than the value on the right, otherwise it returns false.
- Greater than ``` (>) — ``` returns true if the value on the left is greater than the value on the right, otherwise it returns false.
- Less than or equal to ``` (<=) — ``` returns true if the value on the left is less than or equal to the value on the right, otherwise it returns false.
- Greater than or equal to ` (>=) — ` returns true if the value on the left is greater than or equal to the value on the right, otherwise it returns false.
- Equal to ` " (===) — " ` returns true if the value on the left is equal to the value on the right, otherwise it returns false.
- Not equal to ` (!==) — ` returns true if the value on the left is not equal to the value on the right, otherwise it returns false.
# Logical Operators #
- we can assert whether two values or expressions are equal with ` === `, or, whether one value is greater than another with` > `.

- There are scenarios, however, in which we must assert whether multiple values or expressions are true. In JavaScript, we can use logical operators to make these assertions.

- ` && ` (and) — This operator will be truthy (act like true) if and only if the expressions on both sides of it are true.
- `||` (or) — This operator will be truthy if the expression on either side of it is true. Otherwise, it will be falsy (act like false).
- ` var isTrue = ('yellow' === 'green') && (4 >= 4); `

In the example above, we check if the string 'yellow' is equal to the string 'green' and (&&) if 4 is greater than or equal to 4. Let’s break this down into the two comparison expressions.
The first expression is false, because the string 'yellow' is not the same (equal) as the string 'green'.
The second expression is true, because the number 4 is greater than or equal to 4.
The && operator requires that both expressions be true in order for the expression to be truthy. Because one expression is false and the other is true, the expression is falsy and evaluates to false.

# LOOPS #
Loops check a condition. If It returns true, a code block will run. Then the condition will be checked again and if it still returns true, the code block will run again. It repeats until the condition returns false.

## There are three common types of loops : ##

### FOR ###
If you need to run code a specific number of times, use a for loop. ( it is the most common loop). In a for loop, the condition is usually a counter which is used to tell how many times the loop should run.

example

  ``` 
  for(var i = 0; i<10; i++ ) {
      document.write(i); 
  } 
  ```

### WHILE ###

If you do not know how many times the Code should run, you Can use a while loop. Here the condition can be something other than a counter, and the code will continue to loop for as long as the condition is true.
```
while (condition) {
  // code block to be executed
}
```
```while (i < 20) {
  text += "The number is " + i;
  i++;
}
```


