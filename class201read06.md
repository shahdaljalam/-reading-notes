# WHAT IS AN OBJECT ? #

Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.


## PROPERTIES ##
In object variables become known as Properties
If a variable is part of an object, it is called a property. Properties tell us about the object .
## METHODS ##
In object functions become known as method
If a function is part of an object, it is called a method. Methods represent tasks that are associated with the object.

The variable have two type,

Local variable that declare in a scop of code block and we can't access it from outside the block.
Global variable that in declared outside any block un the code so we can access it from any where in the code.

# The Document Object Model (DOM)
Specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window

## MAKING A MODEL OF THE HTML PAGE ##

When the browser loads a web page, it creates a model of the page in memory. The DOM specifies the way in which the browser should structure this model using a **DOM tree**.

The DOM is called an object model because the model (the DOM tree) is made of objects.

Each object represents a different part of the page loaded in the browser window.

THE **DOM TREE** IS A MODEL OF A WEB PAGE
As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers’ memory. It consists of four main types of nodes.
- document nodes
- element nodes
- attibute nodes
- text nodes

can select element nodes by their id or class attributes,by tag name, or using CSS selector syntanx.

DOM query can return more than one node, it will always return a NodeList.

from an element node , you can access and update its content using properties such as textContent and innerHTML or usin DOM manipulation techniques.

an element node can contain multiple text nodes and child elements that are siblings of each other.

browsers offer tools for viewing the DOM tree.

## WORKING WITH THE DOM TREE

Accessing and updating the DOM tree involves two steps:

1- Locate the node that represents the element you want to work with.

2- Use its text content, child elements, and attributes.

## EXAMINING THE DOM IN FIREFOX

Firefox has similar built-in tools, but you can also download a DOM inspector tool that shows the text nodes.

## Problem Domain
A problem domain is the area of expertise or application that needs to be examined to solve a problem. A problem domain is simply looking at only the topics you are interested in, and excluding everything else. It is the area where the problems your application is intended to solve, belong to.

As programmers, we are often given inadequate information about the problem domain, and therefore lack the skills needed to comprehend it. We wrote code with the aim of constructing components that we had removed from the “bigger picture.”

If you understand the problem domain, programming is easy. I was given a pixel-perfect specification for a printer tab control and told precisely how it should work. Writing the coding for a function was a breeze. I’ve spent days trying to introduce a function only to have to go back and speak to a product owner about how and why anything can work the way it does. It’s not like being on an Agile team, where you have to describe the issue in depth to the product owner before writing code. It may be time-consuming, but it’s much more efficient th an hammering out a spec in a couple of hours. It also gives you a good picture of the problem.