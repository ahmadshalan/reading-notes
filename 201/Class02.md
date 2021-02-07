# Chapter 2 : Text

When creating a web page, you add tags (known as markup) to the contents of the
page. These tags provide extra meaning and allow browsers to show users the
appropriate structure for the page.

* Structural markup: the elements that you can use to describe both headings and paragraphs.
* Semantic markup: which provides extra information; such as where emphasis is placed in a sentence, 
that something you have written is a quotation (and who said it), the meaning of acronyms, and so on


## Headings :
![img](201/headings.jpg)

## Paragraphs :

To create a paragraph, surround the words that make up the paragraph with an opening <p>
tag and closing </p> tag. By default, a browser will show each paragraph on a new line
with some space between it and any subsequent paragraphs.

## Bold and Italic :

1. By enclosing words in the tags <b> and </b> we can make characters appear bold.

2. By enclosing words in the tags <i> and </i> we can make characters appear italic.

## Superscript & Subscrip:

The <sup> element is used to contain characters that should be superscript such
as the suffixes of dates or mathematical concepts like raising a number to a power.

## Line Breaks & Horizontal Rules:

* <br />  if you wanted to add a line break inside the middle of a paragraph you can
use the line break tag <br />.

* <hr /> To create a break between themes — such as a change of topic in a book or a new scene
in a play — you can add a horizontal rule between sections using the <hr /> tag.

## Strong & Emphasis :

* strong : The use of the <strong> element indicates that its content has strong importance. 

* em : The <em> element indicates emphasis that subtly changes the meaning of a sentence.

# Quotation:

Ther are two elements used for marking up a quotation:
* blockquotes 
* q


# Chapter 10 : Introducing CSS :

* CSS allows you to create rules that specify how the content of an element should appear.

* CSS allows you to create rules that control the way that each individual box (and the contents
of that box) is presented.

* CSS works by associating rules with HTML elements. These rules govern how the content of specified
 elements should be displayed. A CSS rule contains two parts: a *selector* and a *declaration*.

 ![img](/mnt/c/Users/engas/102/reading-notes/CSS rule.jpg)

 * CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value,
  separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.
 ![img](/mnt/c/Users/engas/102/reading-notes/Ex.jpg)

 ## Using External CSS:

 * The <link> element can be used in an HTML document to tell the browser where to find the CSS
file used to style the page.

* rel: This specifies the relationship between the HTML page and the file it is linked to.

## Using Internal CSS:

We can also include CSS rules within an HTML page by placing them inside a <style> element,
which usually sits inside the <head> element of the page.

## CSS Selectors:

![img](/mnt/c/Users/engas/102/reading-notes/CSS Selectors.jpg)

# Chapter 2 : Basic JavaCript Instructions

* Statements :

A script is a series of instructions that a computer can follow one-by-one. Each individual instruction 
or step is known as a statement. Statements should end with a semicolon. 

* Comments :
You should write comments to explain what your code does. They help make your code easier to read and 
understand.

## What is a variable?

A script will have to temporarily store the bits of information it needs to do its job. It can store 
this data in variables.

Before we use a variable we need to call it:

*var* (which is the variable key word) *quantity* (variable name);

* Ex. using a variable to store a number : *quantity* (variable name) = 3(variable value);

* Ex. using a variable to store a string : *quantity* (variable name) = '3'(variable value);

* Ex. using a variable to store a boolean : *quantity* (variable name) = true(variable value);


## Mathmatical operators:

![img](/mnt/c/Users/engas/102/reading-notes/Mathematical operators.jpg)

## string operators:

there is only one string operator +. used to join two strings.

# chapter 4 : Decisions and loops:

* EVALUATIONS :You can analyze values in your scripts to determine whether or note they
match expected results.

* Decisions : Using the results of evaluations, you can decide which path your script should go 
down. 

* Loops : There are also many occasions where you will want to perform the same set of steps 
repeatedly. 


### Evaluate condition and conditional statements :

there are two components to a decision:
1. An expression is evaluated which returns a value.
2. A conditional statement says what to do.

### Comparison Operators
used to evaluate a situation and the result will be true or false

### Types of Comparison Operators

* Equal : ==
* not Equal : !=
* Strict Equal : ===
* Strict not Equal : !==
* greater than : >
* Less Than : <
* Greater or Equal : >=
* Less or Equal : <=



### Logical Operators:

return a single value of true or false and it allows to compare more than one comparison operation.

### Types of Logical Operators :

* Logical and : &&
* Logical or : ||
* Logical not : !

### the IF statement:

 evaluate a condition if it is true any statement in the subsequent block are excuted.


### If Else statement:

evaluate a condition if it is true any statement in the first subsequent block are excuted. if it is false the second block is excuted.



















