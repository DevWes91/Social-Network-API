# Social Network API

## Description 
A robust API for a social network application where users can share thoughts, react to friends' thoughts, and create a friend list. Built with Express.js, MongoDB, and Mongoose ODM.

## Table of Contents 
[Installation](#installation) 
[Usage](#usage) 
[API Routes](#api-routes) 
[Technologies](#technologies) 
[Demo](#demo)

## Installation 
1. Clone the repository
2. Install dependencies: ```bash npm install ```
3. Start MongoDB server
4. Start the application: ```bash npm start ```

## Usage 
Use Postman or another API client to test the endpoints. The API allows you to: * Create, read, update, and delete users * Add and remove friends * Create, read, update, and delete thoughts * Add and remove reactions to thoughts

## API Routes

### Users 
`GET /api/users` - Get all users 
`GET /api/users/:userId` - Get single user 
`POST /api/users` - Create user 
`PUT /api/users/:userId` - Update user 
`DELETE /api/users/:userId` - Delete user

### Friends 
`POST /api/users/:userId/friends/:friendId` - Add friend 
`DELETE /api/users/:userId/friends/:friendId` - Remove friend

### Thoughts 
`GET /api/thoughts` - Get all thoughts
`GET /api/thoughts/:thoughtId` - Get single thought
`POST /api/thoughts` - Create thought 
`PUT /api/thoughts/:thoughtId` - Update thought 
`DELETE /api/thoughts/:thoughtId` - Delete thought

### Reactions 
`POST /api/thoughts/:thoughtId/reactions` - Create reaction 
`DELETE /api/thoughts/:thoughtId/reactions/:reactionId` - Delete reaction

## Technologies 
* Node.js
* Express.js
* MongoDB
* Mongoose ODM
* JavaScript

## Demo
[View Demo Video](https://drive.google.com/file/d/1Wt5mV_zRuqR-YSAb2y172Mwbcznq1R9o/view?usp=drive_link)

## License 
Please refer to the LICENSE in the repo.
