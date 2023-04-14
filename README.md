#Book-Record-Management Project
This is a project for managing book records using React and Express. Users can view, add, edit, and delete book records.

#Getting Started
To get started with the project, clone the repository and install the dependencies using the following commands:

git clone https://github.com/<username>/book-record-management.git
cd book-record-management
npm install
Running the Server
To run the server, use the following command:

npm start
The server will be running at http://localhost:8081.

#Contributing
Anyone can contribute to this project by making a pull request. Before making a pull request, please make sure to understand the code and follow the project's coding style.

#Routes
GET /: Displays a message indicating that the server is up and running.
GET /users: Returns a list of users.
GET /books: Returns a list of books.
POST /users: Adds a new user.
POST /books: Adds a new book.
PUT /users/:id: Updates a user with the specified id.
PUT /books/:id: Updates a book with the specified id.
DELETE /users/:id: Deletes a user with the specified id.
DELETE /books/:id: Deletes a book with the specified id.
#Error Handling
If a route is not found, a 404 error will be returned with the message "This route doesn't exist".
