# Chainloop Demo

Source code used:
- in Chainloop documentation, how-to guides anbd blog posts,
- to demo the integration with Chainloop [seen here](https://www.youtube.com/watch?v=iBTVpjNaE6M).

Note: The example simple-todo app has been taken from https://github.com/bopbi/simple-todo

## simple-todo

A Simple REST Server app, using golang and sqlite, build for testing client app, the SQLITE file already contain some example data

### REST API

- GET ALL

      GET todos

- GET BY ID, example id is 12

      GET todos/12

- INSERT, it will return the json for new todo

      POST todos

- UPDATE BY ID, example id is 12 and it will return the json for new todo

      PUT todos/12

- DELETE BY ID, example id is 12

      DELETE todos/12
