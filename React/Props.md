Props: Short for properties, these are used to pass data from a parent component to a child component

1. [[Props]]: Short for properties, props are how components talk to each other. They are passed down from parent to child components.

2. [[PropTypes]]: A library that allows you to runtime check the types of the props passed to the component.

3. [[DefaultProps]]: Default props can be defined as a property on the component function to set default values for props.

4. [[Destructuring Props]]: A JavaScript feature that allows you to extract multiple properties from an object more concisely in your component's arguments.

5. [[Passing Functions as Props]] Props can be any type of JavaScript variable, including functions. This allows parent components to pass functions to children, which can then communicate back up to the parent.

6. [[Spread Operator in Props]]: The spread operator (...) can be used to split up the properties in an object and apply them to a component.

7. [[Props in Class Components]]: In class-based components, props must be accessed with `this.props`.

8. [[Props in Functional Components]]: In functional components, props are typically accepted as a single argument.

9. [[Prop Drilling]]: The process by which you pass data from part of the component tree to another by going through other parts that do not need the data but are merely passing it along.

10. [[Props Children]]: A special prop (`this.props.children`) that lets the component access the content within its opening and closing JSX tags.

11. [[Readonly Props]]: Props are readonly in React components. This means a component cannot modify its own props.

12. [[Optional Props]]: While defining PropTypes, some props can be marked as optional if the component has sensible default values or can handle missing data.

13. [[Required Props]]: PropTypes can also be marked as required, signaling that the component expects this prop to always be passed.

14. [[Validation of Props]]: Using PropTypes, it's possible to validate props for presence, type, shape, etc.

15. [[Passing Props to Native HTML Elements]]: In addition to custom components, props can also be passed to native HTML elements like `<div>`, `<button>`, etc.

16. [[State vs. Props]]: Two different ways of handling data in React. State is managed within the component and can change over time, while props are passed into a component and are fixed throughout the component's life.

17. [[Computed Props]]: Props that are calculated based on other props or state.

18. [[Props Flow]]: In React, props flow down the components tree. A parent component passes properties down to its child components.

19. [[Higher-Order Components (HOCs) and Props]]: HOCs are functions that take a component and return a new component with additional props.

20. [[Custom Prop Attributes]]: Besides the built-in DOM attributes, you can also pass in custom attributes as props. However, they should be prefixed with `data-` to be valid HTML and avoid potential issues.
