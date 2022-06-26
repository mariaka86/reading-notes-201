# Reading 6 notes
How would you describe an object to a non-technical friend you grew up with?

an object is a block of related functions and variables 
ie functions and variables that serve the same purpose

What are some advantages to creating object literals?

They're easier to transfer than arrays.

How do objects differ from arrays?

They're easier to transfer than arrays.
arrays are used to store a list of items while objects are used to store data.

Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation. 

if you wanted to list the objects index number to be a name instead of a number to make it easier for someone to read your code.

Evaluate the code below. What does the term this refer to and what is the advantage to using this?
 this refers to the object as a whole, it is referring to the dogs name and age. An advantage of using this is that it makes it clear to the reader what values are supposed to go in the curly braces.
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
## Introduction To The DOM

What is the DOM?

Briefly describe the relationship between the DOM and JavaScript.

The Document Object Model (DOM) is a representation of the objects that are in the structure and content of a document on the web.

What’s the difference between primitive values and object references in JavaScript?

you can't alter primitive values but you can alter object references.

## Things I want to know more about/notes to remember
- creating an object starts with defining and initializing a variable.
- arrays and numbers are an object's properties while functions are and object's  method