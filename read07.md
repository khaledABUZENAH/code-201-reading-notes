# read07

## Domain modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem.

### Generat Random Numbers

in this case we use Math.random() function

the methods can be added to a prototype instead of the object itself

* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
* Model its attributes with a constructor function that defines and initializes properties.
* Model its behaviors with small methods that focus on doing one job well.
* Create instances using the new keyword followed by a call to a constructor function.
* Store the newly created object in a variable so you can access its properties and methods from outside.
* Use the this variable within methods so you can access the object's properties and methods from inside.


## Tables

There are several types of information that need to be displayed in a grid or table. For example: sports results, stock reports, train timetables. A table represents information in a grid format.

### Basic Table Structure

* The **table** element is used to create a table. The contents of the table are written out row by row.
* The **table** element is used to create a table. The contents of the table are written out row by row.
* Each cell of a table is represented using a **td** element. (The td stands for table data.) At the end of each cell you use a closing **td** tag.

### Table headings 

The **th** element is used just like the **td** element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.) Even if a cell has no content, you should still use a **td** or **th** element to representb the presence of an empty cell otherwise the table will not render correctly.

### Spanning columns

Sometimes you may need the entries in a table to stretch across more than one column. The colspan attribute can be used on a **th** or **td** element and indicates how many columns that cell should run across.

Colspan="n of columns that u want it to strech in"

### Spanning Rows

You may also need entries in a table to stretch down across more than one row. The rowspan attribute can be used on a **th** or **td** element to indicate how many rows a cell should span down the table.

Rowspan="n of rows that u want it to strech in"

### Long tables

There are three elements that help distinguish between the main content of the table and the first and last rows

* The headings of the table should sit inside the **thead** element.
* The body should sit inside the **tbody** element.
*  The footer belongs inside the **tfoot** element.
