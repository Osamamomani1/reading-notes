## HTML (Links)

* Links are created using the < a > element.

* The < a > element uses the href attribute to indicate 
the page you are linking to :
```
 < a href="(the page link)> (pagename)< /a >
```
* If you are linking to a page within your own site, it is 
best to use relative links rather than qualified URLs :
```
< a href="(relative links)" >(pagename)< /a >
```
* You can create links to open email programs with an 
email address in the "to" field :
```
< a href="mailto:(Emailadress)" >(Emailname)< /a >
```
* You can use the id attribute to target elements within 
a page that can be linked to
```
< a href="#(idname)">(name you want)< /a >
```
* you can Opening Links in a New Window using target :

```
< a href="page link" target="_blank">(pagename)< /a >
```

## HTML & CSS (Layout)

Key Concepts in Positioning Elements

* CSS treats each HTML element as if it is in its 
own box. This box will either be a block-level
box or an inline box
  * Block-level elements start on a new line
Examples include:< h1> < p> < ul> < li>
  * Inline elements
flow in between surrounding text Examples include:< img> < b> < i>

* Containing Elements :If one block-level element sits inside another 
block-level element then the outer box is 
known as the containing or parent element.

* Controlling the Position of Elements
```
CSS has the following positioning schemes that allow you to control 
the layout of a page: normal flow, relative positioning, and absolute 
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property

1. Normal flow :

Every block-level element 
appears on a new line, causing 
each item to appear lower down 
the page than the previous one. 
Even if you specify the width 
of the boxes and there is space 
for two elements to sit side-byside, they will not appear next 
to each other. This is the default 
behavior (unless you tell the 
browser to do something else).

2. Relative Positioning :

This moves an element from the 
position it would be in normal 
flow, shifting it to the top, right, 
bottom, or left of where it 
would have been placed. This 
does not affect the position of 
surrounding elements; they stay 
in the position they would be in 
in normal flow

3. Absolute positioning :

This positions the element 
in relation to its containing 
element. It is taken out of 
normal flow, meaning that it 
does not affect the position 
of any surrounding elements 
(as they simply ignore the 
space it would have taken up). 
Absolutely positioned elements 
move as users scroll up and 
down the page.
``` 

* To indicate where a box should be positioned, you may also need to use 
box offset properties to tell the browser how far from the top or bottom 
and left or right it should be placed.

  * Fixed Positioning  :

  This is a form of absolute 
positioning that positions 
the element in relation to the 
browser window, as opposed 
to the containing element. 
Elements with fixed positioning 
do not affect the position of 
surrounding elements and they 
do not move when the user 
scrolls up or down the page

  * Floating Elements

  Floating an element allows 
you to take that element out 
of normal flow and position 
it to the far left or right of a 
containing box. The floated 
element becomes a block-level 
element around which other 
content can flow

**When you move 
any element from 
normal flow, boxes 
can overlap. The 
z-index property 
allows you to control 
which box appears 
on top**

## JavaScript(Functions ,Methods & objects)

Browsers require very detailed instructions about what 
we want them to do. Therefore, complex scripts can run 
to hundreds (even thousands) of lines. Programmers use 
functions, methods, and objects to organize their code. 

### What is a function ? 

Functions let you group a series of statements together to perform a 
specific task. If different parts of a script repeat the same task, you can 
reuse the function (rather than repeating the same set of statements). 

### ANONYMOUS FUNCTIONS & FUNCTION EXPRESSIONS 

* FUNCTION DECLARATION :

A function declaration creates a function that you 
can call later in your code.

In order to call the function later in your code, you 
must give it a name, so these are known as named 
functions. Below, a function called area() is 
declared, which can then be called using its name. 
```
function area (width, height) {
return width * height; 
}; 
var size= area (3, 4) ;
```
* FUNCTION EXPRESSION  :
If you put a function where the interpreter would 
expect to see an expression, then it is treated as an 
expression, and it is known as a function expression. 

In function expressions, the name is usually omitted. 
A function with no name is called an anonymous 
function. Below, the function is stored in a variable 
called area. It can be called like any function created 
with a function declaration. 
```
var area = f unction(width, height) { 
return width * height; 
} ; 
var size = area (3, 4) ;
```

**you nees to call the function if you want to use it : functionname();**

