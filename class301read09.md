# Functional Programming #

## 1. What is functional programming? ##
Functional programming is a programming paradigmn -- a style of building the structure and elements of computer programs -- that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

## 2. What is a pure function and how do we know if something is a pure function?

the function is pure when it returns the same result if given the same arguments, and does not cause any observable side effects. 

## 3. What are the benefits of a pure function?

is that if the global variables ever used are changed, the value accurately scales with the edit

## 4. What is immutability?

When data is ummutable, its state cannot change after it's created. If you want to change an immutable obejct, you cant. Instead, you create a new object with the new value.

## 5. What is Referential transparency?

Referential transparency A function is considered a referentially transparent when we can replace it with a constant value. So, if a function consistently yields the same result for the same input, it is referentially transparent. Functions as first-class entities The idea is to treat functions as values and pass functions like data. This way we can combine different functions to create new functions with new behavior.
