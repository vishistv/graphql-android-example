# graphql-android-example
Using graphql in android


SETUP 

- Add Authorization Token from github API

- If changing the schema.json and the queries
  - run npm install apollo-codegen
  - node_modules/.bin/apollo-codegen download-schema https://api.github.com/graphql --output schema.json --header "Authorization: Bearer <TOKEN>"
  - Now create a graphql folder in the /main directory
  - Here you need to create two files, 
    - A .graphql file: where all your graphql queries go
    - And the schema.json file which you got from running the command 

