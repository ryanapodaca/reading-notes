# Functional Programming 

*Definition:*

A style of programming that emphasizes computational evalutation of mathematical functions and avoids mutable data.

*Conditions of Function Purity:*

- Deterministic, meaning that if all inputs are known, then outputs are correlatively deterimined by the function. 
- No side effects. 

For example, any function that utilzes a randomness generator cannot be pure. It is mutable, and therefore unpure.  

Pure functions are useful for their predictability, which aids in function modularity and stability.

Stability refers to the attribute of variable constancy after creation.

pure functions and immutable data entails referential transparency.  

## Node JS

*Module:*

A module is another JS file

Require method is used to connect modules and their functionality to a main JS module.   

In order to bring a module's function into another JS module, you need assign a variable to the require method, and explicitly export the function from it's module. Exporting a function using the module.exports method makes it 'available.'
