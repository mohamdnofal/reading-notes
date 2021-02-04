**The evolution of HTML:**

- Since the web was first created, there have
been several different versions of HTML. Each new version was designed to be an improvement by adding and removing elements and attributes.

- Not all web users will be able to view all of the latest features and
Markup as there are several versions of each browser used to view web pages (browsers not supporting certain features).

**HTML4 released 1997 :**


**XHTML 1.0 released 2000 :**

- to allow people to write new markup languages. HTML 4 should be reformulated to follow the rules of XML. This meant that authors had to follow more strict rules when writing markup. For example:

-  1- A closing tag (except for empty elements such as < img />).

- 2- Attribute names had to be in lowercase.

- 3- All attributes required a value, and all values were to be placed in double quotes.

- 4- Deprecated elements should no longer be used.

- 5- Every element that was opened inside another element should be closed inside that same element.

**HTML5 released 2000 :**

In HTML5, web page authors do not need to close all tags, and new elements and attributes will be introduced. writing, the HTML5 specification had not been completed.


***DOCTYPEs:***

DOCTYPE declaration to tell a browser which version of HTML the page is using : 

- HTML5
<! DOCTYPE html>

- HTML4
<! DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd"> 
- Transitional XHTML 1.0
<! DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">

- Strict XHTML 1.0
<! DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/ xhtml1-strict.dtd">

- XML Declaration
< ?xml version="1.0" ?>

**Comments in HTML : <!-- -->**

- Comments in HTML won’t be visible in the user’s browser. They can be viewed by anyone who looks at the source code behind the page.

- Comments should be added to describe the code to be easier to understand when you come back to it or when someone reads it.
Example: 

  ( <! -- comment goes here --> )


**ID Attribute :**

- It can be used with any HTML element  to uniquely identify that element from other elements on the page.
Giving an element a unique identity allows you to style it differently than any other Instance in the page
id attributes can be used to allow the script to work with that particular element which allows you to add interactivity to your pages.

**Class Attribute :**

- Every HTML element can also carry a class attribute. Sometimes, rather than uniquely identifying one element within a document.
The class attribute on any element can share the same value. It will only change their appearance if there is a CSS rule affecting the class.


- Block Elements
Blokes are the elements that will always appear to start on a new line in the browser window.
Examples of block elements are
< h1>, < p>, < ul>, and < l  i>.

**Inline Elements :**

- Inline elements will always appear to continue on the same line as their neighbouring elements.
Examples of inline elements are
< a>, < b>, < em>, and < img>.

**Grouping Text & Elements In a Block :**

- The < div> element allows you to group a set of elements together in one block-level box.

**Grouping Text & Elements Inline :**

- The <span> element acts like an inline equivalent of the <div> element. 



**IFrames :**

- An iframe is like a little window that has been cut into your page — and in that window you can see another page.

- 1- src :

  The src attribute specifies the URL of the page to show in the frame.

- 2- height :

  The height attribute specifies the height of the iframe in pixels.

- 3- width :

  The width attribute specifies the width of the iframe in pixels.



**Information About Your Pages:**

- The < meta> element lives inside the < head> element and contains information about that web page.



**HTML5 :**

- HTML5 is introducing a new set of elements that help define the structure of a page. Older browsers that do not understand HTML5 elements need to be told which elements are
block-level elements. To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed, which is available free from Google.


**Headers < header> & Footer < footer> :**

- The main hea 
der or footer
that appears at the top or
bottom of every page on the
site.

-  A header or footer for an
individual < article> or
< section> within the page.


**Navigation :**

- The < nav> element is used to contain the major navigational blocks on the site such as the primary site navigation.

**Articles < article> :**

- The < article> element acts as a container for any section of a page that could stand alone and potentially be syndicated.

**Aside < aside> :**

- The < aside> element has two purposes, depending on whether it is inside an < article> element or not.

**Sections < section> :**

- The < section> element groups related content together, and typically each section would have its own heading.

**Heading Groups < hgroup> :**

- The purpose of the < hgroup> element is to group together a set of one or more < h1> through < h6> elements so that they are treated as one single heading.

**Figures < figure> < figcaption> :**

- ***To display a figure could be:***

- 1- Images
- 2- Videos
- 3- Graphs
- 4- Diagrams
- 5- Code samples
- Text that supports the main body of an article
The < figure> element should also contain a < figcaption> element which provides a text description for the content of the < figure> element.




