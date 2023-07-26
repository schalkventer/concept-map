Hooks: Functions that let you "hook into" React state and lifecycle features from function components

1. [[UseState Hook]]: A built-in hook in React that allows you to add state to functional components.

2. [[UseEffect Hook]]: A built-in hook in React that is used to perform side effects, such as fetching data or manipulating the DOM, in functional components.

3. [[useContext]]: A built-in hook that allows you to use context without wrapping a component in a Context.Consumer.

4. [[useReducer Hook]]: A built-in hook that allows you to handle complex state logic in functional components. It's similar to Redux in concept.

5. [[useMemo]]: A built-in hook that memoizes expensive computations and only re-computes when certain dependencies change.

6. [[useCallback]]: A built-in hook that returns a memoized version of the callback that only changes if dependencies change.

7. [[useRef Hook]]: A built-in hook that allows you to access and interact with DOM nodes directly, or store mutable values that don't cause re-renders when they change.

8. [[Custom Hooks]]: Functions that allow you to extract component logic into reusable functions. Custom hooks can use other hooks within them.

9. [[Rules of Hooks]]: Rules that must be followed when using hooks, including only calling hooks at the top level (not in loops or if statements), and only calling hooks from React functions.

10. [[Dependency Array]]: An array of dependencies that a hook relies on. If any dependency changes, the hook will run again.

11. [[Hook Flow]]: The sequence in which hooks are called and run in a React application.

12. [[useLayoutEffect]]: A built-in hook similar to useEffect, but it fires synchronously after all DOM mutations, before the browser has a chance to paint.

13. [[useState vs useReducer]]: Different ways of handling state within functional components, each with its own use cases.

14. [[Side Effects]]: Operations that affect state outside the scope of the function being executed. Hooks like useEffect are used to handle side effects.

15. [[State Hook]]: Hooks that manage and update state in a functional component.

16. [[useEffect Cleanup]]: The optional return function in useEffect that can be used to cleanup or revert side effects when the component unmounts or before the next effect runs.

17. [[Hook Testing]]: Techniques and libraries for testing hooks, such as the @testing-library/react-hooks package.

18. [[useImperativeHandle]]: A built-in hook that allows you to customize the instance value that is exposed to parent components when using ref.

19. [[useDebugValue]]: A built-in hook that can be used to display a label for custom hooks in React DevTools.

20. [[React DevTools]]: A browser extension that provides a suite of debugging tools, and has support for inspecting values returned by hooks.