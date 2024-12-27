<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hair Salon</title>
    <link rel="stylesheet" href="styles.css">
</dinorashairsalon>
<dinorah>
    <header>
        <h1>Welcome to Our Hair Salon</h1>
        <nav>
            <ul>
                <li><a href="#services">Services</a></li>
                <li><a href="#promotion">Promotion</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Haircut<30$>
            <li>Coloring</100>
            <li>Styling</99>
            <li>Spa Treatments</99>
        </ul>
    </section>

    <section id="promotion">
        <h2>Special Promotion</h2>
        <p>Get 20% off your first visit! Use code: WELCOME20</p>
        <button id="applyPromotion">Apply Promotion</button>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@hairsalon.com</p>
        <p>Phone: (123) 456-7890</p>
    </section>

    <script src="scripts.js"></script>
</body>
</html>
Public code references from 6 repositories
Step 2: Add Styling with CSS
Create a CSS file (e.g., styles.css) to style the hair salon website.

CSS
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #white;
    color: #white;
    padding: 1em 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 2em;
    margin: 2em auto;
    max-width: 600px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
    color: #333;
}

button {
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}
 

    

    

 

