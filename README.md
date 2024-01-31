# 5-2-0 Assignment: Inheritance

## Short Response

Do them!

## Question 1 - Quadrilateral
Create a `Quadrilateral` class. Check the tests to see what arguments it's expecting and whether or not it has any methods on it.

## Question 2 - Rectangle
Now make a `Rectangle` class that inherits from the `Quadrilateral` class. Pay very careful attention to how the arguments for `Rectangle` differ from `Quadrilateral`. How should this class deal with its parent? Does it need any methods of its own or is it borrowing from the parent?

## Question 3 - Square
Finally, make a `Square` class that inherits from...someone. Check the tests to see who the direct parent is, and what arguments `Square` takes on each instance.

Now, there are some methods that square *should* add:
- getPerimeter
- getArea
- getDiagonal

Hopefully you know how to get those things from the sides, but google or GPT is your friend here. Whenever you have a question, always think about where you're staring from (what do you know about the square) and where you're going (what are you trying to calculate).

## Design Challenge

Design a `Person` class. 

**Instance Properties / Methods**: An instance of `Person` should have three *or more* data properties which can be any type (string, number, boolean, array, object, etc.). Your `Person` class should have at least three **non-trivial** instance methods. For this assignment, a trivial method is one that either gets the data property or sets the data property to the parameter value. In other words, methods like `setName()` or `changeName()` or `get name()` will not be accepted.

**Class Properties / Methods**: As for the *class* of Person, it should have a private variable to track each new instance, a `list` method that returns that variable, and a `find` method that allows you to look up a person by some attribute (you're choice).

This design challenge is purposefully ambiguous and open-ended to encourage creativity. There are no tests, so you will be responsible for QAing the code yourself with the `playground.js` file. Basically just log stuff out.

...Though if you wanted to add some *literal* tests yourself in a new `person.spec.js`, who's gonna stop you?
(don't add the scoring engine, just regular jest tests are fine).

