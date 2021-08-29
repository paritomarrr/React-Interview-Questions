
# React Interview Questions & Answers

Click ⭐if you like the project. Pull Request are highly appreciated. Follow me   [@tomarpari90](https://twitter.com/tomarpari90) for technical updates.





## Table of Content


```http

```

| S. No.  | Questions                |
| :-------- | :------------------------- |
| `1`  | What is React JS?             |
| |
| `2`  | Why React?                |
| |
| `3`  | What is JSX?             |
| |
| `4`  | What do you understand by Virtual DOM?           |
| |
| `5`  | Differentiate between Real DOM and Virtual DOM.           |
| |
| `6`  | Why can’t browsers read JSX?         |
| |
| `7`  | “In React, everything is a component.” Explain.     |
| |
| `8`  | What is the purpose of render() in React.    |
| |
| `9`  | What is Props? |
| |
| `10`  |What is a state in React and how is it used? |
| |
| `11`  |How can you update the State of a component?    |
| |




```http

```



  
## Answers

1. **What is React JS**
React.js is an open-source JavaScript library that is used for building user interfaces specifically for single-page applications. It’s used for handling the view layer for web and mobile apps. React also allows us to create reusable UI components. React was first created by Jordan Walke, a software engineer working for Facebook. React first deployed on Facebook’s newsfeed in 2011 and on Instagram.com in 2012.
 React allows developers to create large web applications that can change data, without reloading the page. The main purpose of React is to be fast, scalable, and simple. It works only on user interfaces in the application. This corresponds to the view in the MVC template. It can be used with a combination of other JavaScript libraries or frameworks, such as Angular JS in MVC

2. **Why React JS?**
React’s popularity today has eclipsed that of all other front-end development frameworks. Here is why:
 

- Easy creation of dynamic applications
- Improved performance
- Reusable components
- Unidirectional data flow
- Small learning curve
- It can be used for the development of both web and mobile apps

3. **What is JSX?**
 JSX stands for JavaScript XML.
It allows us to write HTML inside JavaScript and place them in the DOM without using functions like appendChild( ) or createElement( ).
As stated in the official docs of React, JSX provides syntactic sugar for React.createElement( ) function.

4. **What do you understand by Virtual DOM?**
A virtual DOM is a lightweight JavaScript object which originally is just the copy of the real DOM. It is a node tree that lists the elements, their attributes and content as Objects and their properties. React’s render function creates a node tree out of the React components. It then updates this tree in response to the mutations in the data model which is caused by various actions done by the user or by the system.

5. **Differentiate between Real DOM and Virtual DOM.**
```http

```

| Real DOM  | Virtual DOM                |
| :-------- | :------------------------- |
| 1.  It updates slow.  | 1. It updates faster.            |
| |
| 2. Can directly update HTML.  | 2. Can’t directly update HTML.               |
| |
| 3. Creates a new DOM if element updates.  | 3. Updates the JSX if element updates.              |
| |
|4. DOM manipulation is very expensive.  | 4. DOM manipulation is very easy.     |
| |
| 5. Too much of memory wastage.  | 5. No memory wastage.      |
| |



```http


```


6. **Why can’t browsers read JSX?** <br>
Browsers can only read JavaScript objects but JSX in not a regular JavaScript object. Thus to enable a browser to read JSX, first, we need to transform JSX file into a JavaScript object using JSX transformers like Babel and then pass it to the browser.

7. **“In React, everything is a component.” Explain.**
Components are the building blocks of a React application’s UI. These components split up the entire UI into small independent and reusable pieces. Then it renders each of these components independent of each other without affecting the rest of the UI.

8. **What is the purpose of render() in React.**
Each React component must have a render() mandatorily. It returns a single React element which is the representation of the native DOM component. If more than one HTML element needs to be rendered, then they must be grouped together inside one enclosing tag such as <form>, <group>,<div> etc. This function must be kept pure i.e., it must return the same result each time it is invoked.

9. **What is Props?** 
Props is the shorthand for Properties in React. They are read-only components which must be kept pure i.e. immutable. They are always passed down from the parent to the child components throughout the application. A child component can never send a prop back to the parent component. This help in maintaining the unidirectional data flow and are generally used to render the dynamically generated data.

 10. **What is a state in React and how is it used?**
The State is an updatable structure which holds the data and information about the component. It may be changed over the lifetime of the component in response to user action or system event. It is the heart of the react component which determines the behavior of the component and how it will render. It must be kept as simple as possible.
11. **How can you update the State of a component?**
We can update the State of a component using this.setState() method. This method does not always replace the State immediately. Instead, it only adds changes to the original State. It is a primary method which is used to update the user interface(UI) in response to event handlers and server responses.
