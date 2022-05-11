# Simple API using Fiber and Mongo

This little project explains how to create an API using Fiber as framework and MongoDB to store the data.

The code is fairly simple, the entire logic is in the main function and the connect() is used to instantiate a new MongoDB client to be used later.

MongoDB uses a BSON format (binary Json) to store the data.

The API exposes 4 endpoints:

- Get all Employees

- Create an Employee (POST); this also checks the syntax of the request through the BodyParser function

- Update an Employee (PUT); this also checks the syntax of the request through the BodyParser function

- Delete an Employee (DELETE)
