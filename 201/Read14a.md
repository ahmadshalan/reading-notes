# CSS Transforms

The transform property comes in two different settings:
1. two-dimensional.
2. three-dimensional.

### Transform Syntax
The actual syntax for the transform property is the transform property followed by the value. <br />
*EX :* -webkit-transform: scale(1.5); <br />



## 2D Transforms:

* Two-dimensional transforms work on the x and y axes. <br />

* Three-dimensional transforms work on both the x, y and z axis. <br />


### 2D Rotate:

The rotate provides the ability to rotate an element from 0 to 360 degrees with 2 ways:. <br />

1. Using a positive value will rotate clockwise.
2. using a negative value will rotate counterclockwise.

### 2D Scale :

it allows us to change the appeared size of an element. The default scale value is 1. <br /> 

1. value between .99 and .01 makes it smaller. 
2. value greater than or equal to 1.01 makes it larger.

*EX :*  { transform: scale(.75);} <br />

to scale the height or width of an element:
1. The scaleX value will scale the width.
2. the scaleY value will scale the height.


### 2D Translate
The translate value pushing and pulling an element in different directions without interrupting the normal flow of the document. <br /> 

1. the *translateX* value will change the position of an element on the horizontal axis.
2. the *translateY* value will change the position of an element on the vertical axis.

### 2D Skew
is used to distort elements on the horizontal axis, vertical axis, or both. <br />

1.  the *skewX* value distorts an element on the horizontal axis.
2.  the *skewY* value distorts an element on the vertical axis.

### Transform Origin

The transform-origin property can accept one or two values.<br /> 

1. one value: it is used for both the horizontal and vertical axes. 
2. two values : the first is used for the horizontal axis and the second is used for the vertical axis.

### Perspective

The perspective can be set in two different ways:
1. One way includes using the perspective value within the transform property on individual elements.
2. the other includes using the perspective property on the parent element residing over child elements being transformed.


## 3D Transforms

### 3D Rotate

1.  the rotateX value allows you to rotate an element around the x axis, as horizontally.
2.  the rotateY value allows you to rotate an element around the y axis, as vertically. 
3.  the rotateZ value allows an element to be rotated around the z axis.

### 3D Scale

### 3D Translate
1. A negative value will push an element further away on the z axis, resulting in a smaller element.
2. A positive value will pull an element closer on the z axis, resulting in a larger element.


# 8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS

1. Fade in:
* first set the initial state.
*  Second set the change.
2. Change color.
3. Grow & Shrink.
4. Rotate elements
5. Square to circle
6. 3D shadow
7. Swing
8. Inset border
