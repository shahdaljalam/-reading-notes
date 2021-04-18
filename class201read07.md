# HTML table basics #
What is a table ?

A table is a structured set of data made up of rows and columns (tabular data). A table allows you to quickly and easily look up values that indicate some kind of connection between different types of data .

## Creating a table : ##
The content of every table is enclosed by these two tags : `<table></table>`. Add these inside the body of your HTML.
The smallest container inside a table is a table cell, which is created by a `<td> `element (`'td'` stands for 'table data'). Add the following inside your table tags:
````
<td>Hi, I'm your first cell.</td>
If we want a row of four cells, we need to copy these tags three times. Update the contents of your table to look like so:
<td>Hi, I'm your first cell.</td>
<td>I'm your second cell.</td>
<td>I'm your third cell.</td>
<td>I'm your fourth cell.</td>
````
As you will see, the cells are not placed underneath each other, rather they are automatically aligned with each other on the same row. Each <td> element creates a single cell and together they make up the first row. Every cell we add makes the row grow longer.

To stop this row from growing and start placing subsequent cells on a second row, we need to use the <tr> element ('tr' stands for 'table row'). Let's investigate this now.

Place the four cells you've already created inside <tr> tags, like so:
```
<tr>
  <td>Hi, I'm your first cell.</td>
  <td>I'm your second cell.</td>
  <td>I'm your third cell.</td>
  <td>I'm your fourth cell.</td>
</tr>
````
Now you've made one row, have a go at making one or two more — each row needs to be wrapped in an additional <tr> element, with each cell contained in a <td>.
This should result in a table that looks something like the following:

Hi, I'm your first cell. | I'm your second cell.| I'm your third cell.|I'm your fourth cell.
----|---|----|----
Second row,first cell.|	Cell 2.	|Cell 3.|	Cell 4.

## Adding headers with <th> elements ##
Now let's turn our attention to table headers — special cells that go at the start of a row or column and define the type of data that row or column contains

## Providing common styling to columns ##
 HTML has a method of defining styling information for an entire column of data all in one place — the <col> and <colgroup> elements. These exist because it can be a bit annoying and inefficient having to specify styling on columns — you generally have to specify your styling information on every <td> or <th> in the column, or use a complex selector such as :nth-child.