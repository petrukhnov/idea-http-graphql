# idea-http-graphql
Example of using idea to connect to graphql

Based on the https://learning.postman.com/docs/sending-requests/graphql/graphql-client-first-request/

## Step-by-step guide

1. Install GraphQL plugin and restart IDE
2. Get url for the endpoint. From the webpage it would be: `https://graphql.postman-echo.com/graphql`
3. Create new file with config [graphql.config.yml](postman-echo-example/graphql.config.yml). Note the filename should be exact.
4. Run the endpoint. It would generate new file: [postman-echo.graphql](postman-echo-example/postman-echo.graphql)
5. Create new file: [request-example.http](postman-echo-example/request-example.http)
6. Add few requests (enjoy autocomplete) and run them


