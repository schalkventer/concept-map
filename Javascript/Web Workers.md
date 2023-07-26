
35. [[Web Workers]] - A simple means for web content to run scripts in background threads

37. [[Web Workers]] - Web Workers are a simple means for web content to run scripts in background threads.

38. [[Dedicated Workers]] - These are workers that are utilized by a single script. They are not shared across different scripts or tabs.

39. [[Shared Workers]] - These are workers that can be utilized by multiple scripts running in the same origin, but in different tabs, windows, or iframes.

40. [[Worker Scope]] - A Worker has its own global scope, separate from the main thread's scope, which is often called "worker scope" or "worker global scope".

41. [[WorkerGlobalScope]] - It's an abstract interface that represents the global execution context of a worker, providing functionality available to both dedicated workers and shared workers.

42. [[Worker Objects]] - A Worker is an object created by a script in the main page, which runs a named JavaScript file, providing an easy means for workers to communicate with other workers or the main script.

43. [[postMessage()]] - The method used to send data to a Web Worker.

44. [[onmessage Event Handler]] - This event handler is used to receive data from a Web Worker.

45. [[Terminating a Worker]] - A web worker can be terminated by invoking the Worker.terminate() method from the main page.

46. [[Importing Scripts and Libraries]] - A worker can import scripts and libraries using the importScripts() method.

47. [[Worker Location]] - The worker location is represented by the WorkerLocation object, containing the actual script location of the Worker.

48. [[Worker Navigator]] - The worker navigator is represented by the WorkerNavigator object, and provides limited navigator functionality within the worker context.

49. [[Data Types and Structures]] - Workers can send and receive any kind of data or JavaScript objects, including ArrayBuffers and typed arrays.

50. [[Error Handling in Workers]] - Workers have an onerror handler for uncaught runtime errors.

51. [[Limitations of Web Workers]] - Web Workers run in an isolated thread, so they don't have access to the DOM or the window object. Also, they can't directly manipulate the webpage.

52. [[Worker Performance Considerations]] - Since workers are heavy resources, creating too many of them can degrade performance and increase memory usage.

53. [[Service Workers]] - These are a type of worker that act as a programmable network proxy, allowing you to control how network requests from your page are handled.

54. [[MessageChannel and MessagePort]] - These are part of the Web Messaging API and can be used for more complex communication between workers and the main thread.

55. [[Worker Threads and Concurrency]] - JavaScript is single-threaded, but workers can be used to achieve concurrent execution of JavaScript code.

56. [[Transferable Objects]] - These are objects that can be transferred from one context to another (like from a main thread to a worker, and vice versa) with a zero-copy operation, which vastly improves the performance of sending data to a worker.
