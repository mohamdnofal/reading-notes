**CHAPTER 2**

# Text :

- When creating a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.

***Structural markup :***

- the elements that you can use to describe both headings and paragraphs

***Semantic markup :***
- which provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on .

**Headings :**

- HTML has six "levels" of headings:
( h1 )  is used for main headings ( h2 ) is used for subheadings if there are further sections under the subheadings then the ( h3 )element is used, and so on .

**Paragraphs :**
- To create a paragraph, surround the words that make up the paragraph with an opening () p ) tag and closing ( p ) tag. 

    By default, a browser will show each paragraph on a new line with some space between it and any subsequent paragraphs.

**Bold & iTalic :**
- By enclosing words in the tags ( b )and ( b ) we can make characters appear bold.

    By enclosing words in the tags (i) and (i) we can make characters appear italic.

**supersacrTipictl & e suBscript :**
- (sup) : 
The (sup) element is used
to contain characters that should be superscript such
as the suffixes of dates or mathematical concepts like raising a number to a power such as 22.

    (sub) : 
The (sub) element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H20.

**White space :**
- In order to make code easier to read, web page authors often add extra spaces or start some elements on new lines.

**line breaks & horizontal rules :**

- (br) : 
As you have already seen, the browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag (br) . 

- (hr) :
To create a break between themes — such as a change of topic in a book or a new scene
in a play — you can add a horizontal rule between sections using the (hr )tag.

**Visual ediTors & THeir code VieWs :**
- Content management systems and HTML editors such as Dreamweaver usually have two views of the page you are creating: a visual editor and a code view.

**semanTic markup :**
- There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages — they are known as semantic markup.

**STrong & emphasis :**
- (storng) :

    The use of the (strong) element indicates that its content has strong importance. For example, the words contained in this element might be said with strong emphasis.
By default, browsers will show the contents of a (strong) element in bold.

- (em) :

    The (em) element indicates emphasis that subtly changes the meaning of a sentence.
By default browsers will show the contents of an (em) element in italic.

**Quotaartiiocnles :**

- There are two elements commonly used for marking up quotations:

    1- (blockquote) :

    The (blockquote) element is used for longer quotes that take up an entire paragraph. Note how the (p) element is still used inside the (blockquote) element.
Browsers tend to indent the contents of the (blockquote) element, however you should not use this element just to indent a piece of text — rather you should achieve this effect using CSS.

    2- (q)
The (q) element is used for shorter quotes that sit within
a paragraph. Browsers are supposed to put quotes around the (q) element, however Internet Explorer does not — therefore many people avoid using the (q) element.
Both elements may use the cite attribute to indicate where the quote is from. Its value should be a URL that will have more information about the source of the quotation.

**Abbreviations & acronyms :**

(abbr) :    
If you use an abbreviation or an acronym, then the (abbr) element can be used. A title attribute on the opening tag is used to specify the full term.

(cite) :    
When you are referencing a piece of work such as a book, film or research paper, the (cite) element can be used to indicate where the citation is from.

(dfn) : 
The first time you explain some new terminology (perhaps an academic concept or some jargon) in a document, it is known as the defining instance of it.

**Author details :**

(address):  
The (address) element has quite a specific use: to contain contact details for the author of the page.

(ins) (del) :   
The (ins) element can be used to show content that has been inserted into a document, while the (del) element can show text that has been deleted from it.

(s):
The (s) element indicates something that is no longer accurate or relevant (but that should not be deleted).

**Chapter 10**
# Introducing CSS :

**underStandIng cSS:** 

- thinking inside the box  
    The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

**BLock & Inline eLements :**
 - Block level elements look
like they start on a new line. Examples include the (h1)- (h6), (p) and (div) elements.


CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.



**CSS aSSociates styLe rukes with html eLements :**

 - CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. 
A CSS rule contains two parts:

    1- Selectors : indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.

    2-Declarations : indicate how
the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value), and are separated by a colon.

**Css propertieS affect how elements are displayed :**

- CSS declarations sit inside curly brackets and each is made up of two parts: 

    1- Properties :
    
     indicate the aspects of the element you want to change. For example, color, font, width, height and border.

    2- Values :
    
    
     specify the settings
you want to use for the chosen properties. For example, if you want to specify a color property then the value is the color you want the text in these elements to be.

**using externaL css :**

1- (link) :
The (link) element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the (head) element. It should use three attributes:

    1- href
    2- type
    3- rel 

2- (style) :

You can also include CSS rules within an HTML page by placing them inside a (style) element, which usually sits inside the ( head ) element of the page.

**Css SeLectors :**

- There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document.
The table on the opposite page introduces the most commonly used CSS selectors.
On this page, there is an HTML file to demonstrate which elements these CSS selectors would apply to.
CSS selectors are case sensitive, so they must match element names and attribute values exactly.
There are some more advanced selectors which allow you
to select elements based on attributes and their values .


**how cSS ruLeS caScade :**
- If there are two or more rules that apply to the same element, it is important to understand which will take precedence.

**Inheritance :**
- If you specify the font-family or color properties on the <body> element, they will apply to most child elements. This is because the value of the font-family property is inherited by child elements. It saves you from having to apply these properties to as many elements (and results in simpler style sheets).
You can compare this with
the background-color or border properties; they are not inherited by child elements. If these were inherited by all child elements then the page could look quite messy.
----

**CHAPTER 2 JAVA SCRIPT :**
# Basic JavaScript Instructions


**STATEMENTS :**
- A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement.
Statements should end with a semicolon.

-  JavaScript is case sensitive so hourNow means
something different to HourNow or HOURNOW.

- A statement is an individual instruction that the computer should follow. Each one should start on a new line and end with a semicolon. This makes your code easier to read and follow.

- Some statements are surrounded by curly braces; these are known as code blocks. The closing curly
brace is not followed by a semicolon.

**COMMENTS :**

You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code .

- 1- MULTI-LINE COMMENTS : 

    To write a comment that stretches over more than one line, you use a multi-line comment, starting with the /* characters and ending with the */ characters. Anything between these characters is not processed· by the JavaScript interpreter.

- 2- SINGLE-LINE COMMENTS :

    In a single-line comment, anything that follows the two forward slash characters I/ on that line will not be processed by the JavaScript interpreter. Single- line comments are often used for short descriptions of what the code is doing.

**WHAT IS A VARIABLE?**

- A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.
When you write JavaScript, you have to tell the interpreter every individual step that you want it to perform. This sometimes involves more detail than you might expect.

**DATA TYPES :**
- JavaScript distinguishes between numbers, strings, and true or false values known as Booleans.


**SHORTHAND FOR CREATING VARIABLES :**

Programmers sometimes use shorthand to create variables. Here are three variations of how to declare variables and assign them values:
1. Variables are declared and values assigned in the same statement.
2. Three variables are declared on the same line, then values assigned to each.
3. Two variables are declared and assigned values on the same line. Then one is declared and assigned a value on the next line.
4. Here, a variable is used to hold a reference to an element in the HTML page. This allows you to work directly with the element stored in that variable. (See more about this on p190.)

**CHANGING THE VALUE OF A VARIABLE :**

- Once you have assigned a value to a variable, you can then change what is stored in the variable later in the same script.
Once the variable has been created, you do not need to
use the var keyword to assign
it a new value. You just use the variable name, the equals sign (al so known as t he assignment operator), and the new value for that attribute.

**RULES FOR NAMING VARIABLES :**

Here are six rules you must always follow when giving a variable a name :

1. The name must begin with
a letter, dollar sign ($),or an underscore (_). It must not start with a number.

2. The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name.

3. You cannot use keywords or reserved words. Keywords
are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of JavaScript.

4. All variables are case sensitive, so score and Score would be different variable names, but
it is bad practice to create two variables that have the same name using different cases. 

