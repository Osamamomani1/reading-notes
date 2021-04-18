# CSS (Cascading Style Sheets)

## inroducing :

CSS allows you to create rules that specify how the content of 
an element should appear. For example, you can specify that 
the background of the page is cream, all paragraphs should 
appear in gray using the Arial typeface, or that all level one 
headings should be in a blue, italic, Times typeface.

** Example Styles** :

- Boxes : Width and height
Borders (color, width, and style)
Background color and images
Position in the browser window.


- Text :
   - Typeface
  - Size
  - Color
  - Italics, bold, uppercase, 
  - lowercase, small-caps


  - Specific : There are also specific ways 
in which you can style certain 
elements such as lists, tables, 
and forms.



 ** CSS can be added to HTML documents in 3 ways:**

1. Inline - by using the style attribute inside HTML elements.

2. Internal - by using a <style> element in the <head> section.

3. External - by using a <link> element to link to an external CSS file.

## Color 

The color property allows you 
to specify the color of text inside 
an element. You can specify any 
color in CSS in one of three ways:

1. RGB values :

These express colors in terms 
of how much red, green and 
blue are used to make it up. For 
example: rgb(100,100,90)

2. hex codes :

These are six-digit codes that 
represent the amount of red, 
green and blue in a color, 
preceded by a pound or hash # 
sign. For example: #ee3e80

3. color names : 

There are 147 predefined color 
names that are recognized 
by browsers. For example: 
DarkCyan

4. HSL 

- Hue : 
Hue is near to the colloquial idea 
of color. Technically speaking 
however, a color can also have 
saturation and brightness as 
well as hue.


- Saturation :

Saturation refers to the amount 
of gray in a color. At maximum 
saturation, there would be no 
gray in the color. At minimum 
saturation, the color would be 
mostly gray

- Brightness :

Brightness (or "value") refers 
to how much black is in a color. 
At maximum brightness, there 
would be no black in the color. 
At minimum brightness, the 
color would be very dark.


** Contrast ** :
When picking foreground and background 
colors, it is important to ensure that there is 
enough contrast for the text to be legible.

** CSS3 Opacity **: (rgba)



property which allows you to 
specify the opacity of an element 
and any of its child elements. 
The value is a number between 
0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15% 
opacity).

The CSS3 rgba property allows 
you to specify a color, just like 
you would with an RGB value, 
but adds a fourth value to 
indicate opacity. This value is 
known as an alpha value and is 
a number between 0.0 and 1.0
(so a value of 0.5 is 50% opacity 
and 0.15 is 15% opacity). The 
rgba value will only affect the 
element on which it is applied 
(not child elements).

** CSS3: HSL & HSLA **

alternative way to specify colors. 
The value of the property starts 
with the letters hsl, followed 
by individual values inside 
parentheses for: 

- hue
This is expressed as an angle 
(between 0 and 360 degrees)


- saturation
This is expressed as a 
percentage.


 - lightness
This is expressed as a 
percentage with 0% being white, 
50% being normal, and 100% 
being black.


- alpha
This is expressed as a 
number between 0 and 1.0. 
For example, 0.5 represents 
50% transparency, and 0.75
represents 75% transparency


