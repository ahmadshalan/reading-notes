# Chapter 15 : Layout 

## Building Blocks:


CSS treats each HTML element as if it is in its own box. This box will either be a block-level
box or an inline box.

* Block-level elements :start on a new line Examples include: <h1> <p> <ul> <li>.

* Inline elements: flow in between surrounding text Examples include: <img> <b> <i>.

## Containing Elements
If one block-level element sits inside another block-level element then the outer box is
known as the containing or parent element.

## Controlling the Position of Elements
CSS has the following positioning schemes that allow you to control the layout of a page
: normal flow, relative positioning, and absolute positioning. 

You specify the positioning scheme using the position property in CSS. You can also float elements 
using the float property.

To indicate where a box should be positioned, you may also need to use box offset properties to tell 
the browser how far from the top or bottom and left or right it should be placed.

* Fixed Positioning This is a form of absolute positioning that positions
the element in relation to the browser window, as opposed to the containing element. Elements with fixed 
positioning do not affect the position of surrounding elements and they do not move when the user
scrolls up or down the page.

* Floating Elements Floating an element allows you to take that element out of normal flow and position
it to the far left or right of a containing box. The floated element becomes a block-level
element around which other content can flow.


## Normal Flow
* position:static

in normal flow, each block-level element sits on top of the next one. Since this is the default
way in which browsers treat HTML elements, you do not need a CSS property to indicate
that elements should appear in normal flow, but the syntax would be:
position: static;



## Relative Positioning 
* position:relative

Relative positioning moves an element in relation to where it
would have been in normal flow. For example, you can move it 10
pixels lower than it would have been in normal flow or 20% to
the right.

## Abosulte Positioning 
* position:absolute

When the position property is given a value of absolute, the box is taken out of normal
flow and no longer affects the position of other elements on the page.


## Fixed Positioning 
* position:fixed

Fixed positioning is a type of absolute positioning that
requires the position property to have a value of fixed.

## Overlapping elements 
* z-index

When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the
elements that appear later in the HTML code sit on top of those that are earlier in the page.

## Floating Elements
* float

The float property allows you to take an element in normal
flow and place it as far to the left or right of the containing
element as possible.

## Clearing floats
* clear

The clear property allows you to say that no element 
should touch the left or righthand sides of a box. 




