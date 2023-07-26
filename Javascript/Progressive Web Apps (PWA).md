81. [[Progressive Web Apps (PWA)]] - Web apps that use modern web capabilities to deliver an app-like experience to users
 PWAs are web applications that have been enhanced with modern web technologies, allowing them to provide a user experience similar to native apps (e.g., offline capability, push notifications).

2. [[Service Workers]] - Service workers are a type of web worker. They act as a proxy server that sits between web applications, the browser, and the network, allowing PWAs to cache assets and provide offline functionality.

3. [[Web App Manifest]] - The web app manifest is a JSON file that controls how a PWA appears to the user and how it can be launched. It includes properties like name, background color, display mode, and icons.

4. [[Add to Home Screen (A2HS)]] - A feature of PWAs that allows users to 'install' the web app on their device's home screen, making it available for offline use and launchable like a native app.

5. [[Offline Functionality]] - One of the key features of PWAs is their ability to work offline. This is achieved through caching strategies implemented by service workers.

6. [[Push Notifications]] - PWAs can receive push messages from a server, even when the web app is not active, through the Push API and Notifications API.

7. [[Background Sync]] - This feature allows you to defer actions until the user has stable connectivity. This is useful for ensuring that whatever the user wants to send is actually sent.

8. [[Fetch API]] - The Fetch API is a modern alternative to XMLHttpRequest for making network requests. It is promise-based and used heavily in service workers to cache network requests.

9. [[Promise-based APIs]] - Promises are used heavily in PWAs, for example in the Fetch API and in service workers. They allow for asynchronous operations and better handling of callbacks.

10. [[IndexedDB]] - IndexedDB is a low-level API for client-side storage of significant amounts of structured data, including files/blobs. It's used in PWAs for data persistence.

11. [[App Shell Architecture]] - This is an application design concept where the initial load of a PWA provides a shell of an app UI, and the content populates later as it becomes available.

12. [[Network Information API]] - This API provides information about the system's connection, which can be used to optimize the experience of PWA users.

13. [[Workbox]] - Workbox is a set of libraries developed by Google to remove a lot of the boilerplate code in writing service workers.

14. [[Responsive Design]] - PWAs should be built with a responsive design to ensure they provide a good user experience on any device.

15. [[PWA and Performance]] - PWAs aim to be fast and performant, and therefore involve strategies for efficient caching, resource prioritization, and load optimization.

16. [[Cross-Browser Compatibility]] - PWAs should work across all browsers that support the necessary web technologies (service workers, web app manifest, and more).

17. [[HTTPS Requirement]] - Service workers, and hence PWAs, require a secure context to work, so your site must be served over HTTPS.

18. [[Lighthouse]] - Lighthouse is an open-source, automated tool for improving the quality of web pages. It has audits for performance, accessibility, progressive web apps, and more.

19. [[PWA Discoverability]] - As PWAs are essentially websites, they are discoverable by search engines, which is a significant advantage over native apps.

20. [[Linkability]] - A key feature of the web, and hence PWAs, is the ability to link directly to specific content within the app.
