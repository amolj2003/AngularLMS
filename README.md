<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Library Management System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0073e6;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        main {
            padding: 20px;
        }
        h1, h2 {
            color: #333;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            background-color: #fff;
            margin: 5px 0;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #0073e6;
            color: white;
        }
    </style>
</head>
<body>

    <header>
        <h1>Library Management System</h1>
        <p>A simple system to manage books in your library.</p>
    </header>

    <main>
        <h2>Features:</h2>
        <ul>
            <li>View a list of books</li>
            <li>Search for books by title or author</li>
            <li>Add new books</li>
            <li>Edit existing books</li>
            <li>Delete books from the list</li>
        </ul>

        <h2>How to Run the Application</h2>
        <p>1. Clone the repository:</p>
        <pre><code>git clone <repository-url></code></pre>
        
        <p>2. Install dependencies:</p>
        <pre><code>npm install</code></pre>
        
        <p>3. Start the JSON Server:</p>
        <pre><code>json-server --watch db.json</code></pre>
        
        <p>4. Start the Angular Application:</p>
        <pre><code>ng serve</code></pre>
    </main>

    <footer>
        <p>&copy; 2025 Library Management System</p>
    </footer>

</body>
</html>
