# Webpack dev middleware example

Unlike webpack-dev-server, this middleware allows you do add to a node server 
in order to do things such as including a mock REST API for use in dev, etc.

This example includes a fake REST API for events:

    HEAD /user/:user/events  => Count all events
    GET /user/:user/events => List all events
    HEAD /user/:user/events/:type => Count all events of a specific type
    GET /user/:user/events/:type => List all events of a specific type
    GET /events/:id => Get a single event

----

## Install & Run:

    npm install
    npm start
    open http://localhost:3333
