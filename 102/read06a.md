# Chapter 10 : Introduction to CSS

In this section, we will look at how to make web pages more attractive,
controlling the design of them using CSS.

## Understanding CSS:
## Thinking Inside the Box

* The key to understanding how CSS works is to imagine that there is an invisible box around
every HTML element.

* CSS allows you to create rules that control the way that each individual box is presented.

## Example Styles:

|  Boxes|   text  |specific| 
| ----- | ------  | ------ |
|   Width and height |  Size  |   you can style certainelements such as lists, tables,and forms.   | 

## a CSS rule contains two parts:
1. Sector :  indicate which element the rule applies to.

2. Declaration: indicate how the elements referred to in the selector should be styled.

## CSS declarations sit inside curly brackets and each is made up of two parts: 

1. property: indicate the aspects of the element you want to change. 

2. value: specify the settings you want to use for the chosen properties.

separated by a colon You can specify several properties in one declaration, each separated by a semi-colon.

# Using External CSS"

* The link: element can be used in an HTML document to tell the browser where to find the CSS file used to style the page.

* href: This specifies the path to the CSS file.

* type: This attribute specifies the type of document being linked to.

* rel: This specifies the relationship between the HTML page and the file it is linked to. 


# Chapter 11 : colors

## Foreground Color


The color property allows you to specify the color of text inside an element. You can specify any
color in CSS in one of three ways:

* rgb values :

These express colors in terms of how much red, green and blue are used to make it up.

* hex codes :

These are six-digit codes that represent the amount of red, green and blue in a color,
preceded by a pound or hash # sign.

* color names :
There are 147 predefined color names that are recognized by browsers.

## Background color:

You can specify your choice of background color in the same three ways you can specify
foreground colors: RGB values, hex codes, and color names.

### Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker.

Color picking tools are available in image editing programs like Photoshop and GIMP.

## Contrast :

When picking foreground and background colors, it is important to ensure that there is
enough contrast for the text to be legible.

# CSS3: Opacity
opacity, rgba 

CSS3 introduces the opacity property which allows you to specify the opacity of an element
and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15% opacity).

# CSS3: HSL colors

CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation,
and lightness values.


# CSS3 : HSL and HSLA:
hsl and hsla.







