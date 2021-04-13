# HTML Links #
 Links allow users to click their way from page to page.

 In HTML, links are defined with the `<a>` tag:
```
 <a href="url">link text</a>
```
The href attribute specifies the destination address

The link text is the visible part 

Clicking on the link text, will send you to the specified address.

## Local Links ##
above we used an absolute URL (A full web address).

A local link (link to the same web site) is specified with a relative URL (without http://www....).

## HTML Links - Colors ##
When you move the mouse over a link, two things will normally happen:

The mouse arrow will turn into a little hand
The color of the link element will change
By default, a link will appear like this (in all browsers):

An unvisited link is underlined and blue
A visited link is underlined and purple
An active link is underlined and red
You can change the default colors, by using styles:

**Example**
```
<style>
a:link    {color:green; background-color:transparent; text-decoration:none}
a:visited {color:pink; background-color:transparent; text-decoration:none}
a:hover   {color:red; background-color:transparent; text-decoration:underline}
a:active  {color:yellow; background-color:transparent; text-decoration:underline}
</style>
```
## HTML Links - The target Attribute ##
The target attribute specifies where to open the linked document.
|Target Value|Description|
|---|---|
_blank|Opens the linked document in a new window or tab
_parent|Opens the linked document in the parent frame
_top|Opens the linked document in the full body of the window
framename|Opens the linked document in a named frame


This example will open the linked document in a new browser window or in a new tab:

**Example**
```
<a href="http://www.google.com/" target="_blank">Visit google!</a>
```
Use the HTML `<img>` element (inside `<a>`) to use an image as a link
Use the HTML `id` attribute (id="value") to define bookmarks in a page
Use the HTML` href` attribute (href="#value") to link to the bookmark

## JavaScript Functions ##
In JavaScript, a function allows you to define a block of code, give it a name and then execute it as many times as you want

that functions are declared with the following syntax:
```
function functionName(parameters) {
  // code to be executed
}
```
Function Parameters
A function can have one or more parameters, which will be supplied by the calling code and can be used inside a function. JavaScript is a dynamic type scripting language, so a function parameter can have value of any data type.

## css Layout ##
Key Concepts in Positioning Elements
Building Blocks

**CSS position** is how we determine the layout and design of a webpage. The CSS position is how we position each element in a document. This property is a single keyword, and we attach a value to it to set the specific position of an element.

There are five main values for the position property. We will define these in detail below:

- static
- relative
- absolute
- fixed
- sticky

**Position: static**

With this value, an element is positioned according to the flow of the document, and the helper properties have no effect. This means that if we want to move elements, static is of no use.

**Relative Positioning**

You can indicate that an element should be relatively positioned using the position property with a value of relative.

**Position: absolute**

An element using position: absolute is positioned relative to the nearest ancestor. In other words, an element with position:absolute is positioned relative to its parent element.

If an element doesn’t have a parent element, it’s placed relative to its initial containing block. It can then be positioned by the values of top, right, bottom, and left.

**Fixed Positioning**

Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed.

**Position: sticky**

position:sticky can be explained as a mixture of position:relative and position:fixed. At declaration, it acts like position:relative, but when scrolling, it acts like position:fixed.