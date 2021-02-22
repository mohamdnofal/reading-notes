# TABLES

**chapter 6:**

---

***What's a Table?***

- A table represents information in a grid format.

**Basic Table Structure:**

- 1- `<table>`

The `<table>` element is used to create a table. The contents of the table are written out rowby row.

- 2- `<tr>` You indicate the start of each row using the opening `<tr>` tag.

(The tr stands for table row.) It is followed by one or more
`<td>` elements (one for each cellin that row). 
At the end of the row you use aclosing `</tr>` tag.

- 3- `<td>` Each cell of a table is represented using a `<td>` element. (The td stands for table data.)
At the end of each cell you use aclosing </td> tag. Some browsers automatically
draw lines around the table and/or the individual cells.

- 4- Table Heading `<th>` Using elements for headings helps people who use screen readers, improves the ability for search engines to index your pages, and also enables you to control the appearance of tables better when you start to use CSS.

Spanning Columns
Sometimes you may need the entries in a table to stretch across more than one column.
The colspan attribute can be used on a `<th>` or `<td>` element and indicates how many columns that cell should run across.
Spanning Rows
You may also need entries in a table to stretch down across more than one row.
The rowspan attribute can be used on a or element to indicate how many rows a cell should span down the table.

Long Tables
There are three elements that help distinguish between the main content of the table and the first and last rows (which can contain different content). These elements help people who use screen readers and also allow you to style these sections in a different manner than the rest of the table.

`<thead>`:
The headings of the table should sit inside the element.

`<tbody>`:
The body should sit inside the element.

`<tfoot>`:
The footer belongs inside the element.
By default, browsers rarely treat the content of these elements any differently than other elements however designers often use CSS styles to change their appearance.

Some of the HTML editors that come in content management
systems offer tools to help draw tables. If the first row of your table only contains `<th>` elements, then you may find that the editor inserts a `<thead>` element automatically.

**Old Code:**

1- Width & Spacing :

- The width attribute was used on the opening `<table>` tag to indicate how wide that table should be and on some opening `<th>` and `<td>` tags to specify the width of individual cells. The value of this attribute is the width of the table or cell in pixels.
The columns in a table need to form a straight line, so you often only see the width attribute on the first row (and all subsequent rows would use that setting).
The Opening `<table>` tag could also use the cellpadding attribute to add space inside each cell of the table, and the cellspacing attribute to create space between each cell of the table. The values for these attributes were given in pixels.

2- Border & Background:

- The border attribute was used on both the `<table>` and `<td>` elements to indicate the width of the border in pixels.
The bgcolor attribute was used to indicate background colors of either the entire table or individual table cells. The value is usually a hex code.

---
# FUNCTIONS, METHODS, AND OBJECTS

**CHAPTER 3:**

***Creating an object constructor notation:***

- 1-First, you create a new object using a combination of the new keyword and the Object () constructor function. (This function is part of the JavaScript language and is used to create objects.) 

- 2-Next, having created the blank object, you can add properties and methods to it using dot notation. Each statement that adds a property or method should end with a semicolon.

- 3-You can use this syntax to add properties and methods to any object you have created (no matter which notation you used to create it).

- 4-To create an empty object using literal notation use: {}.
The curly brackets create an empty object.

**Updating an object:**

- 1-To update a property, use the same technique that was shown on the left-hand page to add properties to the object, but give it a new value.

- 2-If the object does not have the property you are trying to update, it will be added to the object.

- 3-You can also update the properties of an object (but not its methods) using square bracket syntax. The object name is followed by square brackets, and the property name is inside them.

- 4-A new value for the property is added after the assignment operator. Again, if the property you are attempting to update does not exist, it will be added to the object.

- 5-To delete a property, use the delete keyword.

- 6-If you just want to clear the value o f a property, you could set It to do a blank string.

***CREATING MANY OBJECTS:***

- CONSTRUCTOR NOTATION:

Sometimes you will want several objects to represent similar things. Object constructors can use a function as a template for creating objects. First, create the template with the object's properties and methods.
You create instances of the object using the constructor function. The new keyword followed by a call to the function creates a new object. The properties of each object are given as arguments to the function.

- ARRAYS ARE OBJECT:

Arrays are actually a special type of object. They hold a related set of key/value pairs (like all objects), but the key for each value is its index number.

- ARRAYS OF OBJECTS & OBJECTS IN ARRAYS:

You can combine arrays and objects to create complex data structures: Arrays can store a series of objects (and remember their order). Objects can also hold arrays (as values of their properties).
In an object, the order in which the properties appear is not important. In an array, the index numbers dictate the order of the properties.

 - - ARRAYS IN AN OBJECT:

    The property of any object can hold an array. On the left, each item on a hotel bill is stored separately in an array.

- - OBJECT IN AN ARRAYS:

    The value of any element in an array can be an object (written using the object literal syntax)

- ***Three groups of built –in object:***

    1- BROWSER OBJECT MODEL:
    The Browser Object Model creates a model of the browser tab or window.

    2- DOCUMENT OBJECT MODEL:

    The Document Object Model (DOM) creates a model of the current web page.

    3- GLOBAL JAVASCRIPT OBJECTS:

    The global objects do not form a single model. They are a group of individual objects that relate to different parts of the JavaScript language.

**Creating an instance of the date object:**

- To create a Date object, use the Date () object constructor. The syntax is the same for creating any object with a constructor function. You can use it to create more than one Date object.


