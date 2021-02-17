# Chapter 10 : Error Handling and Debugging

### ORDER OF EXECUTION

To find the source of an error, it helps to know how scripts are processed. 


### EXECUTION CONTEXTS 


Every statement in a script lives in one of three execution contexts: 
* Global Context
* Function Context
* Eval Context

### VARIABLE SCOPE :

* Global Scope.

* Function level scope

## The Stack

JS intrepreter prcesses one line of conduct at a time. when statement need data from another function it stacks the new function on the top of the current task.

## EXECUTION CONTEXT & HOISTING

Each time a script enters a new execution context, there are two phases
of activity: 

1. PREPARE
* The new scope is created
* Variables, functions, and arguments are created
* The value of the this keyword is determined


2. EXECUTE
* Now it can assign values to variables
* Reference functions and run their code
* Execute statements

### UNDERSTANDING SCOPE
In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's variables object. 


### UNDERSTANDING ERRORS
If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code. 


### ERROR OBJECTS 

![img](201/error objects.png)

### there are two things do with the errors:

1. DEBUG THE SCRIPT TO FIX ERRORS
If you come across an error while writing a script you will need to debug the code, track down the source of the error,
and fix it. 

2.  HANDLE ERRORS GRACEFULLY
handle errors gracefully using try, catch,throw, and finally statements.


### The console helps narrow down the area in which the error is located, so you can try to find the exact error. 