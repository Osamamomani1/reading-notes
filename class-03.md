## HTML (Lists)

* There are three types of HTML lists: ordered, 
unordered, and definition.

1- Ordered lists : are lists where each item in the list is 
numbered. For example, the list might be a set of steps for 
a recipe that must be performed in order, or a legal contract 
where each point needs to be identified by a section 
number

2- Unordered lists are lists that begin with a bullet point 
(rather than characters that indicate order)

3- Definition lists are made up of a set of terms along with the 
definitions for each of those terms

### < dl > 

The definition list is created with 
the < dl > element and usually 
consists of a series of terms and 
their definitions.

Inside the < dl> element you will 
usually see pairs of < dt > and 
< dd > elements.

### < dt >
This is used to contain the term 
being defined (the definition 
term).

### < dd >
This is used to contain the 
definition

**Nested Lest**

You can put a second list inside
an < li > element to create a sublist or nested list.

## HTML & CSS (Boxes)

* CSS treats each HTML element as if it has its own box.

* You can use CSS to control the dimensions of a box.

* You can also control the borders, margin and padding 
for each box with CSS

* It is possible to hide elements using the display and 
visibility properties.

* Block-level boxes can be made into inline boxes, and 
inline boxes made into block-level boxes.

* Legibility can be improved by controlling the width of 
boxes containing text and the leading.

* CSS3 has introduced the ability to create image 
borders and rounded borders

## JavaScript (Arrays)

* An array is a special type of variable. It doesn't 
just store one value; it stores a list of values. 


* CREATING AN ARRAY  :

```
var colors 
new Array('white ' , 
'black', 
'custom'); 
var el = document.getElementByid( ' colors' ); 
el.innerHTML = colors.item(O); 
```

**Values in an array are accessed as if they are in 
a numbered list. It is important to know that the 
numbering of this list starts at zero (not one).**

* ACCESSING & CHANGING VALUES IN AN ARRAY 

```
// Create the array 

var colors = ['white', 
'black' , 
'custom']; 

// Update the third item in the array 

colors[2] = 'beige ' ; 

// Get the element with an id of col ors 

var el = document .getElementByid(' colors') ; 

// Replace with third item from the array 

el .textContent = colors[2]; 
```

## JavaScript (loops'switch statment')

* switch statements allow you to compare a value 
against possible outcomes (and also provides a default 
option if none match).

* Data types can be coerced from one type to another. 

* All values evaluate to either truthy or falsy. 

* There are three types of loop: for, while, and 
do ... while. Each repeats a set of statements.


| IF ..ELSE |  SWITCH | 
|----------|:-------------:|
|There is no need to provide an el se option.| You have a default option that is run if none of the cases match. 
|With a series of if statements, they are all checked even if a match has been found (so it performs more slowly than switch). |If a match is found, that code is run; then the break statement stops the rest of the switch statement running (providing better performance than multiple i f statements).|
| | |