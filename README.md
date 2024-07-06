
# Project Title

This project provides a simple API for managing users, allowing operations like creating, reading, updating, and deleting user records. It is built using Node.js and Express framework.


## User Management API 

Features
Create User: Add a new user with a unique identifier.

Read Users: Retrieve a list of all users or a specific user by ID.

Update User: Modify existing user information.

Delete User: Remove a user from the system.

Prerequisites

Before running this project, ensure you have the following installed:

Node.js (v12.x or higher)
npm (Node Package Manager) or yarn

## API Endpoints

GET /users: Retrieve all users.

POST /user: Create a new user.

GET /user/: Retrieve a user by ID.

PUT /user/: Update a user by ID.

DELETE /user/: Delete a user by ID.

## Usage
Creating a User
Send a POST request to /user with JSON body containing name, email, and contact fields.
{
  "name": "Abhijeet Kulkarni",
  "email": "Abhijeet@gmail.com",
  "contact": "1234567890"
}

Retrieving Users
Send a GET request to /users to retrieve all users.
Send a GET request to /user/:id to retrieve a specific user by ID.

Updating a User
Send a PUT request to /user/:id with JSON body containing updated name, email, and contact fields.

{
  "name": "Updated Name",
  "email": "updated.email@gmail.com",
  "contact": "9876543210"
}

Deleting a User
Send a DELETE request to /user/:id to delete a specific user by ID.


## Acknowledgments
Express.js - Fast, unopinionated, minimalist web framework for Node.js
uuid - For generating RFC compliant UUIDs
