1. /helpers/create_router.js is responsible for defining the routes of the games resource.

2.Client is responsible for the app/game logic(frontend) and server is responsible for database/data(backend).

3.

4.

5.

6. The optional second argument is an init object, we are making a post request with a promise and resonse.json.

7.

8.We are using the driver to connect the app to the MongoDB database and to interact with data.



1. What is responsible for defining the routes of the `games` resource?
2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?
3. What are the the responsibilities of server.js?
4. What are the responsibilities of the `gamesRouter`?
5. What process does the the client (front-end) use to communicate with the server?
6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs
7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?