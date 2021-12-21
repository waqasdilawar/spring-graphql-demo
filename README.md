# Spring GraphQL 

### Use below curl command to test the greeting endpoint after running.

`curl --location --request POST 'localhost:8088/graphql' \
--header 'Content-Type: application/json' \
--data-raw '{"query":"query greeting {\n greeting\n}","variables":{}}'`
