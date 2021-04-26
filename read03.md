# HTML Lists, Control Flow with JS, and the CSS Box Model

## lists

HTML provides us with three different types of lists:

1. Ordered lists are lists where each item in the list is numbered. The ordered list is created with the (<ol>) element. Each item in the list is placed
between an opening (<li>) tagand a closing (</li>) tag. You can put a second list inside an <li> element to create a sublist or nested list.

2. Unordered lists are lists that begin with a bullet point. The unordered list is created with the (<ul> ) element. Each item in the list is placedbetween an opening (<li>) tag
and a closing (</li>) tag.

3. Definition lists are made up of a set of terms along with the definitions for each of those terms. The definition list is created with the (<dl>)element and usually consists of a series of terms and their definitions. Inside the (<dl>)element you will usually see pairs of (<dt>) and (<dd>) elements. the (<dt>) is used to contain the term being defined, and (<dd>) is used to contain the definition.

## boxes

By default a box is sized just big enough to hold its contents. To set your own dimensions for a box you can use the height and width properties. Some page designs expand and shrink to fit the size of the user's screen. In such designs, the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide.

### overflowing content

 The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:

 1. **hidden** This property simply hides any extra content that does not fit in the box.
 2. **scroll** This property adds a scrollbar to the box so that users can scroll to see the missing content.

### border, margin, and padding

* border: The border separates the edge of one box from another.
* margin: Margins sit outside the edge of the border
* padding: Padding is the space between the border of a box and any content contained within it.\

### hiding boxes and visibility

 The visibility property allows you to hide boxes from users but It leaves a space where the element would have been. This property can take two values;
hidden (This hides the element.) anvisible (This shows the element.). If the visibility of an element is set to hidden, a blank space will appear in its place.

### border images

The border-image property applies an image to the border of any box. It takes a background image and slices it into nine pieces.

### box shadows

The box-shadow property allows you to add a drop shadow around a box. It must use at least the first of these two values as well as a color:

* horizontal offset:negative values
* vertical offset: negative values
*  blur distance: positive values
* spread of shadow: positive values

The inset keyword can also be used before these values to mcreate an inner-shadow.

### rounded corners (border-radius)
CSS3 introduces the ability to create rounded corners on any box, using a property called border-radius. The value indicates the size of the radius in pixels. To create more complex shapes, you can specify different distances for the horizontal and the vertical parts of the rounded corners.

## Review from Reading 02 - Chapter 2:

### arrays

An array is a special type of variable. It doesn't just store one value; it stores a list of values. You should consider using an array whenever you are working with a list or a set of values that are related to each other. You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of mthe array). Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).

## Decisions and Loops

### SWITCH STATEMENTS

![switch](https://www.codegrepper.com/codeimages/switch-statement-javascriptr.png)

A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

 ### type coerecion and weak typing

 * type coerecion: JavaScript converts data types behind the scenes to complete an operation.
 * JavaScript is said to use weak typing because the data type for a value can change. Some other languages require that you specify what data type each variable will be.

 ### truthy and fulsy values

 Due to type coercion, every value in JavaScript can be treated as if it were true or false; and this has some interesting side effects. Falsy values are treated as if they are fa1se. Falsy values can also be treated as the number 0. And truthy values are treated as if they are true. Almost everything that is not in the falsy table can be treated as if it were true. Truthy va lues can also be treated as the number 1. In addition, the presence of an object or an array is usually considered truthy, too.

 ### SHORT CIRCUIT VALUES

 Logical operators are processed left to right. They short-circui (stop) as soon as they have a result - but they return the value that stopped the processing (not necessarily true or fa 1 se).





