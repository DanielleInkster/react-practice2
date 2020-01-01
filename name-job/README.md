# Practice with React (The Sequel)

In an effort to get more practice with React, I completed a tutorial found here: 
https://www.taniarascia.com/getting-started-with-react/

This was a tutorial to complete a simple form to display names and occupations. The program can add, display and delete name/occupations. 

### Technologies
 - React
 - CSS
 - ***It's recommended but not strictly necessary to have a recent version of Node.js installed***
 
 ### How to install and run
 
 ```
 git clone git@github.com:DanielleInkster/react-practice2.git
 npm start (if Node is installed)
 
```

Reflection
I found this to be a better tutorial than the first. There was a bit less hand holding and a bit more inquiry needed to get it working properly. That said, I think I'm done with tutorials and ready to move in to my own projects to secure my understanding. I understand the basic concepts of React. I need to start experimenting to understand some of the finer details. 

What I've learned
Components are a Javascript class or function that takes properties as inputs and returns a React element that describes how the User Interface should look.

Functional Components are basically Javascript functions that are only for show, such as buttons. They don't use a render method
Class Components extend the component class in React. They usually implement logic and/or state.
Properties(Props) are immutable data (usually) passed from parent components to child components. I understand this in theory but would benefit from more hands-on practice. super(props) is used in the parent constructor only.

State is not inherited but created within the component itself. State is changed over time (usually by user activity) using this.state info and .setState (causes object to re-render). State remains within the component; it is not passed on to any child components.