# Creating A GraphQL Server With Node And Express

# Description

The purpose of this app is provide a minimal effort on, how to setup a GraphQL server with [Node](https://nodejs.org/en/) and [Express](https://expressjs.com/en). We’ll be using the Express middleware [express-graphql](https://github.com/graphql/express-graphql) in our example that helps GraphQL to send queries and mutations to the server. And this example got the **CRUD** operation that speaks to GraphQL in schema/schema.js

And uses [json-server](https://github.com/typicode/json-server) which creates the Fake Api for us to play with it.

The two configuration properties which are used for the Express GraphQL middleware are the following:

- schema: The GraphQL schema which should be attached to the specific endpoint

- graphiql: Must be set to true to enable the GraphiQL tool when accessing the endpoint in the browser. GraphiQL is a graphical interactive in-browser GraphQL IDE. By using this tool you can directly write your queries in the browser and try out the endpoint.


# Running the App

In the project directory, you can run:

### `npm run dev`

Runs the app in the development mode.<br>
Open [http://localhost:5000](http://localhost:5000) to view it in the browser.

And The GraphQL endpoint is [http://localhost:5000/graphql](http://localhost:5000/graphql)

### `npm run json:server`

The api server will be concurrently runs on.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser
