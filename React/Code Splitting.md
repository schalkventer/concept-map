. Code Splitting: A technique that allows you to split your code into smaller chunks which you can then load on demand

1. [[React.lazy]]: A function provided by React for loading components lazily through code splitting.

2. [[Dynamic Import]]: JavaScript feature that allows code to be loaded at runtime. It returns a promise resolving to the imported module.

3. [[React.Suspense]]: A component provided by React that allows rendering of some fallback content while waiting for the lazily-loaded component to be ready.

4. [[Bundle Splitting]]: The concept of splitting your code into various bundles which can be loaded on demand or in parallel.

5. [[Webpack]]: A static module bundler for modern JavaScript applications that can be used to split code.

6. [[Route-based code splitting]]: Concept where different routes of an application are split into separate code blocks, improving initial load time.

7. [[Async Component Rendering]]: Concept of rendering components only when they are needed or when the data they depend on is ready.

8. [[Lazy Loading]]: Loading components or modules only when they are needed, as opposed to loading them all at once at the start.

9. [[Babel]]: A JavaScript compiler that can transform syntax, enabling newer language features like dynamic imports.

10. [[Chunk]]: The name given to the code blocks created by webpack during code splitting.

11. [[Named Exports]]: Concept of exporting multiple named components or functions from a module which can then be lazily loaded in React.

12. [[Loadable Components]]: A higher-order component library for code splitting that automatically handles loading and error states, with support for server-side rendering.

13. [[Preloading]]: Loading a component in the background while the user is not immediately needing it, improving perceived performance for future navigation.

14. [[Prefetching]]: Similar to preloading, but usually done during idle time and with lower priority, helping future navigation.

15. [[Fallback UI]]: The interface displayed to the user while the split components are still loading, typically handled by React.Suspense.

16. [[SplitChunksPlugin]]: A Webpack plugin for additional control over chunk splitting, including heuristics for common/shared modules among chunks.

17. [[React.lazy with Named Exports]]: By default, React.lazy only works with default exports, but it can be worked around for named exports.

18. [[Error Boundaries]]: In case a lazily-loaded module fails, Error Boundaries can be used to catch and handle errors gracefully.

19. [[Server Side Rendering (SSR)]]: Concept of rendering the React app on the server, which brings additional complexities with code-splitting.

20. [[Concurrent Mode]]: A set of new features in React that help to render more complex UI's, enabling the use of React.lazy() with React.Suspense for data fetching.
