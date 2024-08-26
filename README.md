# CS465-FullStackDevelopmentI
CS-465 Full Stack Development with MEAN

JOURNAL

Architecture

•	Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

The Angular project structure differs significantly from that of the Express HTML customer-facing page.  Express is a backend framework that organizes server-side logic with controllers, routes, and middleware to handle HTTP requests and render HTML.  Angular is a front-end framework designed to create single-page applications (SPAs) which can dynamically load a single web document within a web browser.  Angular organizes the application into components, services, and modules to manage the user interface and data interactions.  
SPAs enable the webpage to change without having to load the entire webpage from the server.  The advantage of this is that less data is required to move between the web browser and the server.  Therefore, the website will run faster, and the user will have a more seamless experience.

•	Why did the backend use a NoSQL MongoDB database?

NoSQL MongoDB database is advantageous because it features horizontal scaling, making it able to handle large volumes of data.  It is flexible so data can be stored without defining the structure in advance.  MongoDB supports read and write operations as well as rich queries.  Also, it’s easy to integrate various programming languages with MongoDB.

Functionality

•	How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

JSON is a data format composed of key-value pairs.  It is used to transfer data between a server and a client in web applications.

JavaScript is a high-level programming language that is used to create dynamic effects within a web browser.  It can manipulate JSON data, HTML, and other things.

•	Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
One instance where the code was refactored was when the ‘trips’ data was changed from static HTML to Handlebars templates with JSON data.  This replaced 120 lines of static HTML with 35 lines of code.  This change enables the application to dynamically render trip data.  Reusable UI components allow for modularity so that components can be tested independently.  Also, it makes the application scalable. 

Testing

•	Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

HTTP Methods are used to make requests: GET, POST, PUT, and DELETE.  They are used in conjunction with endpoints, which are specific paths on the server where API requests are sent.  
Security includes authentication of the user or application before they can access the API.  JWT (JSON Web Tokens) are used to authenticate users.

Reflection

•	How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

This course has helped me adopt new skills that will help me build modern web applications.  I have learned how to use Visual Studio and Angular to build a dynamic, single-page (SPA) applications.  In addition, I have learned how to use Postman to test API endpoints.  This has taught me new ways to debug an application.  These skills make me more marketable as modern web applications are in demand.
