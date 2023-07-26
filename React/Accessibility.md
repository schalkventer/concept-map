Accessibility (A11y): The design of products to be usable by all people, to the greatest extent possible, including when it comes to dynamic web content

1. [[Semantic HTML]]: Writing code with HTML elements that accurately represent the content and functionality they encapsulate. Semantic HTML is crucial for accessibility as it provides meaning to the code which is used by screen readers and other assistive technologies.

2. [[WAI-ARIA]]: Web Accessibility Initiative - Accessible Rich Internet Applications (WAI-ARIA) is a technical specification by W3C that provides a framework to improve the accessibility and interoperability of web content and applications.

3. [[Keyboard Accessibility]]: Ensuring all functionality of the app can be achieved using only the keyboard. This is important for users who cannot use a mouse or similar pointing device.

4. [[Focus Management]]: Proper handling of focus in an application allows a user to navigate and interact with elements in the expected order. 

5. [[Accessible Forms]]: Labels should be used with all form elements so users understand what input is expected. 

6. [[Alt Text]]: Alt text should be provided for all non-decorative images. This text can be read by screen readers to describe the image.

7. [[Roles and Landmarks]]: Roles and landmarks provide information about what an element is or does, or the larger region of the page that it is part of. They can be assigned directly using ARIA roles.

8. [[Error Identification]]: Users should be notified of errors in input and these errors should be easy to understand and fix.

9. [[High Contrast]] UI: Users with vision impairments might need high contrast between foreground and background elements to perceive the content correctly.

10. [[Color]] and Color Contrast: Making sure there is enough contrast between the text color and its background is necessary for readability. Also, color should not be used as the only means to convey information.

11. [[Accessible Routing]]: When using routing in a React app, it is important to manage focus and announce page changes to assistive technologies.

12. [[Accessibility Testing]]: Regular testing for accessibility compliance should be part of the development process. Tools like Jest, Axe, and React Testing Library can be used for this.

13. [[Captioning and Transcripts]]: Providing captions for video content and transcripts for audio content helps those with hearing impairments.

14. [[Dynamic Content Updates]]: Changes in the state of a component or page should be communicated to assistive technologies using ARIA live regions.

16. [[Time-based Media Control]]: If an app contains any time-based media like videos or animation, controls for pause, play, and stop should be provided.

17. [[Bypass Blocks]]: Providing a way to bypass blocks of content that are repeated on multiple pages, like navigation menus.

18. [[React Accessibility Linters]]: Linters such as eslint-plugin-jsx-a11y can catch accessibility issues in the development phase itself.

19. [[Accessible Modals]]: Modals should be implemented in an accessible way, such as trapping focus within the modal when it is open and returning focus to the correct location once the modal is closed.

20. [[Readable Font Sizes]]: The text size should be big enough to read without straining the eyes, and users should be allowed to resize text as needed.