5. Use a name that describes the kind of information that the variable stores. For example, fi rstName might be used to store a person's first name,
l astNarne for their last name, and age for their age.

6. If your variable name is made
up of more than one word, use a capital letter for the first letter of every word after the first word. For example, f i rstName rather than fi rstnarne (this is referred to as camel case). You can also use an underscore between each word (you cannot use a dash).

**ARRAYS :**

- An array is a special type of variable. It doesn't just store one value; it stores a list of values.

***CREATING AN ARRAY :***
- You create an array and give it
a name just like you would any other variable (using the var keyword followed by the name of the array).

***VALUES IN ARRAYS :***
- Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).

**EXPRESSIONS :**
- An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions :

1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE :
    In order for a variable to be useful, it needs to be given a value. As you have seen, this is done using the assignment operator (the equals sign).

2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE :
    You can perform operations on any number of individual values (see next page) to determine a single value. 

**OPERATORS :**

Expressions rely on things called operators; they allow programmers to create a single value from one or more values.

**ARITHMETIC OPERATORS :**

   JavaScript contains the following mathematical operators, which you can use with numbers. You may remember some from math class.

**STRING OPERATOR :**

   There is just one string operator: the+ symbol. It is used to join the strings on either side of it.


----
**CHAPTRER 4**
# DECISIONS & LOOPS :

**EVALUATING CONDITIONS :**

 You can evaluate a situation by comparing one value in the script to what you expect it might be> the result will be a Boolean: true or false> .
- ***1- (==) IS EQUAL 
TO :***

    This operator compares tow values (numbers, string, or Booleans) to see if they are the same.

- 2- ***(!=) IS NOT EQUAL TO:***

    The operator compares tow values (numbers, sting, or Booleans) to see if they are not the same.

- 3- ***(===) STRICT EQUAL TO :***

    The operator compares tow values to check that both the type and value are the same.

- 4- ***(!==) STRICT NOT EQUAL TO:***

  The operator compares tow values to check that both the type and value are not the same.

- 5- ***(>) GREATER THAN :***

  The operator checks if the number on the left is great than the number on the right.

- 6- ***(<) LESS THAN :***

    The operator checks if the number on the left is less than the number on the right.

- 7- ***(>=) GREATER THAN OR EQUAL TO :***

    The operator checks if the number on the left is greater than or equal to the number on the right.

- 8- ***(<=) LESS THAN OR EQUAL TO :***

    The operator checks if the number on the left is less than or equal to the number on the right.

---

# LOGICAL OPERATORS :

Comparison operators usually return single values of true or false.
Logical operators allow you to compares the results of more than one comparison operator.

- 1- ***(!) LOGICAL NOT :***

    This operator takes a single Boolean value and inverts it.

- 2- ***`(||)` LOGICAL OR :***

    This operator test at least one condition.

- 3- ***(&&) LOGICAL AND :***

    This operator test more than one condition.

---

# SHORT-CIRCUIT EVALUATION :

Logical expressions evaluation left to right 
If the first condition can provide enough information to get the answer, then there is no need to evaluate second condition.


1-  ( *False && anything^It has found a false .* )

 2- *True `(||)`  anything 
^
It has found a true .* 




# LOOPS :

- Loops check a condition. If it returns true, a code block will run . Then the condition will be chacked again and if it still returns true , the code block will run again. It repeats until the coditions returns false .

**There are three common types of loops :**

1 - ***FOR :*** 

 If you need to run the code a specific number o times, use a for loops (It is the most common loop.) here the condition is usually a counter which is used to tell how many times the loop should run .

2-  ***WHILE :***

If you dint know how manytimes the code should run, you can use a while loop. Here the condition can be something other than a counter, and the code will continue to loop for as long as condition is true .

3- ***DO WHILE :***

The do..while loop is very similar to the while loop, but has one key difference. it will always run the statements inside the curly barces at least once, even if the condition evaluates to false.














