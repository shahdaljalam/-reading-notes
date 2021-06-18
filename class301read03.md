# Passing Functions as Props

## What does .map() return? ##
it returns an array with a length is equal to the original (maped) array.

## If I want to loop through an array and display each value in JSX, how do I do that in React? ##
we loop through the numbers array using the JavaScript map() function. We return a < li > element for each item. Finally, we assign the resulting array of elements to listItems

### Each list item needs a unique 
< li > tag . ###

## What is the purpose of a key? ##
Keys help React identify which items have changed, are added, or are removed.

## What is the spread operator? ##
In JavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

## things that the spread operator can do. ##
- Concatenating or combining arrays

-Using an array as arguments

- Adding to state in React

- Converting NodeList to an array

## an example of using the spread operator to combine two arrays. ##
- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments
- Adding an item to a list

## an example of using the spread operator to add a new item to an array. ##


## an example of using the spread operator to combine two objects into one. ##

## the first step that the developer does to pass functions between components ##
He should increment and pass inide it the object from the function, then he uses the map function

## what does the increment function do? ##
It helps us to know what is the next node in the same level. 

## How can you pass a method from a parent component into a child component? ##
First we define our parent callback function in the parent component, then we pass the function to the child component, after that we set up an input variable in the child component and the last thing is the callback function.

## How does the child component invoke a method that was passed to it from a parent component? ##
Using the 'this' method that calls the method passed to it from the main component.