<h2 align="center" font-weight="bold">User Management System (Basic CRUD app)</h2>
<h3 align="left">This web app provides CRUD operations for managing user data and includes.
<h3 align= "left" font-weight= "bold">Features:- </h3> 
User Management: Allows creating, reading, updating, and deleting user data.
Data Persistence: Uses MongoDB with Mongoose for database operations.
Interactive UI: Utilizes EJS templates for rendering dynamic views. Static File Serving: Static files (e.g., CSS, images) served through Express middleware. interactive views for easy data manipulation. 
<h3 align= "left" font-weight= "bold">Endpoints:-  </h3>
GET /: Renders the homepage with basic information. 
GET /read: Displays a list of all users in the database. 
GET /delete/:id: Deletes a user by their ID.
GET /edit/:userid: Renders a form to edit details for a specific user.
POST /update/:userid: Updates user information based on the submitted form data. 
POST /create: Creates a new user based on the submitted form data. 
<h3 align= "left" font-weight= "bold">Dependencies:- </h3> express: Web application framework for Node.js. ejs: Templating engine for rendering HTML templates. mongoose: MongoDB object modeling tool for Node.js.



<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> </a> </p>
