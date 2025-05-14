**Brief Summary of How It Works**
This Express.js REST API allows you to manage a list of items (in-memory):

Start the Server

Run npm install → installs dependencies.

Run npm start → starts server at http://localhost:3000.

Root Route

GET / returns "Hello, World!"

CRUD Operations on Items

GET /items → Get all items

GET /items/:id → Get item by ID

POST /items → Create a new item (requires name & description)

PUT /items/:id → Update an item (requires name & description)

DELETE /items/:id → Delete an item by ID

Validation & Errors

Returns 400 for bad input, 404 for not found, and 500 for server errors

Invalid routes return a 404 JSON error

The data is stored in a simple array in memory (not a database). You can test it using Postman or any REST client.
