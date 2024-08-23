
# [Module 18] Social Sphere: A Social Networking API

## Overview

Social Sphere is a backend API for a social networking application that allows users to share thoughts, react to friends' thoughts, and create a friend list. Built using Node.js, Express, and MongoDB, this API provides a robust and scalable solution for managing user data, thoughts, reactions, and friendships in a social networking environment.

## Features

- **User Management**: Create, update, and delete user profiles.
- **Thought Sharing**: Post, edit, and delete thoughts. Users can share what's on their mind with their friends.
- **Reactions**: Users can react to thoughts with reactions, similar to comments.
- **Friend List Management**: Add and remove friends to build a network of connections.
- **RESTful API**: Provides endpoints for all CRUD operations related to users, thoughts, reactions, and friendships.

## Technologies Used

- **Node.js**: For building the server-side application.
- **Express.js**: To handle routing and middleware functionalities.
- **MongoDB**: A NoSQL database to store user data, thoughts, reactions, and friendship connections.
- **Mongoose**: An ODM (Object Data Modeling) library for MongoDB and Node.js.
- **JavaScript**: For server-side scripting.

## Installation

To install and run Social Sphere locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd social-sphere
   ```
3. Install the necessary dependencies:
   ```bash
   npm install
   ```
4. Start the application:
   ```bash
   npm start
   ```

## Usage

1. Use a tool like Postman to interact with the API endpoints.
2. Create, read, update, and delete users, thoughts, and reactions.
3. Manage friends and see the impact of friendships on thoughts and reactions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Thanks to the developers of Node.js, Express.js, and MongoDB for providing the tools that made building this API possible.
- Special thanks to all contributors who provided feedback and support during the development of Social Sphere.
