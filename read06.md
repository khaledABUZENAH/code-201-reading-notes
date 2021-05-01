# read06

## Object Literals

### What is an object?

Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.

* IN AN OBJECT: variables become known as **PROPERTIES** and functions as **METHODS**.

### Creating an Object: Literal Notation

it is the easiest and most popular way to creat objects
![objects](https://miro.medium.com/max/2012/1*gslNlU_BKtZuSyjLMbmp7Q.png)
as you can see her, dog1 is the ***object***. Name, colors, and age are **properties**, and "max", "brown" and "5" are **values**.
if we used a function to return one of these values, we call this function is that case as a **method**.


* you can access the properties or methods of an object using dot notation, you can also accsess properties using suqare brackets.

## The Document Object Model

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas:

* MAKING A MODEL OF THE HTML PAGE:
The DOM specifies the way in which the browser should structure this model using a DOM tree. And it's a model of a web page.

* ACCESSING AND CHANGING THE HTML PAGE:
The DOM also defines methods and properties to access and update each object in this model, which in turn updates what the user sees in the browser.


* The browser represents the page using a DOM tree.

* DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.

* You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax.

* Whenever a DOM query can return more than one node, it will always return a Nadel i st.

* From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques.

* An element node can contain multiple text nodes and child elements that are siblings of each other.

* In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).

* Browsers offer tools for viewing the DOM tree.



