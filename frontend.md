## React.js

#### Q1. If you want to import just the Component from the React library, what syntax do you use?

- [ ] `import React.Component from 'react'`
- [ ] `import [ Component ] from 'react'`
- [ ] `import Component from 'react'`
- [ ] `import { Component } from 'react'`

#### Q2. If you see the following import in a file, what is being used for state management in the component?

`import React, {useState} from 'react';`

- [ ] React Hooks
- [ ] stateful components
- [ ] math
- [ ] class components

#### Q3. Why might you use Redux over Local State in a React component?

- [ ] when you want to replace Redux
- [ ] when you need to manage more complex state in an app
- [ ] when you want to improve performance
- [ ] when you want to break your production app

#### Q4. Which props from the props object is available to the component with the following syntax?

```javascript
<Message {...props} />
```

- [ ] any that have not changed
- [ ] all of them
- [ ] child props
- [ ] any that have changed

#### Q5. Consider the following code from React Router. What do you call :id in the path prop?

```javascript
<Route path="/:id" />
```

- [ ] This is a route modal
- [ ] This is a route parameter
- [ ] This is a route splitter
- [ ] This is a route link

#### Q6. If you created a component called Dish and rendered it to the DOM, what type of element would be rendered?

```javascript
function Dish() {
  return <h1>Mac and Cheese</h1>;
}

ReactDOM.render(<Dish />, document.getElementById('root'));
```

- [ ] `div`
- [ ] section
- [ ] component
- [ ] `h1`

#### Q7. What do you call the message wrapped in curly braces below?

```javascript
const message = 'Hi there';
const element = <p>{message}</p>;
```

- [ ] a JS function
- [ ] a JS element
- [ ] a JS expression
- [ ] a JSX wrapper

#### Q8. What is the difference between the click behaviors of these two buttons (assuming that this.handleClick is bound correctly)?

```javascript
A. <button onClick={this.handleClick}>Click Me</button>
B. <button onClick={event => this.handleClick(event)}>Click Me</button>
```

- [ ] Button A will not have access to the event object on click of the button.
- [ ] Button B will not fire the handler this.handleClick successfully.
- [ ] Button A will not fire the handler this.handleClick successfully.
- [ ] There is no difference.

#### Q9. Why is it important to avoid copying the values of props into a component's state where possible?

- [ ] because you should never mutate state
- [ ] because `getDerivedStateFromProps()` is an unsafe method to use
- [ ] because you want to allow a component to update in response to changes in the props
- [ ] because you want to allow data to flow back up to the parent

#### Q10. What is the children prop?

- [ ] a property that adds child components to state
- [ ] a property that lets you pass components as data to other components
- [ ] a property that lets you set an array as a property
- [ ] a property that lets you pass data to child elements

#### Q11. A representation of a user interface that is kept in memory and is synced with the "real" DOM is called what?

- [ ] virtual DOM
- [ ] DOM
- [ ] virtual elements
- [ ] shadow DOM

#### Q12. You have written the following code but nothing is rendering. How do you fix this problem?

```javascript
const Heading = () => {
  <h1>Hello!</h1>;
};
```

- [ ] Add a render function.
- [ ] Change the curly braces to parentheses or add a return statement before the `h1` tag.
- [ ] Move the `h1` to another component.
- [ ] Surround the `h1` in a `div`.

#### Q13. In which lifecycle method do you make requests for data in a class component?

- [ ] constructor
- [ ] componentDidMount
- [ ] componentWillReceiveProps
- [ ] componentWillMount

#### Q14. Why might you use a ref?

- [ ] to directly access the DOM node
- [ ] to refer to another JS file
- [ ] to call a function
- [ ] to bind the function

#### Q15. What is `[e.target.id]` called in the following code snippet?

```javascript
handleChange(e) {
  this.setState({ [e.target.id]: e.target.value })
}
```

- [ ] a computed property name
- [ ] a set value
- [ ] a dynamic key
- [ ] a JSX code string

#### Q16. What package contains the render() function that renders a React element tree to the DOM?

- [ ] `React`
- [ ] `ReactDOM`
- [ ] `Render`
- [ ] `DOM`

#### Q17. What do you need to change about this code to get it to run?

```js
class clock extends React.Component {
  render() {
    return <h1>Look at the time: {this.props.time}</h1>;
  }
}
```

- [ ] Add quotes around the return value
- [ ] Remove `this`
- [ ] Remove the render method
- [ ] Capitalize `clock`

