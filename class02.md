## text
when you create a web page, you add tags to the contents of it. These tags provide extra meaning to the page and allow browsers to show users the apropriate structure for the page, and we have two different types of tags:

* **structural markup**(tags):
it's used to describe both headings and paragraphs.
* **semantic markup**: 
provides extra information.

### headings 
![headings](https://www.tutorialrepublic.com/lib/images/html/html-headings.png)

HTML has six levels of headings, **<h1>** is used for main headings,**<h2>** is used for subheading, **<h3>** is smaller and less important and so on.

### paragraph
![paragraphs](https://i.pinimg.com/originals/50/9b/d9/509bd991e8c50c31c3c55e53a6e2f8e5.png)
To create a paragraph, surround the words that make up the paragraph with an opening **<p>** tag and closing **</p>** tag. And by enclosing words in the tags **<b>** and **</b>** we can makecharacters appear bold. By enclosing words in the tags **<i>** and **</i>** we can make characters appear italic.

### superscript and subscript
![subsup](https://www.oreilly.com/library/view/web-standards-programmers/9780764588204/9780764588204_superscript_comma_subscript_comma_big_co_image01.png)
 
 * The **<sup>** element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 22.

 * The **<sub>** element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H20.

### line breaks and horizontal rules

 * as you see in the photo below, if you wanted to add a line break inside the middle of a paragraph you can use the line break tag **<br />**.
 ![linebreak](https://ptgmedia.pearsoncmg.com/images/chap4_9780321719614/elementLinks/04_22.jpg)
 
 * To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the **<hr />** tag.
 ![rule](https://media.geeksforgeeks.org/wp-content/uploads/Screen-Shot-2018-09-27-at-4.31.37-AM.png)



## semantic markup
There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages — they are known as semantic markup.

### strong and emphasis

* The use of the **<strong>** element indicates that its content has strong importance.
* The **<em>** element indicates emphasis that subtly changes the meaning of a sentence. This will be showq as italic.

### quotations

* The **<blockquote>** element is used for longer quotes that take up an entire paragraph. Note how the **<p>** element is still used inside the **<blockquote>** element.

* The **<q>** element is used for shorter quotes that sit within a paragraph.

### abbreviations and acronyms

* If you use an abbreviation or an acronym, then the <abbr> element can be used. A title attribute on the opening tag is used to specify the full term.

### citations and definitions

* When you are referencing a piece of work such as a book, film or research paper, the **<cite>** element can be used to indicate where the citation is from.
* The **<dfn>** element is used to indicate the defining instance of a new term.

### authors details

The **<address>** element has quite a specific use: to contain contact details for the author of
the page.

### changes to content 

* The **<ins>** element can be used to show content that has been inserted into a document, while the <del> element can show text that has been deleted from it.
![insdel](https://static.javatpoint.com/htmlpages/images/html-ins-tag.png)

* The **<s>** element indicates something that is no longer accurate or relevant (but that should not be deleted).

## Introducing CSS

CSS allows you to create rules that specify how the content of an element should appear.

* CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

![css](https://cdn.lynda.com/video/433961-111-635784530255453630_338x600_thumb.jpg)

* CSS properties affects how the element will be displayed.

### using external css

The **<link>** element can be used in an HTML document to tell the browser where to find the CSS file used to style the page and it lives insede the head element. It should use three attributes:

* **rel**
This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.
* **href**
This specifies the path to the CSS file (which is often placed in a folder called css or styles).
* **type**
This attribute specifies the type of document being linked to. The value should be text/css.

### using internal css

You can also include CSS rules within an HTML page by placing them inside a **<style>** element, which usually sits inside the **<head>** element of the page.
![internal](https://codebridgeplus.com/wp-content/uploads/InternalCSSInternalstylingisdefinedinthe_head_sectionofanHTMLpageusinga_style_element..jpg)

## Basic JavaScript Instructions

1. statements
A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.
Some statements are surrounded by curly braces; these are known as code blocks. The closing curly brace is not followed by a semicolon>


![blocks](https://codecondo.com/wp-content/uploads/2015/04/1.gif)

2. comments 
You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code.

 -  multiple line comments: To write a comment that stretches over more than one line, you use a multi-line comment, starting with
the /* characters and ending with the * / characters. Anything between these characters is not processed· by the JavaScript interpreter.

 -  single line comments: anything that follows the two forward slash characters I/ on that line will not be processed by the JavaScript interpreter. Singleline comments are often used for short descriptions of what the code is doing.

 
3. variables 

A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables. A variable is a good name for this
concept because the data stored in a variable can change each time a script runs.

* ypu can put in the variables; strig operators and arithmatic operators>

### using a variable to store a boolian

![boolian](https://www.includehelp.com/code-snippets/Images/boolean-in-js-1.jpg)

### arrays

An array is a special type of variable. It doesn't just store one value; it stores a list of values.

## Decisions and Loops

### comparison operators
you can evaluate a situation by comparing one value in the script to what you expect it maight be. The result wil be a boolean.

 * **==** : is equal to, compares only the value.
 * **!=** : is not equal to, compares only the value.
 * **===** : strict equal to, compares the value and the datatype.
 * **!==** : a strict not equal t, it also compares the value and the datatype.
 * **<** :greater than.
 * **>** :less than.
 * **>=** :greater than or equal to.
 * **<=** :less than or equal to.


### logical operators

![logical](https://miro.medium.com/max/480/1*YKB4AzklPRAbvYtDkZEkYQ.png)

It allowes you compare the results of more than one condition.

* the logical and(**&&**):
this operator tests more than one condition.
(false && anything = false)

* the logical or( **||** ):
this operator  tests at least one condition.
(true || anything = true)

* logical not (**!**):
this operator takes a single operator value and inverts it. 
! true = false
! false = true

### loops: 

loops check a condition, if it's true, a code block will run, then the condition will be checked again and if it's still true, the code block will run again and again until the condition is false. There are three common types of loops, for, while, and do while:

* **for loop**
![for](https://www.tutorialspoint.com/cprogramming/images/cpp_for_loop.jpg)

A for loop is a repetition control structure that allows you to write a loop that needs to run a specific number of times. for example, if you want to execute a loop for 12 time, the code will be like that:

***for( i = 0; a < 12; i++ )***


* **while loop**
![while](https://upload.wikimedia.org/wikipedia/commons/thumb/4/43/While-loop-diagram.svg/220px-While-loop-diagram.svg.png)

you can use it if you don't know how many times the code should run, the code will continue to loop as long as the condition is true.







 


