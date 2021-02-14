# Domain Modeling

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

## Model epic fails videos
Imagine you've been tasked to build a program that models the popularity of epic fail videos. After months of painstaking research, you've determined that the two essential metrics for gauging popularity are an epic rating and whether or not the video has animals.

Since you'll be modeling the popularity of many types of videos—parkour epic fails, corgi epic fails, etc.—you'll want to build self-contained objects with the same attributes and behaviors. That way, when you need to change the algorithm for determining popularity, the changes will be small and targeted.



As you read this article, type out and run all code samples you come across. Do not copy and paste. Writing out and testing your code will help you remember how to implement domain models in JavaScript later.

## Define a constructor and initialize properties
To define the same properties between many objects, you'll want to use a constructor function. Below is a table that summarizes a JavaScript representation of an EpicFailVideo object.


## Calculate daily Likes
Popularity of a video is measured in Likes. And the formula for calculating Likes is the number of viewers times the percentage of viewers who'll Like a video. In other words, viewers times percentage.

To calculate the number of viewers per day, generate a random number between 10 and 30 and then multiply it by the epic rating of that video.

The dailyLikes() method on EpicFailVideo's prototype is assigned a function with no parameters. This method starts by defining two variables called viewers and percentage.

The viewers variable is assigned the value of this.generateRandom(10, 30) multiplied by this.epicRating. Using the this variable, methods can access any property or method on the same object that called the dailyLikes() method.

The percentage variable is assigned a decimal percentage based on the object's this.hasAnimals property. Again, using the this variable, methods can access any property of the same object that called the dailyLikes() method.

Finally, viewers and percentage are multiplied, rounded to the nearest integer with Math.round, and the value is returned. When the dailyLikes() method is called on both parkourFail and corgiFail, the result is logged to the console.


## Summary
Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

Here's some tips to follow when building your own domain models.

When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
Model its attributes with a constructor function that defines and initializes properties.
Model its behaviors with small methods that focus on doing one job well.
Create instances using the new keyword followed by a call to a constructor function.
Store the newly created object in a variable so you can access its properties and methods from outside.
Use the this variable within methods so you can access the object's properties and methods from inside.




# Chapter 6 Tables:

## What's a Table?

A table represents information in a grid format. Examples of tables include financial reports, TV
schedules, and sports results.


## Basic Table Structure

* <'table'>
* <'tr'>
* <'td'>
* <'th'>


## Spanning columns

The colspan attribute can be used on a <'th'> or <'td'> element
and indicates how many columns that cell should run across.

## Spanning rows

The rowspan attribute can be used on a <'th'> or <'td'> element
to indicate how many rows a cell should span down the table.

## Long Tables

* <'thead>
The headings of the table should sit inside the <'thead> element.
* <'tbody>
The body should sit inside the <'tbody> element.
* <'tfoot>
The footer belongs inside the <'tfoot> element.

