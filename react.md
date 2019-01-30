## Define React component?

<details>
  <summary>Answer here</summary>
  A chunk of a website that can be reused - includes JS, CSS, HTML
</details>

## What is the lifecyle of a React component?
* Created
* Mounted on the DOM
* Unmounted
* Destroyed

## Describe the different types of React Component?

<details>
  <summary>Answer here</summary>
  1. Function component:  a function that returns a single React Element.
  2. Class component: A JavaScript class that extends React.Component; must have a render method. 
</details>

## Describe the differences between class and function component (also in relation to props)?

<details>
  <summary>Answer here</summary>
  1. Function component:  stateless; use destructuring to access props.
  2. Class component: saves state; must use this.props.object after using the super keyword; must have a render method. 
</details>

## What do you use to pass data into components? Define that?

<details>
  <summary>Answer here</summary>
    Props: an object passed from parent to child. 
</details>

## What is controlled component?

<details>
  <summary>Answer here</summary>
  Controlled component: manages its own state. Form can be constructed as a controlled component. 
</details>

## Describe the error of directly managing state? 

<details>
  <summary>Answer here</summary>
  this.state = something 
</details>

## Define state? What are some examples of where we've managed state thus far?

<details>
  <summary>Answer here</summary>
  State is the data structure, and view reflects it within the DOM. Login/Logout would change the state of multiple elements.
</details>

## What are the types of React Components and what are pros and cons of each?

<details>
  <summary>Answer here</summary>
  The two types of React Components are Functional versus Stateful Class Components. Functional components are preferred if possible because of simplicity, however Stateful Class Components can be used to manage the state of a particular element if necessary. A recurrent example of a Stateful Class Component is with a Form, where the inputs should be managed by state.
</details>
<br>


## What is a React Component? Give an Example.

<details>
  <summary>Answer here</summary>
  A React Component is a function that returns a single react element, a repeatable part of a website. Examples might include a form, navbar, list, list item.
</details>
<br>

## What keyword should you use to change state in React? 

<details>
  <summary>Answer here</summary>
  this.setState({ data : newData })
</details>

## Define React lifecyle?

<details>
  <summary>Answer here</summary>
  The life of a React component, from birth (pre-mounting) and death (unmounting).
  Through lifecycle methods, we can then control what happens when each tiny section of your UI renders, updates, thinks about re-rendering, and then disappears entirely.
</details>

## When to use ComponentDidMount? 

<details>
  <summary>Answer here</summary>
  - This method is called once the component is mounted to the DOM.
  - Commonly used to load data with an ajax call. May set state in this method.
</details>

## When does component render?
<details>
  <summary>Answer here</summary>
  * when the state changes
  * Parent's props change
  * Component mounts the fist time
</details>

## Describe the concept of "state" and the pros and cons of using it.

<details>
  <summary>Answer here</summary>
  * State are objects that stores the information about a component.
  * States must be kept simple. States are the objects which determine components rendering and behavior.
  * accessed by this.state()
  * pros - powerful, render the components easily with state
  * cons - can be heavy

</details>
<br>

## What are the differences between html and jsx notation?

<details>
  <summary>Answer here</summary>
  JSX (Java Script XML) allows one to inject javascript into html notation and is used by React to generate more dynamic html. HTML is similar, but does not allow javascript outside of script tags.
</details>
<br>

## What is constructor?

<details>
  <summary>Answer here</summary>
  * This is the first method that gets called whenever a component is created. The constructor is called only once in the whole lifecycle of a component. It’s used to set up the initial values of variables and component state. 
  * Usage: Setup the initial state of the component.
</details>

## What is the difference between using React and not?

<details>
  <summary>Answer here</summary>
  React is a stronger tool when it comes to handeling state; it has an entire lifecycle system that allows your code to be more dynamic and 'react' to changes more efficiently. However, writing your code with a typical MCV model is also efficient depending on how dynamic your pages are.
</details>

## How do we access props?

<details>
  <summary>Answer here</summary>

- Props are properties passed down from the parent component. 
- Within a functional component, props are accessed directly with the argument props, or destructured keys of props. 
- Within a stateful class component props are accessed with this.props (after a constructor is built with props as an arguement and super(props){} is within that constructor)
</details>
<br>