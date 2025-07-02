# todos-crud-user
BE

This is the BE code for the Todo App. It provides the API endpoints and handles database operations for managing todos.

## Architecture Followed

MVC (Model View Controller) Architecture </br>

The architecture followed is an mvc architecture where models and controllers are in server whereas view are in our client app.

## Technologies Used

<ul>
    <li>Node.js with Express.js for building the server</li>
    <li>MongoDB for the database</li>
    <li>JWT for authentication</li>
    <li>bcrypt for password hashing</li>
    <li>mongoose for database operations</li>
    <li>dotenv for environment variables</li>
    <li>cors for cross origin resource sharing</li>
    <li>nodemon for hot reloading</li>
</ul>

## Folder Structure

The server code is organized into the following directories:

<ul>
<li><strong>`controllers:`</strong> Contains the request handlers for each API endpoint.</li>
<li><strong>`models:`</strong> Contains the mongoose models for the database.</li>
<li><strong>`routes:`</strong> Contains the API routes.</li>
<li><strong>`middleware:`</strong> Contains the auth middleware function.</li>
<li><strong>`index.js:`</strong> Entry point of the application.</li>
</ul>
