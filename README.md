# 18 NoSQL: Social Network API

## Task

 To build an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. By using Express.js for routing, a MongoDB database, and the Mongoose ODM. In addition to using the [Express.js](https://www.npmjs.com/package/express) and [Mongoose](https://www.npmjs.com/package/mongoose) packages, We may also optionally use a JavaScript date library of our own choice or the native JavaScript `Date` object to format timestamps.

## Table of contents
* [User Story](#user-story)
* [Acceptance Criteria](#Acceptance-Criteria)
* [Screenshots](#Screenshots)
* [Mock-Up](#Mock-Up)
* [Application Functionality](#Application-Functionality)
* [Technologies Use](#Technologies-Use)
* [Contributor](#Contributor)


## User Story

```md
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria

```md
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

## Mock Up
The following video shows an example of the application being used from the command line: 
### <a href="">Video Link</a>

The application is build using the following tools & packages:

- Mongoose
- Express
- Node.js

## Application Functionality

The following API routes have been generated:

### For Users:

- GET:
  - Return all users in the database (including thoughts and friends from each user)
  - Return one user by id (including thoughts and friends from the user)
- POST:
  - Create a new user
  - Add a friend (other user) to a user's friend list
- PUT:
  - Update a user by id
- DELETE:
  - Remove a user by id
  - Remove a friend from a user's friend list

### For Thoughts:

- GET:
  - Return all thoughts in the database (including reactions for each thought)
  - Return one thought by id (including reactions for the thought)
- POST:
  - Create a new thought by specific user
  - Create a reaction to a thought
- PUT:
  - Update a thought by id
- DELETE:
  - Delete a thought by id
  - Delete a reation by id

## Usage

To test the API routes, use a tool like Postman or Insomnia.

## References

- Mongoose: https://mongoosejs.com/
- Express: https://expressjs.com/
- Node.js: https://nodejs.org/en/



## Contributor
Sorna Kesavan ©2022 All Rights Reserved.
- - -
