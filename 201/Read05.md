# Chapter 5 Images

Images can be used to set the tone for a site in less time than it takes to read a description.

If you are building a site from scratch, it is good practice to create a folder for all of the images
the site uses.

To add an image into the page you need to use an <'img'> element. This is an empty
element (which means there is no closing tag). It must carry the
following two attributes:


* src
This tells the browser where it can find the image file.

* alt
This provides a text description of the image which describes the image if you cannot see it.

* title
to provide additional information about the image.


## Height & Width of Images

element use two other attributes that specify its size:

* height
This specifies the height of the image in pixels.
* width
This specifies the width of the image in pixels.

## Where to Place Images in Your Code

1. before a paragraph
 The paragraph starts on a new line after the image.
2. inside the start of aparagraph
The first row of text aligns with the bottom of the image.
3. in the middle of a paragraph
The image is placed between the words of the paragraph that it appears in.


#### The align attribute 

was commonly used to indicate how the other parts of a page should flow around an image. 
It has been removed from HTML5 and new websites should use CSS to control the alignment of images.

The align attribute can take these horizontal values:

* left
This aligns the image to the left (allowing text to flow around its right-hand side).
* right
This aligns the image to the right (allowing text to flow around its left-hand side).

#### There are three values that the align attribute can take that control how the image should

align vertically with the text that surrounds it:

1. top
This aligns the first line of the surrounding text with the top of the image.
2. middle
This aligns the first line of the surrounding text with the middle of the image.
3. bottom
This aligns the first line of the surrounding text with the bottom of the image.

### Three Rules for Creating Images

There are three rules to remember when you are creating images for your website:

1. Save images in the right format
2. Save images at the right size
3. Use the correct resolution


Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

### HTML5: Figure and Figure Caption

<'figure'>
Images often come with captions. HTML5 has introduced a new <'figure'> element to contain images 
and their caption so that the two are associated. 

<'figcaption'>
The <'figcaption'> element has been added to HTML5 in order to allow web page authors to add
a caption to an image.


## Chapter 11 colors

The color property allows you to specify the color of text inside an element. You can specify any
color in CSS in one of three ways:

1. rgb values
These express colors in terms of how much red, green and blue are used to make it up. For
example: rgb(100,100,90)
2. hex codes
These are six-digit codes that represent the amount of red, green and blue in a color, preceded by 
a pound or hash # sign. For example: #ee3e80
3. color names
There are 147 predefined color names that are recognized by browsers. For example: DarkCyan

### background-color

CSS treats each HTML element as if it appears in a box, and the background-color property
sets the color of the background for that box.

### CSS3: Opacity opacity, rgba

The CSS3 rgba property allows you to specify a color, just like you would with an RGB value,
but adds a fourth value to indicate opacity.

### CSS3: HSL & HSLA

The hsl color property has been introduced in CSS3 as an alternative way to specify colors.
The value of the property starts with the letters hsl, followed by individual values inside
parentheses for:

1. hue
This is expressed as an angle (between 0 and 360 degrees).
2. saturation
This is expressed as a percentage.
3. lightness
This is expressed as a percentage with 0% being white, 50% being normal, and 100% being black.

## Chapter 12 Text

![img3](201/typeface.png)

![img4](201/The XYZ.png)

### Units of Type Size

Setting font size in pixels is the best way to ensure that the type appears at the size you intended
(because percentages and ems are more likely to vary if a user has changed the default size of
text in their browser). Pixels are relative to the resolution of the screen, so the same type size will look larger
when a screen has a resolution of 800x600 than it would when it is 1280x800.
You can also use pt for point sizes instead of px for pixels, but you should only do this when
creating style sheets for printerfriendly versions of pages. The default size of text in a
web browser is 16 pixels. Using percentages of this amount, you can create a scale where the default text size is 12 pixels, and headings are sized in relation to this.
It is possible for users to change the default size of text in their web browsers. If they have done this, the fonts will be displayed at the same scale that the designer intended, but at a larger size.
Ems allow you to change the size of text relative to the size of the text in the parent element. Since
the default size of text in web
browsers is 16 pixels, you can use similar rules to those shown for percentages.
Because users can change the default size of text in their browser, the fonts could all appear larger (or smaller) than
the designer intended. The extra p rule above is to help Internet Explorer 6 and 7 display the fonts at the right size.
Without this extra rule, IE6 and IE7 exaggerate the relative sizes
of other text.
Pixels Percentages Ems

### Bold font-weight

### Italic font Style

