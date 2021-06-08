# Create Post-Book API 

In this project we will create our own API of posts and connect it to a react front end. 

## What you will be doing

This project will allow you to practise using:

> CORS 
> Configuring application to allow cross origin requests. 


This project assumes you've already had experience with:

> - ExpressJS Routing
> - Http methods


## Task 1 - Getting ready

1. Initialise npm into your project
   `npm init -y`
2. Install the express.js npm package
   `npm i express`
3. Create a file for your server (`server.js`)


## Task 2 - Set up your server

##### starter code
```javascript
const express = require('express');
const app = express();

app.use(express.urlencoded({extended:true}));
app.use(express.json());

app.listen(4000, () => {
   console.log("The server is listening to requests") 
});
```

## Task 3 - Setting up routes 

  1. Create a folder /routes 
  2. Create a postsRoutes.js file 
  3. Import the route applications into your `server.js` file.
  4. Assign route applications to their respective route. `/post`


## Task 4 - Create a GET request in postsRoutes.js
  1. Create a GET request which exposes all the posts from dataposts.json

## Task 5 - Configure Cors
 1. Install the cors module
    `npm i cors`










