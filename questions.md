# 1. What is responsible for defining the routes of the `games` resource?
The gamesRouter within the server side of the app.

# 2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?
Client is responsible for all functionallity of the front end, Server responsibilities seems to come down routing and db management.

# 3. What are the the responsibilities of server.js?
Require all of our server side dependancies, create the routing for our api.

# 4. What are the responsibilities of the `gamesRouter`?
The gamesRouter is responsible for directing the get/post/delete/put requests directing it in corespondance with the gamesCollection.

# 5. What process does the the client (front-end) use to communicate with the server?
The fetch process within the services/GameService.js file.

# 6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs
It can take an init object and in this application it is used to POST JSON data.

# 7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
POST for '/' is used when a game is added, DELETE for '/:id' is used for deleting items on the list.

# 8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?
I think it is being used to set up a connection between the app and the backend database.
