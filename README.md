<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Car Cleaning Services</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Car Cleaning Services</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    /* styles.css */

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 1rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 2rem;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    position: absolute;
    width: 100%;
    bottom: 0;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-top: 1rem;
}

form input, form textarea {
    margin-top: 0.5rem;
    padding: 0.5rem;
}

form button {
    margin-top: 1rem;
    padding: 0.5rem;
    background-color: #333;
    color: white;
    border: none;
    cursor: pointer;
}


    <section id="home">
        <h2>Welcome to Car Cleaning Services</h2>
        <p>Your car deserves the best care. We provide top-notch cleaning services for all types of vehicles.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Exterior Washing</li>
            <li>Interior Detailing</li>
            <li>Waxing and Polishing</li>
            <li>Tire and Rim Cleaning</li>
        </ul>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We are a dedicated team of car enthusiasts who believe in providing the best cleaning services. Our mission is to make your car shine like new.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Car Cleaning Services. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

