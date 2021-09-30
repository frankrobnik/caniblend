**work in progress**

# caniblend

Web application to create custom smoothies. Search and blend ingredients and get detailed nutritional information about its composition. 

## Tech stack

**Frontend:** React, TypeScript, Tailwindcss

**Backend:** Expressjs, MongoDB, mongoose

## Screenshots

<img src="screenshots/caniblend_screenshot.jpg?raw=true" width=50% height=50%>


## Requirements

[mongoDB](https://docs.mongodb.com/manual/administration/install-community/) needs to be installed on your computer

## Installation

1. `git clone` this repo
2. setup your environment variables for the database and the server in `.env.example`
3. run `npm install` in the **server** folder
4. run `npm install` in the **client** folder
5. start the server within the **server** folder with `npx nodemon index.js` this will autopopulate the db with example ingredients and recipes
6. finally start the client in the **client** folder with `npm start`


**Happy blending** 🍍 🍉 🥕
