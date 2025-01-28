Library Management System
<br>
This is a simple Library Management System built using Angular. It allows users to:
<br>
<br>View a list of books.
<br>Search for books by title or author.
<br>Add new books to the collection.
<br>Edit or update existing books.
<br>Delete books from the list.
<br>The system uses a JSON Server backend to manage the books.
<br>
Features
Home Page (Book List)

Displays a list of all books.
Includes a search bar to filter books by title or author.
Offers "Edit" and "Delete" options for each book.
Includes an "Add Book" button to navigate to the add book form.
Add Book Page

A form to add a new book, including fields for Title, Author, ISBN, and Availability.
On submission, the new book is added to the backend and the user is redirected to the home page.
Includes a "Cancel" button to return to the home page without saving any changes.
Edit Book Page

Similar to the Add Book page but pre-populates the form with the book's details.
Allows users to update the book details and saves them to the backend.
Search Functionality

A search bar on the home page to filter the book list in real-time, by title or author (case-insensitive).
How to Run the Application
Prerequisites
Node.js installed on your system.
Angular CLI installed globally. (Install it with npm install -g @angular/cli)
JSON Server installed globally. (Install it with npm install -g json-server)
Steps to Run
Clone the Repository:

bash
Copy
git clone <repository-url>
cd library-management
Install Dependencies:

Copy
npm install
Start the JSON Server: Create a db.json file in the project root with the following content:

json
Copy
{
  "books": [
    { "id": 1, "title": "Angular Basics", "author": "John Doe", "isbn": "123456", "available": true },
    { "id": 2, "title": "Advanced Angular", "author": "Jane Smith", "isbn": "654321", "available": false }
  ]
}
Then start the JSON Server:

css
Copy
json-server --watch db.json
Start the Angular Application:

Copy
ng serve
The app will be available at http://localhost:4200.
