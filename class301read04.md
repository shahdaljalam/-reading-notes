# React and Forms #

## `Controlled Component` ##
1- What is a Controlled Component?

In HTML, form elements such as `<input>`, `<textarea>`, and `<select>` typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.

2- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

we update the value in state with their responses as soon as they enter them , so the display value will update as the user tyoes.

3- How do we target what the user is entering if we have an event handler on an input field?

by using the (event.target.name)for that input filed.

- Why would we use a ternary operator?

 it's to simplify our if-else statements that are used to assign values to variables.
 faster and less code, it can be written in one line.


- Rewrite the following statement using a ternary statement

```
 if(x===y){

console.log(true);}

else{

console.log(false);}

x===y ? console.log(true) : console.log(false) 
```

--------------------------