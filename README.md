## 💫 Overview
A simple demonstration of using sessions in Express.js to store and retrieve user data.

## 🪄 Features
- Using `express-session` middleware to manage sessions
- Storing and retrieving user data, such as view counts and usernames
- Demonstrating session persistence across multiple requests

## 🔗 API Endpoints
- `GET /viewcount`: Displays the number of times the page has been viewed, stored in the session
- `GET /register`: Sets the username in the session based on the query parameter
- `GET /greet`: Welcomes the user back with their stored username