#### Q18. How do you invoke setDone only when component mounts, using hooks?

```javascript
function MyComponent(props) {
  const [done, setDone] = useState(false);

  return <h1>Done: {done}</h1>;
}
```

- [ ] `useEffect(() => { setDone(true); });`
- [ ] `useEffect(() => { setDone(true); }, []);`
- [ ] `useEffect(() => { setDone(true); }, [setDone]);`
- [ ] `useEffect(() => { setDone(true); }, [done, setDone]);`

#### Q19. Currently, `handleClick` is being called instead of passed as a reference. How do you fix this?

```javascript
<button onClick={this.handleClick()}>Click this</button>
```

- [ ] `<button onClick={this.handleClick.bind(handleClick)}>Click this</button>`
- [ ] `<button onClick={handleClick()}>Click this</button>`
- [ ] `<button onClick={this.handleClick}>Click this</button>`
- [ ] `<button onclick={this.handleClick}>Click this</button>`

#### Q20. Which answer best describes a function component?

- [ ] A function component is the same as a class component.
- [ ] A function component accepts a single props object and returns a React element.
- [ ] A function component is the only way to create a component.
- [ ] A function component is required to create a React component.

#### Q21. What will happen when this useEffect Hook is executed, assuming name is not already equal to John?

```javascript
useEffect(() => {
  setName('John');
}, [name]);
```

- [ ] It will cause an error immediately.
- [ ] It will execute the code inside the function, but only after waiting to ensure that no other component is accessing the name variable.
- [ ] It will update the value of name once and not run again until name is changed from the outside.
- [ ] It will cause an infinite loop.

#### Q22. Which choice will not cause a React component to rerender?

- [ ] if the component calls `this.setState(...)`
- [ ] the value of one of the component's props changes
- [ ] if the component calls `this.forceUpdate()`
- [ ] one of the component's siblings rerenders

#### Q23. Per the following code, when is the Hello component displayed?

```javascript
const greeting = isLoggedIn ? <Hello /> : null;
```

- [ ] never
- [ ] when `isLoggedIn` is true
- [ ] when a user logs in
- [ ] when the Hello function is called

#### Q24. You have added a style property to the `h1` but there is an unexpected token error when it runs. How do you fix this?

```javascript
const element = <h1 style={ backgroundColor: "blue" }>Hi</h1>;
```

- [ ] `const element = <h1 style="backgroundColor: "blue""}>Hi</h1>;`
- [ ] `const element = <h1 style={{backgroundColor: "blue"}}>Hi</h1>;`
- [ ] `const element = <h1 style={blue}>Hi</h1>;`
- [ ] `const element = <h1 style="blue">Hi</h1>;`

#### Q25. Consider the following component. What is the default color for the star?

```javascript
const Star = ({ selected = false }) => <Icon color={selected ? 'red' : 'grey'} />;
```

- [ ] black
- [ ] red
- [ ] grey
- [ ] white

#### Q26. Which attribute must have a unique value each time it is used in an HTML document?

- [ ] title
- [ ] class
- [ ] style
- [ ] id

#### Q27. In this code, what is the term for the h1?

```css
h1 {
  color: red;
  font-size: 5em;
}
```

- [ ] selector
- [ ] combinator
- [ ] declarator
- [ ] markup

#### Q28. Which HTML will result in text being highlighted in yellow?

```css
.highlight {
  background-color: yellow;
}
```

- [ ] `<span class="highlight">#BLM</span>`
- [ ] `<span style="highlight">#BLM</span>`
- [ ] `<highlight">#BLM</span>`
- [ ] `<div id="highlight">#BLM</span>`

#### Q29. How does the rem unit represent a font size?

- [ ] Font sizes are expressed relative to the font size of the containing div element
- [ ] Font sizes are expressed relative to the font size of the parent elements
- [ ] Font sizes are relative to the base font size of the operating system.
- [ ] Font sizes are relative to the root em unit used in the HTML element.

#### Q30. Which description correctly describes the initial values of flex items if the only thing you have done is apply `display: flex` to their parent?

- [ ] Items display in a row, lined up at the start, and do not stretch to fill the container
- [ ] Items display in a column, lined up at the start, and do not stretch to fill the container
- [ ] Items stay in a column until you add some flex properties.
- [ ] Items display in a row, lined up at the start, and stretch to fill the container
