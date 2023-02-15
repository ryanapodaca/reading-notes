# OOP and Tables

## Domain Modeling

**Any domain that collects info in properties and uses behaviors as methods.**

Object oriented programming gives us the capacity to generate information from absracted wireframes(objects) which are intentiionally designed to hold information and behave(methods) in determinate ways when specific information is processed.  Thus we can generate whole web pages and other forms of content from object templates.

## HTML Tables

Three Reasons Tables are not Good for Website Content:

1. It reduces accessibility to the sight impaired
2. Tables add extra information where it is not needed, specifically data tags where no info is needed.
3. Tables are not interactive initially.

Three semantic table elements:


1. 'th' is a table header element.
2. 'tr' is a table row element.
3. 'td' is a table cell, usually used to generate a column.  

//From Mdn Web

## Constructors

Constructor functions are used to create objects with a specific set of properties and methods.

The advantage of constructor functions is that they allow the user to create objects with only the necessary properties in question.  This saves construction time immensely, allows for genericness, and allows the user to harness information with little programming knowledge.

When 'this' is used in a constructor, the constructor function will call the variable from the object the constructor is ascociated with, and is more often than not actively generating.  'This' simply invokes the variable from the object. The constructor is a higher order function which calls the objects it constructs through.  

## Prototypes

Prototypes allows an object to utilize any number of user-defined methods.

Prototypes specify a set of functions which will be available for use as methods from the object associated with them.  Since the object shares all the methods associated with it, and there are sveral objects that can be created through the root object, which is normally the constructor function, we can assume that all functions genrated from the constructor also inherit all of the prototype functionality. Think about it as a geneologial tree structure.

The form when declaring a prototype is class.prototype.functionname. Imagine that the prototype local is the place-holder for the object to be constructed from the constructor function, which would then inherit all of the class's methods.