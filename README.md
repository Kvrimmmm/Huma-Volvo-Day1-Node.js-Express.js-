# Node.js & Express.js - Day 1 Assignment

## Project Overview

A backend application demonstrating core Node.js capabilities, including asynchronous File System (`fs`) operations, a native HTTP server, and a refactored RESTful API using Express.js structured with a clean MVC-style architecture.

## Project Structure

* `task2_fs.js`: Demonstrates native file system operations (read, write, append, and delete files with error handling).
* `task3_http.js`: Implements a native Node.js HTTP server managing student records.
* `app.js`: Main entry point for the Express.js application.
* `Routes/`: Contains routing configurations for the student endpoints.
* `Controllers/`: Contains the business logic and array manipulation for the API requests.

## Dependencies

* Node.js (Runtime Environment)
* Express.js (Web Framework)

## Quick Execution Steps

**1. Install Dependencies:**
`npm install`

**2. Run File System Task:**
`node task2_fs.js`

**3. Run Native HTTP Server (Port 3001):**
`node task3_http.js`

**4. Run Express.js Server (Port 3000):**
`node app.js`

*(Tip: You can use `nodemon app.js` for automatic server restarts during development).*
