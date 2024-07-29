### You are implementing a sample TODO's app. Your graphql-fetch SDK is not released yet, so it's accessible only locally.

1. Under ./graphql-fetch folder initialize a typescript based sdk, initialize npm library:
    * Implement a function called `graphqlFetch` - executes graphql call using native "fetch" function. The function accepts **endpoint**, **query**, **variables**.
1. "graphql-fetch" sdk should be transpiled and linked to ./react-app application
1. "react-app" it's an empty react application scaffolded by using "npx create-react-app"
1. In the app:
    1. Introduce a GraphQL query to fetch todos.
    1. Import "graphqlFetch" function from "graphql-fetch" sdk and call
    1. Fetch and render only 6 todos (only titles) by providing pagination option to the query

* The api is: https://graphqlzero.almansi.me/api
* See schema
![Alt text](API.png)
