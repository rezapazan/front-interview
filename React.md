# React Interview Questions

**1. What is React Hooks?**

React Hooks are the built-in functions that permit developers for using the state and lifecycle methods within React components. These are newly added features made available in React 16.8 version. Each lifecycle of a component is having 3 phases which include mount, unmount, and update. Along with that, components have properties and states. Hooks will allow using these methods by developers for improving the reuse of code with higher flexibility navigating the component tree.

Using Hook, all features of React can be used without writing class components. For example, before React version 16.8, it required a class component for managing the state of a component. But now using the useState hook, we can keep the state in a functional component.

**2. Why do React Hooks make use of refs?**
Earlier, refs were only limited to class components but now it can also be accessible in function components through the useRef Hook in React.
The refs are used for:

- Managing focus, media playback, or text selection.
- Integrating with DOM libraries by third-party.
- Triggering the imperative animations.

**3. What are the different phases of the component lifecycle?**

- componentWillMount
- componentDidMount
- componentWillUpdate
- shouldComponentUpdate
- componentDidUpdate
- componentWillUnmount

**4. What are Higher Order Components?**
Simply put, Higher-Order Component(HOC) is a function that takes in a component and returns a new component. While developing React applications, we might develop components that are quite similar to each other with minute differences. In most cases, developing similar components might not be an issue but, while developing larger applications we need to keep our code DRY, therefore, we want an abstraction that allows us to define this logic in a single place and share it across components. HOC allows us to create that abstraction.

**5. How to prevent re-renders in React?**
