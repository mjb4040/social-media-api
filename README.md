# social-media-api

## Description
An API for a social media app built with Express.js, Mongoose.js and MongoDB.

## Demo Video
https://youtu.be/yaCkOrPzK0E

## Repo URL

## Usage
- Install and start MongoDB
- Clone code 
- Run NPM install 
- Run NPM start or NPM run dev to start the API 
- Use Insomnia to test the endpoints

## Technologies
- Node.js
- Express.js
- Mongoose.js
- Nodemon
- MongoDB

## Endpoints

**User**
- Get all users:        `GET /api/users`
- Create a user:        `POST /api/users`
- Get user by ID:       `GET /api/users/:id`
- Update a user:        `PUT /api/users/:id`
- Delete a user:        `DELETE /api/users/:id`
- Add a friend:         `POST /api/users/:userId/friends/:friendId`
- Delete a friend:      `DELETE /api/users/:userId/friends/:friendId`

**Thought**
- Get all thoughts:     `GET /api/thoughts`
- Create a thought:     `POST /api/thoughts`
- Get thought by ID:    `GET /api/thoughts/:id`
- Update a thought:     `PUT /api/thoughts/:id`
- Delete a thought:     `DELETE /api/thoughts/:id`

**Reaction**
- Add a reaction:       `POST /api/thoughts/:id/reactions`
- Delete a reaction:    `DELETE /api/thoughts/:id/reactions/:id`
