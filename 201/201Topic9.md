# Forms

Forms are important since they are one of the main ways that users interact with web pages. Virtually every document that has functionality other than displaying of information interacts with the user in some way.  Forms a manner of prompting important information from the user.

When designing a form, it is important to display the prompt in a manner which is clear and concise to the user. One method for making prompts more clear is to utilize a placeholder attribute, which puts grayed text inside of the box.  Te gray text can represent an example of the type of information the form is expecting.

## 5 Form elements

1. <form> element is used to declare the form.
2. <fieldset> element is used to parse the form elements into semantically coherent groups.
3. <tr> declares a row.
4. <th> declares a column within a row that is utilized to display information about the form of the data it represents.
5. <td> declares a column within a row that is used to display the data itself.

## Events

Events are a firstly a form of a conditional statement.  It takes the form as follows:  IF an event occurs, such a mouse click over an icon, for example, THEN something will be happen, such as the icon being lit up with a bright color.  

The event itself is the operator (T or F), it determines whether the program executes what it has been programmed to do IF the event takes place.

When using addEventListener() method, you should specify the name of the event itself, and then follow it with function to be executed if the event occurs.

The event object is useful for implementing the executable code which will allow for user interaction.

### Event Bubbling vs. Capture

After an event is registered, one needs to specify which information is to be collected through it. Event capturing can only catch the information from the event object specified.

Event bubbling allows for capturing of information from the event object, if we also specify an anchor point from above the event object through an element ID.
