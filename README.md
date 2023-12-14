# CS465

**Architecture**<br>

* Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).<br>

Express and Node.js combine to use a traditional model-view-controller design pattern. Angular, by contrast, creates a single-page application that does most of the work in the browser. SPA’s are great for speed once loaded, but bad for search engine optimization, social media previews, advanced analytics, and initial load time. Because of this, the Angular SPA was used for admin purposes, while Express/Node.js was used for the customer facing site.<br>

* Why did the backend use a NoSQL MongoDB database?<br>

The backend used a NoSQL database because it is more flexible than traditional SQL databases. The structure of each document can be unique, allowing for easier customization.
Functionality<br>

* How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?<br>

JSON is a standardized language used for transmitting documents. This makes it great for sending information to and from a database. It is also the format used in MongoDB, making it the logical delivery system.<br>

* Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.<br>

One specific case was using Handlebars to turn the hard-coded HTML into something that could be fed JSON data to create a dynamic site.  This same principle was repeated throughout the project. Reusable pieces of code, whether UI related or not, are desirable because it creates efficiencies in production and allows large-scale changes by changing just a few lines of code. The alternative would be repetitive code and having to change every instance of an object to change the look or functionality of a page.<br>

**Testing**<br>

* Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.<br>

I used both Postman and a local instance of the site for testing. This allowed testing the PUT, POST, GET, and DELETE API endpoints, with specific examples being loading the trip data, registering new users, and logging in. Security included hashing passwords before storing their values and using tokens to verify users once they were logged in. This made testing slightly more complicated, as tokens were required to test the various endpoints.<br>

**Reflection**<br>

* How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?<br>

This course has helped me more completely understand the full-stack process, including database management, security, controller classes, front-end development, and single-page applications. I am now comfortable interacting with a NoSQL database, ensuring a secure API, knowing when to use and SPA v. a traditional MVC pattern, and how to set up the architecture for a fully functioning website. All these skills give me the base to contribute to any full stack development.

