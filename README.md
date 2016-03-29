# GraphQL Example

GraphQL example using GraphiQL for friendly demonstration purposes. Technologies used: GraphQL, Node, PostgreSQL

###Getting Started###
```
	> npm install
	> babel-node server.js
```

Load up localhost:3000/graphql. Use the docs to read about what data you can fetch or add.

Example:
```
{
  people {
    firstName
    lastName
    email
    posts {
      title
      content
    }
  }
}
```