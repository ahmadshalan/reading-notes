# Chapter 15 : Layout 

## Building Blocks:




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




