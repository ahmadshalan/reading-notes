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






