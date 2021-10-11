# Online Voting App

## Features

- Share my polls with my friends.
- See the aggregate results of my polls.
- Delete polls that I decide I don't want anymore.
- Create a poll with any number of possible items.
- Unauthenticated or authenticated user, I can see and vote on everyone's polls.
- As an unauthenticated or authenticated user, I can see the results of polls in chart form. (This could be implemented using Chart.js)

## Getting Started

Include a `.env` file in the `server` directory with the following environment variables.

```
PORT = 4000
DATABASE = 'mongodb://localhost/<DATABASE_NAME>'
SECRET = 'ARandomGenratedkeyByusertokeephisauthenticationsecure'
```

## Built with

- Node.js
- Express.js
- Mongodb
- Mongoose
- Bcrypt
- Jsonwebtoken
- React
