# Online Voting App

## User Stories

- share my polls with my friends.
- see the aggregate results of my polls.
- delete polls that I decide I don't want anymore.
- create a poll with any number of possible items.
- unauthenticated or authenticated user, I can see and vote on everyone's polls.
- As an unauthenticated or authenticated user, I can see the results of polls in chart form. (This could be implemented using Chart.js)

## Getting Started

Include a `.env` file in the `server` directory with the following environment variables.

```
PORT = 4000
DATABASE = 'mongodb://localhost/<DATABASE_NAME>'
SECRET = 'ARandomGenratedkeyByusertokeephisauthenticationsecure'
```

## Built with

- nodejs
- express
- mongodb
- mongoose
- bcrypt
- jsonwebtoken
- react
