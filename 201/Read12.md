# The <'Canvas'> element

It is almost as <'img'> without src and alt attribute only the width and height. when the width and height are not specified it will be 300px and 150 px. it is better to add and id for it to make it much easier for use. 
the canvas can be styled like any img without affecting the actual drawing on the canvas.

## Fallback content:

providing a fallback inside the canvas will help with the browsers that do not support canvas. browsers that do not support it will render the fallback and browsers that support canvas will ignore the fall back.

the canvas unlike the img require a closing tag.

## drawing shapes with canvas

#### the grid:
1 unit in grid corresponds to 1 pixel on the canvas.

### Drawing a rectangle:

there are 3 functions that draw a rectangular on canvas:

1. fill rect(x,y,width,height) draws a filled rectangle.
2. strokeRect(x,y,width,height) draws a rectangular outline.
3. clearRect (x,y,width,height) makes it fully transparent.


### drawing paths:

To make shapes using paths with these steps:

1.  create the path.
2. use drawing commands to draw into the path.
3. fill the path to render it.

Here are the functions used to perform these steps:

* beginPath()

* Path methods

* closePath()

* stroke()

* fill()

### moving the pen:

* moveTo(x, y) : Moves the pen to the coordinates specified by x and y.


### draw lines:

* lineTo(x, y) :Draws a line from the current drawing position to the position specified by x and y.

### Arcs

1. arc(x, y, radius, startAngle, endAngle, anticlockwise)
Draws an arc which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction.
2. arcTo(x1, y1, x2, y2, radius)
Draws an arc with the given control points and radius, connected to the previous point by a straight line.

### Bezier and quadratic curves

1. quadraticCurveTo(cp1x, cp1y, x, y):
Draws a quadratic Bézier curve from the current pen position to the end point specified by x and y, using the control point specified by cp1x and cp1y.
2. bezierCurveTo(cp1x, cp1y, cp2x, cp2y, x, y):
Draws a cubic Bézier curve from the current pen position to the end point specified by x and y, using the control points specified by (cp1x, cp1y) and (cp2x, cp2y).

### Rectangles 
rect(x, y, width, height): 
Draws a rectangle whose top-left corner is specified by (x, y) with the specified width and height.

# Applying styles and colors:

### Colors:

to apply colors to a shape, we can use: 

1. fillStyle = color.
2. strokeStyle =color.

# Drawing text:

The canvas rendering context provides two methods to render text:

1. fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
2. strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.