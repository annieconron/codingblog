---
title: Third Blog Post
publish_date: 2023-03-27
---

Last week I learnt about creating classes and making multiple objects from a class template. 

# Object Array

This week I learnt about duplicating objects using an array, so I can create a single variable  and create a for loop to duplicate it.

In the linked experiment I created a program that easily let me duplicate the object class. I was then able to create an interaction through Implementing a 'for … of' loop.

[Object Array for of Loop](https://editor.p5js.org/annieconron/full/Vhjwom2SG) 

# Mouse Interaction with an object 

**Function Dist**

Befor I could create some type of interaction I first needed to know how to use the dist function. 

function dist(x1, y1, x2, y2)

This function takes two separate points 

By making one point the centre of the circle and the other point where that mouse is clicked, then the program can pass these points into the dist function and get the length of the line - which is called 'd' in this experiment

The value for the radius of the circle is 'r' - so it is already known that this.r is the distance from the centre to the boarder of the circle.
The program tests the distance between the centre of the circle and the location of the mouse. If 'd' is greater than the radius 'r' then the mouse is not within the circle and if it is less than 'r' it is within the circle.

The linked example demonstrates how the dist function can be implemented.

[Mouse Interaction with an object](https://editor.p5js.org/annieconron/full/jH81Ry0n6)

**Removing Object from Array**

I learnt how to remove objects from an array using the splice function. 

What happens in this experiment is:
- In draw it is checking all the time if the mouse is over the object 
	If it is over the object then change its colour 
- In mouse pressed, if the mouse is pressed anywhere then check to see if it is within the object 
  And if so then delete it from the array which should remove it from the canvas  

[Removing Object from Array](https://editor.p5js.org/annieconron/full/117PEBTXm)