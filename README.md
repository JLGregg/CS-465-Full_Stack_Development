# CS-465
Architecture
•	Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
o	ExpressHTML is used with Express framework for backend development with Node.js. 
o	JavaScript can create dynamic and interactive webpages which will add interactivity. It can also validate user input, manipulate Document Object Model and be used alongside HTML and CSS.
o	Single-page applications load a single HTML page and dynamically updates the content. In this project we used Angular, but Vue and React are also popular choices with React being the most popular. SPAs can run faster and smoother than traditional web pages but do have some drawbacks as well.
•	Why did the backend use a NoSQL MongoDB database?
o	MongoDB is flexible and does not use fixed schemas. It uses JSON format which works well with our JS code stack.
Functionality
•	How is JSON different from JavaScript and how does JSON tie together the frontend and backend development pieces?
o	JSON is based on JavaScript but is not the same thing. JSON is easy to read and write and can be used by many languages. JSON has a key, value format as well and ties together the front-end and back-end by providing a standardized data format for communication between them. 
•	Provide instances in the full stack process when you refactored code to improve functionality and efficiencies and name the benefits that come from reusable user interface (UI) components.
o	One way to make the code more efficient is to have all the functions within the trip-data.service.ts to be used for other components. For example, add-trip component will call the addTrip function from trip-data and edit-trip component will call the get-trip function to find the trip to edit.
Testing
•	Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
o	I tested the API by validating my endpoint, GET, POST, PUT, and DELETE, to make sure they functioned the way they are intended. After testing these, security was added by creating a login method to only allow a user who is logged in to add/edit trips.
Reflection
•	How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
o	The course has helped me to see all of my work I have done in previous courses work together to create a functioning website. It has let me create an API and see how both the front-end and back-end utilize it. This has helped me get started down a pathway that could lead to a full-stack career.

