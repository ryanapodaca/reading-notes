# More React

The map function returns data that has been processed in some user-defined way way by an internal function.  

This is usefule in React.. you can use map() to transform arrays into lists of elements.  

React uses JSX to interpolate between scripts and JS functionality.  Curly braces are used to designate JS code. 

Every list should use an indice specifying key. This is important.. keys are used by React to indicate the specific items whose states have changed by user input.  

## Spread Operator

A type of syntax (...) that allows various types of array and object manipulation through expanding an iterable object.

4 Things it can do:

1. Combine two arrays 
2. Add items to arrays
3. Combine two objects
4. Spread indeces of an array across a function as arguments.

### Combine

let a = [1,2];
let b = [3,4];
let ab = [...a,...b];

### Add item to Array

let c = 5;
let abc = [...ab,...c];

### Combine Objects

let d = {name: 'Saul'}
let e = {name: 'Walter'}
let de = {...d,...e}

## Video

In order to call functions from other components, you use the increment method from within the class object, and then make a props call within your increment method in the higher order object.

The increment method functions to update the state of a component when a change of state has been detected.

You can pass a method from from a parent into a child with props method.

A parent's method can be invoked from a child by calling it as a function.  

 








