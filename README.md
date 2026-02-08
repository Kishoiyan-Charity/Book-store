# Book Store
A simple web application to keep track of books you've read, including title, author, and publication year.
## Features
Add books with title, author, and publish year. View your reading list in table or card layout. Edit and delete book entries. MongoDB database for persistent storage. Clean and minimal user interface.

### Technologies
Frontend: HTML5, CSS3, JavaScript, Vite
Backend: Node.js
Database: MongoDB

### Installation
Clone the repository and install dependencies:
git clone
cd book-tracker

MONGO_URI=your_mongodb_connection_string
PORT=5555
#### Start the server:
npm run dev
The app will run on http://localhost:5000

GET /books = Get all books
POST /books = Add a new book
PUT /books/:id = Update a book
DELETE /books/:id = Delete a book


