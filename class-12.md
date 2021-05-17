# Chart.js, Canvas

## Chart.js

Charts.js is a library for JavaScript which uses HTMLs canvas to render various different beautiful charts for the web.

* The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script:
```
<head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
```
* To draw a line chart add this to the body of our HTML page:
```
<script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
</script>
```

* Inside the same script tags we need to create our data , Add this immediately above the line that begins ‘var buyers=’:
```
var buyerData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
}
```

and you can drow bar,pie or whatever you want folowing this link 
[chartjs.org](https://www.chartjs.org/docs/latest/)

## canvas 



The HTML < canvas> element is used to draw graphics, on the fly, via scripting (usually JavaScript).

The < canvas> element is only a container for graphics. You must use a script to actually draw the graphics.

Canvas has several methods for drawing paths, boxes, circles, text, and adding images.


### HTML Canvas Can be Animated
```
Canvas objects can move. Everything is possible: from simple bouncing balls to complex animations.```
```
### HTML Canvas Can be Interactive
```
Canvas can respond to JavaScript events.
Canvas can respond to any user action (key clicks, mouse clicks, button clicks, finger movement).
```
### HTML Canvas Can Draw Text
```
Canvas can draw colorful text, with or without animation.
```
### HTML Canvas Can Draw Graphics
```
Canvas has great features for graphical data presentation with an imagery of graphs and charts.
```
### HTML Canvas Can be Used in Games
```
Canvas' methods for animations, offer a lot of possibilities for HTML gaming applications.
```