<H1>Library Management System</H1>
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
<br>

<br>Displays a list of all books.
<br>Includes a search bar to filter books by title or author.
<br>Offers "Edit" and "Delete" options for each book.
<br>Includes an "Add Book" button to navigate to the add book form.
<br>Add Book Page
<br>
<br>A form to add a new book, including fields for Title, Author, ISBN, and Availability.
<br>On submission, the new book is added to the backend and the user is redirected to the home page.
<br>Includes a "Cancel" button to return to the home page without saving any changes.
<br>Edit Book Page
<br>
<br>Similar to the Add Book page but pre-populates the form with the book's details.
<br>Allows users to update the book details and saves them to the backend.<br>
Search Functionality
<br>
<br>A search bar on the home page to filter the book list in real-time, by title or author (case-insensitive).
<br>How to Run the Application
<br>Prerequisites
<br>Node.js installed on your system.
<br>Angular CLI installed globally. (Install it with npm install -g @angular/cli)
<br>JSON Server installed globally. (Install it with npm install -g json-server)
<br>Steps to Run
<br>Clone the Repository:
<br>
bash
Copy
git clone <repository-url>
cd library-management
Install Dependencies:
<br>
Copy
npm install
Start the JSON Server: Create a db.json file in the project root with the following content:

json
<br>Copy
{
  "books": [
    <br>{ "id": 1, "title": "Angular Basics", "author": "John Doe", "isbn": "123456", "available": true },
    <br>{ "id": 2, "title": "Advanced Angular", "author": "Jane Smith", "isbn": "654321", "available": false }
  ]
}
Then start the JSON Server:

css
Copy<br>
json-server --watch db.json
<br>Start the Angular Application:

Copy<br>
ng serve<br>
The app will be available at http://localhost:4200.
