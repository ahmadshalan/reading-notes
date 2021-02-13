# Chapter 3 object literals : What is an object

Objects group together a set of variables and functions to create a model of a something you
would recognize from the real world. In an object, variables and functions take on new names. 


*IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES*

*IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS*


# Creating an object 

### literal notation.

![literal-ex.](201/img/literal-ex.png)

### Accessing an object and dot notation

You access the properities of an object using dot notation or square brackets.

# Chapter 5 Document object model

The Document Object Model (DOM) specifies how browsers should create a model of an HTML
page and how JavaScript can access and update the contents of a web page while it is in the browser window. 


### THE DOM TREE IS MODEL OF A WEB PAGE
As a browser loads a web page, it creates a model of that page. The model is called *a DOM tree*, and it is
stored in the browsers' memory. It consists of four main types of nodes. 

Each node is an object with methods and properties. Scripts access and update this DOM tree.
Any changes made to the DOM tree are reflected in the browser. 


* ATTRIBUTE NODES

The opening tags of HTML elements can carry
attributes and these are represented by attribute
nodes in the DOM tree.

* TEXT NODES
Once you have accessed an element node, you
can then reach the text within that element. This is
stored in its own text node.

### WORKING WITH THE DOM TREE

Accessing and updating the DOM tree involves two steps:
1.  Locate the node that represents the element you want to work with.
2.  Use its text content, child elements, and attributes. 

### Caching DOM Queries

Methods that find element in the DOM Tree are called DOM Queries.

### ACCESSING ELEMENTS
DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes. 

### Method that select indivduaal elements 

getElementByID()and querySelector()can both search an entire element and return individual elements 
both use similar syntax.


### NODELISTS: DOM QUERIES THAT RETURN MORE THAN ONE ELEMENT
When a DOM method can return more than one element, it returns a
Nodelist (even if it only finds one matching element). 


### selecting an element from a Nodelist

there are two ways to select an element from a Nodelist:

* the item method
* array syntax

### SELECTI NG ELEMENTS USING CLASS ATTRIBUTES
The get El ementsByCl ass Name()method allows you to select elements whose c 1 ass attribute
contains a specific value.

The method has one parameter: the class name which is given in quotes within the parentheses
after the method name. Because several elements can have the same value for their
cl ass attribute, this method always returns a Nodelist.

### SELECTING ELEMENTS BY TAG NAME 
The get El ementsByTagName () method allows you to select elements using their tag name.
JAVASCRIPT The element name is specified as a parameter, so it is placed inside the parentheses and is
contained by quote marks. Note that you do not include the angled brackets that surround
the tag name in the HTML (just the letters inside the brackets). 

### SELECTING ELEMENTS USING CSS SELECTORS
querySe 1 ector() returns the first element node that matches the CSS-style selector.
querySe 1ectorA11 () returns a Nodelist of all of the matches.

### LOOPING THROUGH A NODELIST
If you want to apply the same code to numerous elements, looping through a Nodelist is a
powerful technique. JAVASCRIPT
It involves finding out how many items are in the Nodelist, and then setting a counter to loop
through them, one-by-one. Each time the loop runs, the script checks that the counter
is less than the total number of items in the Nodelist. 

### TRAVERSING THE DOM
When you have an element node, you can select another element in relation to it using these five
properties. This is known as traversing the DOM.


### ACCESS & UPDATE A TEXT NODE WITH NODEVALUE
When you select a text node, you can retrieve or amend the content of it
using the node Va 1 ue property. 


### ACCESSING & CHANGI NG A TEXT NODE
To work with text in an element, first the element node is accessed and then its text node.
JAVASCRIPT The text node has a property called node Value which returns the text in that text node. 


### The textContent property allows you to collect or update just the text that is in the containing element (and its children). 






