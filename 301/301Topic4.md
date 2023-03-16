# Forms in React

A controllled component is a component whose content is controlled by a centralizinhg React state. 

On a form, for example, there might be conditions connected to user input, such as whether someone is a veteran, which would then prompt more user inputs for time in service, benefits, etc.  Given this, it makes more sense to update the state part by part, rather than after the for is submitted.  We target the user input through controlled React components. 

# Ternary Operator

Ternary operators are used in lieu of conditionals in React.

*Form:*

condition ? value if true : value if false

*In lieu of:*

if ( condition ) {
  value if true;
} else {
  value if false;
}

*Example:*

if(x===y){
  console.log(true);
} else {
  console.log(false);
}

x === y ? console.log(true) : console.log(false);