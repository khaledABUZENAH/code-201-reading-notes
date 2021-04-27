# read04

## links
Links are the defining feature of the web because they allow you to move from one web page to another.

### writing links 

Links are created using the <a> element. Users can click on anything between the opening <a> tag and the closing </a> tag. The text between the opening <a> tag and closing </a> tag is known as link text. Where possible, your link text should explain where visitors will be taken if they click on it.

### Linking to other pages on the same site.
When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL, which is the name of the file.the extention of it.

### email links
 To create a link that starts up the user's email program and addresses an email to a specified email address, you use the <a> element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.

 ### opining links in a new window

If you want a link to open in a new window, you can use the target attribute on the opening <a> tag. The value of this attribute should be _blank.

## Key Concepts in Positioning Elements

CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

* Block-level elements start on a new line

* Inline elements flow in between surrounding text

### containing elements

If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

## Functions, Methods, and Objects

Browsers require very detailed instructions about what we want them to do. Therefore, complex scripts can run to hundreds (even thousands) of lines. Programmers use functions, methods, and objects to organize their code.

### functions

**FUNCTIONS**:
Functions consist of a series of statements that have been grouped together because they preform a specific task. We use them to avoid repeating the same statements. In order to make the function perform, tou need to give it a name, when you ask it to perform it's task, it is know as calling the function. Some Functions need to be provided with information in order to achieve a given task, like if you want to calculate the area or the average, these informations are known as parameters. When you write a function and you expect it to provide you with an answer, the response is known as a return value. There are two methods of using functions, declaring functions and funcrions expressions.

**Function declaration**:
to create a function, you give it a name then write the statements needed to perform the task inside the curly braces, then you execute all the statements between the curly braceswith just one line of code, this is called the funtion calling. Diclaring and calling the functions that need information is almost the same, but when when you call the function you need to include the parameter.

### getting multiple values out of a function

Functions can return more than one value using an array. 

### ANONYMOUS FUNCTIONS & FUNCTION EXPRESSIONS

Expressions produce a value. They can be used where values are expected. If a function is placed where a browser expects to see an expression, then it gets treated as an expression. If you put a function where the interpreter wouldexpect to see an expression, then it is treated as anexpression, and it is known as a function expression.

### IMMEDIATELY INVOKED FUNCTION EXPRESSIONS
This way of writing a function is used in several different situations. Often functions are used to ensure that the variable names do not conflict with each other

### variable scope

* **local variable** : When a variable is created inside a function using the var keyword, it can only be used in that function. It is called a local variable or function-level variable. It is said to have local scope or function-level scope. It cannot be accessed outside of the function in which it was declared.

* **global variables**: If you create a variable outside of a function, then it can be used anywhere within the script. It is called a global variable and has global scope.

### how memory and variables work

Global variables use more memory. The browser has to remember them for as long as the web page using them is loaded. Local variables are only remembered during the period of time that a function is being executed.

## pair programming
pair programming is the practice of two developers sharing a single workstation to interactively tackle a coding task together.

#### **How does pair programming work?**

pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture.

#### **six advantages of pair programming**

1. it has greater efficiency 
2. more engaged collaboration
3. Learning from fellow students
4. improves social skills
5. provides job interview readiness
6. provides Work environment readiness


