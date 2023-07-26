Class Components: React components defined as classes with methods for handling lifecycle events.

1. [[Constructor]]: The constructor for a React component is called before it is mounted and is where you initialize state values and bind event handler methods.

2. [[State]]: The built-in object in a class component that contains data specific to that component. The state object is initialized in the constructor.

3. [[Props]]: Properties that allow you to pass values from a parent component down to a child component.

4. [[Lifecycle Methods]]: Special methods that automatically get called as your component gets rendered and updated. Examples include componentDidMount, componentDidUpdate, and componentWillUnmount.

5. [[Render Method]]: A required method in class components that tells React what to render and return.

6. [[this Keyword]]: Used in class components to refer to the current instance of the component.

7. [[componentDidMount]]: A lifecycle method that gets called immediately after a component is inserted into the tree. It's commonly used to perform setup logic for the component.

8. [[componentDidUpdate]]: A lifecycle method that is invoked immediately after updating occurs. It is not called for the initial render.

9. [[componentWillUnmount]]: A lifecycle method that is called just before the component is destroyed or removed from the DOM.

10. [[ShouldComponentUpdate]]: A lifecycle method that lets React know if a component's output is not affected by a change in state or props.

11. [[Event Handlers]]: Functions that are called in response to user actions like clicks, key presses, etc.

12. [[setState]]: The method used to update a component’s state.

13. [[Controlled Components]]: In a controlled component, form data is handled by the state within the component.

14. [[Error Boundaries]]: Class components can be used as error boundaries by defining the lifecycle method componentDidCatch. Error boundaries catch errors during rendering and in lifecycle methods and then render fallback UI.

15. [[PureComponent]]: A component that implements the lifecycle method shouldComponentUpdate with a shallow prop and state comparison.

16. [[React.createRef]] Used to create references in class components, which allow direct access to DOM elements or child components from the parent.

17. [[Default Props]]: Default props allow you to define default values for your props in a class component.

18. [[Higher Order Components (HOCs)]]: A function that takes a component and returns a new component. Can be used to share common functionality between components.

19. [[Context API]]: The Context API provides a way to pass data through the component tree without having to pass props down manually at every level.

20. [[getDerivedStateFromProps]]: A static lifecycle method invoked right before calling the render method, both on the initial mount and on subsequent updates. It should return an object to update the state, or null to update nothing.