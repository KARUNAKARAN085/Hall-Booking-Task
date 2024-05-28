Hall Booking API

This documentation is about the Hall Booking application done using NodeJS and Express. This API allows you to manage room bookings, create rooms, and retrieve booking details.


Base URL: http://localhost:4000


Packages installed:

Express: npm i express
Cors: npm i cors
Nodemon: npm i nodemon


1. GET All Rooms Detais

URL: http://localhost:4000/rooms/list

List Rooms with Booking Data

Description: Retrives and displays the room json data using get method.
URL: /rooms/list
Method: GET
Example: http://localhost:4000/rooms/list



2. POST Create New Room

URL: http://localhost:4000/rooms/create


Description: Creates a new room with details about the room.

URL: /rooms/create

Method: POST

Example: http://localhost:4000/rooms/create


3. GET Display User Details

URL: http://localhost:4000/users/list

Display User Details

Description: Retrieves and displays a list of all customers and their details.

Method: GET

URL: /users/list

Example: http://localhost:4000/users/list


4. GET Display Booking data

URL: http://localhost:4000/users/count/1

Display Booking Data

Description: Retrieves and displays a list of all bookings made.

Method: GET

URL: /bookings/list

Example: http://localhost:4000/users/count/1


5. POST New Booking

URL: http://localhost:4000/bookings/book

New Booking

Description: Books a room for a customer on a specific date and time.

Method: POST

URL: /bookings/book

Example: http://localhost:4000/bookings/book

Postman Documentation link: https://documenter.getpostman.com/view/35182338/2sA3QsBYX1