Components: These are the basic building blocks of a React application.

1. [[Functional Components]]: Components declared as a function in React. These can be stateless or stateful if they use React hooks.

2. [[Class Components]]: Components declared as a class in React. They can have lifecycle methods and state.

3. [[Component Lifecycle]]: The series of methods that are invoked in different stages of a component's existence. The lifecycle can be broken down into three main phases: Mounting, Updating, and Unmounting.

4. [[JSX]]: Stands for JavaScript XML. It allows you to write HTML in React, which then gets transformed into lightweight JavaScript objects.

5. [[Props]]: Short for properties, these are inputs to a React component and they can be data or functions.

6. [[State]]: A built-in object in a React component that contains data that may change over the life of the component.

7. [[Hooks]]: Introduced in React 16.8, Hooks let you use state and other React features in functional components instead of writing a class.

8. [[Context API]]: Provides a way to pass data through the component tree without having to pass props down manually at every level.

9. [[Higher Order Components (HOCs)]]: A function that takes a component and returns a new component, often used for reusing component logic.

10. [[Render Props]]: A technique for sharing code between React components using a prop whose value is a function.

11. [[Controlled Components]]: In React, form values like input, textarea and select are handled by the state within the component.

12. [[Uncontrolled Components]]: An alternative to controlled components where form data is handled by the DOM itself.

13. [[Synthetic Events]]: React wraps the browser’s native event into its own event instance for cross-browser compatibility.

14. [[Error Boundaries]]: A way to catch and handle errors in components during rendering phase, lifecycle methods, and constructors.

15. [[Pure Components]]: React.PureComponent is similar to React.Component. The difference between them is that React.Component doesn't implement shouldComponentUpdate(), but React.PureComponent implements it with a shallow prop and state comparison.

16. [[Fragments]]: A common pattern in React for a component to return multiple elements. Fragments let you group a list of children without adding extra nodes to the DOM.

17. [[Portals]]: Provides a way to render children into a DOM node that exists outside the DOM hierarchy of the parent component.

18. [[Context API]]: Provides a way to share values between different components without having to explicitly pass a prop through every level of the tree.

19. [[Memo]]: A higher order component that you wrap around a functional component to memoize (or remember) the rendered output and prevent unnecessary re-rendering.

20. [[Lazy and Suspense]]: React.Lazy helps to lazily load components while Suspense displays a fallback content while waiting for the lazy component to load.
