# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.

Good luck and happy coding! 🚀💻

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Application</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h1>Welcome to My Web Application</h1>
            <p>This is a sample paragraph to demonstrate HTML structure.</p>
        </section>
        <section>
            <h2>Features</h2>
            <ul>
                <li>Responsive Design</li>
                <li>JavaScript Interactivity</li>
                <li>Multiple Pages</li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 My Web Application</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>

Styling by css

/* styles.css */

/* General styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

/* Header styles */
header {
    background-color: #333;
    color: white;
    padding: 10px 0;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

/* Main content styles */
main {
    padding: 20px;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

/* Responsive design */
@media (max-width: 600px) {
    nav ul li {
        display: block;
        margin: 5px 0;
    }
}



JavaScript 
// script.js

document.addEventListener("DOMContentLoaded", function() {
    const button = document.querySelector("button");
    button.addEventListener("click", function() {
        alert("Button clicked!");
    });
});


Deployment 
Go to Vercel and log in or sign up.
Click New Project.


