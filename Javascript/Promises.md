. [[Promises]] - Objects in JavaScript that link the "producing code" and the "consuming code" together.

Sure, here are 20 concepts related to promises in JavaScript along with brief summaries:

1. [[Promise Definition in JavaScript]] - A Promise is an object representing the eventual completion or failure of an asynchronous operation.

2. [[Creating a Promise]] - A Promise is created with the `new Promise()` constructor, which accepts a function (the executor) with two parameters: resolve and reject.

3. [[Promise States]] - A Promise can be in one of three states: pending, fulfilled, or rejected.

4. [[Promise.then()]] - The `then()` method returns a Promise. It takes up to two arguments: callback functions for the success and failure cases of the Promise.

5. [[Promise.catch()]] - The `catch()` method returns a Promise and deals with rejected cases only. It behaves the same as calling `Promise.then(undefined, onRejected)`.

6. [[Promise.finally()]] - The `finally()` method allows you to specify final code to run after the Promise is settled, regardless of whether it was fulfilled or rejected.

7. [[Promise Chaining]] - Promises can be chained together to perform a series of asynchronous operations. The return value of one callback is passed as input to the next `then()` callback.

8. [[Promise.all()]] - The `Promise.all()` method takes an iterable of promises and returns a new Promise that fulfills when all of the passed promises have been fulfilled, or rejects as soon as one of the promises reject.

9. [[Promise.race()]] - The `Promise.race()` method takes an iterable of promises and returns a new Promise that fulfills or rejects as soon as one of the promises in the iterable fulfills or rejects, with the value from that promise.

10. [[Promise.allSettled()]] - The `Promise.allSettled()` method takes an iterable of promises and returns a new Promise that fulfills when all of the passed promises have been either fulfilled or rejected, with an array of objects that describe the outcomes.

11. [[Promise.any()]] - The `Promise.any()` method takes an iterable of promises and returns the first promise that fulfills, or if all promises are rejected, a new AggregateError is thrown.

12. [[Promise Rejection Handling]] - Unhandled promise rejections can be caught at the global level by listening to the `unhandledrejection` event.

13. [[Creating Resolved or Rejected Promises]] - `Promise.resolve()` and `Promise.reject()` can be used to create a Promise that is immediately resolved or rejected with a given value.

14. [[Async-Await]] - The async/await syntax is a way to consume and produce Promises in a non-blocking manner that resembles synchronous code.

15. [[Error Handling in Promises]] - Errors in Promises can be caught using `catch()` method or the `try/catch` block with async/await.

16. [[Promise Composition]] - Complex asynchronous workflows can be composed using `Promise.all()`, `Promise.race()`, `Promise.any()`, and `Promise.allSettled()`.

17. [[Microtask Queue]] - Promises defer their onFulfilled/onRejected handlers to the microtask queue, which is processed after the current script has finished executing.

18. [[Promise Constructor]] - The Promise constructor is primarily used to wrap functions that do not already support Promises.

19. [[Promises and Timeouts]] - Promises can be used with `setTimeout()` to delay an operation, or to perform an operation if a Promise doesn't settle within a certain amount of time.

20. [[Promises and Fetch API]] - The Fetch API returns Promises. It's a modern, promise-based replacement for XMLHttpRequest for making network requests.
