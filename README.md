# The-Future-Hope-School<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My School Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to [Your School Name]</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#admissions">Admissions</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="home">
        <h2>Welcome to Our School</h2>
        <p>Your journey to quality education starts here!</p>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>We are dedicated to providing excellent education in a supportive environment.</p>
    </section>
    <section id="admissions">
        <h2>Admissions</h2>
        <p>Learn about our admission process and join us today!</p>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 [Your School Name]. All rights reserved.</p>
    </footer>
</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 2rem;
    border-bottom: 1px solid #ddd;
}

section h2 {
    color: #333;
}

form label {
    display: block;
    margin: 10px 0 5px;
}

form input, form textarea, form button {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
}
document.querySelector("form").addEventListener("submit", function(event) {
    event.preventDefault(); // Prevents page refresh
    alert("Thank you for reaching out! We will get back to you soon.");
});
/school-website
    index.html
    styles.css
    script.js
