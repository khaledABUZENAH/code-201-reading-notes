# read09

## Forms

Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information. HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site. The best known form on the web is probably the search box that sits right in the middle of Google's homepage.

### Form controls 


There are several types of form controls that you can use to collect information from visitors to your site:

* adding text

- text input

- password input
- Text area


* making choices  

 - radio buttons
 - checkpoints
 - Down-drop boxes

 * Submetting forms

  - submit buttons
  - image buttons


  * uploading files

  - File upload

### How forms work ?

1. A user fills in a form and then presses a button to submit the information to the server.

2. The name of each form control is sent to the server along with the value the user enters or selects.

3. The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database.

4. The server creates a new page to send back to the browser based on the information received.

A form may have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element.

### Form srtucture

* Form controls live inside a **form** element. This element should always carry the action attribute and will usually have a method and id attribute too.

* Every **form** element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.

* Forms can be sent using one of two methods: get or post. With the **get** method, the values from the form are added to the end of the URL specified in the action attribute. With the **post** method the values are sent in what are known as HTTP headers. As a rule of thumb you should use the post method if your form:

