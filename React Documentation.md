1.Q What is React?
Ans React is a open-source front-end JavaScript library for building user interfaces based on UI components.

2.Q Who made React?
Ans React was made by Jordan Walke

3.Q What is Babel?
Ans Babel is a open-source JavaScript transcompiler that is mainly used to convert ECMAScript 2015+ code into a 
backwards compatible version of JavaScript that can be run by older JavaScript engines. 

4.Q How does Babel convert html code in React into valid code?
Ans Babel acts as the compiler allowing us to leverage all the benefits of JSX while building React components

5.Q What is ReactDOM used for? Write an example?
Ans The react-dom package provides DOM-specific methods that can be used at the top level of app and as an 
escape hatch to get outside the React model if you need to.

6.Q What are the packages that you need to import for react to work with?
Ans 
1. React Testing Library
The React Testing Library is a lightweight solution for testing React components.
2. Framer Motion
Framer Motion is a production-ready motion library for React. The motions and animations are powered by the Framer library.
3. styled-components
styled-components allows you to write actual CSS code to style your React components. 

7.Q How do you add react to a web application?
Step 1: Add a DOM Container to the HTML
Step 2: Add the Script Tags
Step 3: Create a React Component

8.Q What is React.createElement?
Ans  Each JSX element is just syntactic sugar for calling React.createElement(). You will not typically invoke the following methods directly if you are using JSX.

createElement()
createFactory()

9.Q What are the three properties that createElement accept?
Ans React.createElement() takes three arguments. They are:
type: the type of the HTML element (h1,p,button).
props: properties of the object({style:{size:10px}} or Eventhandlers, classNames,etc).
children: anything that need to be displayed on the screen

10.Q What is the meaning of render and root?
Ans Render->to transmit to another : deliver.
Root->What is a root in React?
The root is where the application layout structure is defined. It is typically the first UI element a user interacts with. The root can be changed multiple times
 during the lifespan of the application. 

