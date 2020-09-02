# trv-event-api

To mock server, we are using JSON-server(https://www.npmjs.com/package/json-server)

## Run server

To install the server, run the below command in 'trv-event-api' folder

- `npm install -g json-server`

To start the server, run the below command in 'trv-event-api' folder

- `json-server --watch db.json --port 3001`
- db.json is the mock json we provided.
- we run server on port 3001

## JSON Structure

"cities" array

- It has list if cities objects
- Each city object has name and id

"events" array

- It has list of event details objects
- Each object has information we expect for an event
- A new node 'isSignedUp' is added through 'PATCH' call when the user signed up for the event.
