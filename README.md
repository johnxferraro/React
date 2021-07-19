This is the first Iteration in getting the Learnatric App ready for launch. Its  build using React on the front-end and being served by a Node.js server on the back-end and using a PostgreSQL database for pertsistant storage.


*Get the APP Started Locally*

1. Clone repo to your machine and make sure you have Node and PostgreSQL installed on your machine

2. From inside the root directory run `npm install`

3. To start the server run `npm run start-dev` this will start the node server which serves the React App on port 8080. Its being run with nodemon so it will autmatically listen for changes and refresh accoedingly.

4. In a seperate terminal windo still from insode the root directory run `npm run watch` this will start a webpack server which compiles and bundles the react code and spits it out into a file called bundle.js in public/build and also listens for changes in the React files and automatically refreshes. And to see the app in the browser go to `http://localhost:8080`
