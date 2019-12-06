# trv-venue-hotel-api

To mock server, we are using JSON-server(https://www.npmjs.com/package/json-server)

## Run server
To install the server, run the below command in 'trv-venue-hotel-api' folder
   - ```npm install -g json-server```

To start the server, run the below command in 'trv-venue-hotel-api' folder
  - ```json-server --watch db.json --port 3001```
  - db.json is the mock json we provided.
  - we run server on port 3001

## JSON Structure
"hotel" array
 - It has list if hotel objects
 - Each hotel object has basic details necessary for a hotel

"moreInfo" array
 - It has list of hotel details objects
 - Each object has extra information we expect from a hotel

"details" array
 - It has list of information we show on details page of each hotel
 - Each object has all details of hotel and list of 2 rooms

"rooms" array
 - It has list of objects for room details of hotels
 - Each object has list of rooms available for each hotel

"bookings" array
 - All the bookings done will be updated in this array
