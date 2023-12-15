# Blog-Web-App
Project OverviewGenZies Blog is a general blog website, typically serves as a platform for individuals or organizations to publish and share content with an 
online audience. Below is an overview of key components and features:
Homepage:
• Displays a feed of the latest blog posts.
• Include featured posts and a carousel showcasing popular content.
Navigation:
• Menu bar and navigation links for easy access to different sections like Home, Blog, Categories, Pages, About, and Contact.
Blog Posts:
• Individual pages for blog posts.
• Each post includes a title, author, publication date, and the main content.
• Support for multimedia content such as images within blog posts.
• Social sharing buttons to facilitate content sharing on social media platforms.
Categories and Tags:
• Categorization of blog posts to help users find content on specific topics.
• Tagging system to add keywords to posts, enhancing searchability.
Search Functionality:
• Search bar for users to find specific content based on keywords.
Pagination or Load More Button:
• Option to navigate through multiple pages of blog posts.
• "Load More" button for dynamic loading of additional posts.
User Comments:
• Ability for users to leave comments on blog posts.
• Comment moderation features for the blog owner.
Author Profiles:
• Author information displayed on blog posts, including a bio and social media links.
• Author archives showcasing all posts by a specific author.
About Us Page:
• Information about the blog, its purpose, and the team behind it.
Contact Page:
• Form or contact details for readers to reach out to the blog owner or team.
Responsive Design:
• Mobile-friendly design to ensure a good user experience on various devices.
Search Engine Optimization (SEO):
• Meta tags, alt attributes, and other SEO best practices to improve search engine visibility.
Footer:
• Navigation links, copyright information, and social media icons.
Security Measures:
• Implementation of security best practices, including secure login and protection against common web vulnerabilities.
Customization:
• Theming options to customize the look and feel of the blog.

Features-
• Responsive design
• User login Page
• User sign up Page
• Blog Page that contains Image boxes with clickable content, "Load More Posts" button and image carousel for featured images.
• Each blog can be opened separately to a different page
• Comment section.

Prerequisites-
• Web browser
• Code editor (e.g., Visual Studio Code)

Dependencies Used-
• Bcrypt - It is a password-hashing library that is commonly used in web development to securely hash passwords before storing 
them in a database. It's specifically designed for hashing passwords.
• Express - It is a popular web application framework for Node.js allowing developers to build web applications with a simple and 
straightforward structure with robust routing system.
• Body-Parser- body-parser is a middleware for Express.js that is used to parse the body of incoming HTTP requests. It is 
essential when working with POST requests or any request that has a payload, as it extracts the data from the request body and 
makes it available in the req.body property.
• Ejs-EJS is a templating engine that allows you to embed JavaScript code directly into your HTML templates. It enables you to 
dynamically generate HTML content based on data from your server.
• Mongoose- Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node.js. It provides a higher-level, 
schema-based abstraction over the MongoDB database, making it easier to work with MongoDB using Node.js.
Database UsedMongoDB- It is a popular NoSQL database that is widely used in web development for several reasons that include flexible schema, ability 
to handel large data and supports JSON format.

Use of MongoDB in the projectConnection Setup:
The project establishes a connection to MongoDB using Mongoose. This connection is typically set up in the application's entry point (e.g., 
server.js). It specifies the MongoDB URI and any additional configuration options.

Schema Definition:
Mongoose allows developers to define a schema for their data models. In the project, you might define schemas for entities such as users, 
blog posts, or any other relevant data.

Model Creation:
Models are created based on the defined schemas. Models represent the structure of documents that can be stored in the MongoDB 
collection.

CRUD Operations:
Mongoose provides methods for performing CRUD (Create, Read, Update, Delete) operations on MongoDB collections. This includes
creating new documents, querying for documents, updating existing documents, and deleting documents.
Also used Mongoose to interact with MongoDB in conjunction with Express.js. For example, fetching data from the database and rendering 
it in EJS views.
It is also used for user authentication and validation purpose.
Overall, MongoDB, when used with Mongoose, provides a flexible and scalable solution for storing and retrieving data in a Node.js web 
application. The combination of a NoSQL database like MongoDB and a framework like Express simplifies the development of dynamic 
and data-driven web applications.
