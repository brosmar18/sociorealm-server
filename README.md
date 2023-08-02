# SocioRealm Backend

This repository contains the backend server for SocioRealm, a social media app. The server is built with Node.js and Express.

## Project Structure

The project is structured into several directories:

- `middleware`: Contains middleware used by the server
- `data`: Contains files related to database setup and management
- `models`: Contains data models or schemas for the database
- `controllers`: Contains the business logic for handling different routes
- `routes`: Contains the route definitions for the server

The `index.js` file is the main entry point for the server.

### Middleware

The `middleware` directory contains:

- `auth.js`: Authentication-related middleware

### Data

The `data` directory contains:

- `index.js`: Database setup and management

### Models

The `models` directory contains:

- `Post.js`: Schema for posts
- `User.js`: Schema for users

### Controllers

The `controllers` directory contains:

- `posts.js`: Business logic for post-related routes
- `users.js`: Business logic for user-related routes
- `auth.js`: Business logic for authentication-related routes

### Routes

The `routes` directory contains:

- `posts.js`: Post-related routes
- `users.js`: User-related routes
- `auth.js`: Authentication-related routes

## Tools Used

This project uses the following dependencies:

- `bcryptjs`: Library for hashing and salting user passwords.
- `body-parser`: Middleware to handle request body parsing.
- `cors`: Middleware to enable CORS (Cross-Origin Resource Sharing).
- `dotenv`: Module to load environment variables from a .env file.
- `express`: Web application framework for Node.js.
- `gridfs-stream`: To stream files to and from MongoDB GridFS.
- `helmet`: Helps secure Express apps by setting various HTTP headers.
- `jsonwebtoken`: To create access tokens for user authentication.
- `mongoose`: MongoDB object modeling tool designed to work in an asynchronous environment.
- `morgan`: HTTP request logger middleware for node.js.
- `multer`: Middleware for handling `multipart/form-data`.
- `multer-gridfs-storage`: Storage engine for Multer to store uploaded files directly to MongoDb.

## Setup

To set up the project for development, follow these steps:

1. Clone the repository
2. Install dependencies with `npm install`
3. Start the server with `npm start`

(Note: These steps assume that Node.js and npm are installed on your system)

Please refer to the individual directories for more specific documentation.

#### Acknowledgments

This project was developed by following along with a YouTube course. Much of the code is based on the lessons learned in the course. The original course can be found at [YouTube Course](https://www.youtube.com/watch?v=K8YELRmUb5o).

</sub>
