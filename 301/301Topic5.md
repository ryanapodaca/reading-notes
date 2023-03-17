# React Concepts

*Single Resonsibility Principle*

Ideally, components should be responsible for only one aspect of your website. 

With React, staticness refers to lack of user interactivity. Static components are the structure through which interactivity will be developed with JSX interpolation. States are not used at all during static development.

Once staticness has been implemented, begin adding states, keeping in mind that states are computationally costly.

*3 Properties of Staticness(not a state):*

1. Does not change through time.
2. Passed from parents to children through props.
3. Can be computed based on existing state or other props within the component. 

It isn't always best to put states at higher level components. Consider compuational load at scale... 
Instead, consider the local of states in terms of proximity to their children and programmer interpretability. 

## Higher Order Functions

A higher-order function exploits our ability to abstract complexity into concepts that are more interpreatable for our purposes. For example, an explanation of steering a car might include an elucidation of the dynamics between the engine, turning-apparatus, and wheels, when what is really necessary for us is an understanding of turning the steering wheel in accordance with directions to our destination.  The explanation is necessary ultimately, for steering to work, but the explanation is useless for higher-order purposes, like getting to work on time.  The same holds for code.  Semantics can hide details about loops and selections for the benfit of higher order understanding and implementation. 

More specifically, A higher-order function is a function that processes other functions(as actions), rather than  values alone.

*Consider,*

function greaterThanTen(m) {
  return m => m > 10;
}

This is a function that contains a function. The user inputs variable m. On the second line, an arrow function takes m, and compares it to ten. It returns a boolean predicated on the truth value of the comarison's evaluation. 

Reduce() function takes in an array and returns a single value, by virtue of some inter-functional process.  Outputs can be the summation, or the longest string with an array, or the longest, or smallest, array within an array...
