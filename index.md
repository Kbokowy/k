<!DOCTYPE html>
<link rel="stylesheet" href="styles.css">
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Adaptive Sports Connection</title>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Programs</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h1>Welcome to Adaptive Sports Connection</h1>
        <p>Empowering individuals with disabilities through sports</p>
        <a href="#" class="btn">Learn More</a>
    </section>
    <section class="programs">
        <h2>Our Programs</h2>
        <div class="program">
            <img src="program1.jpg" alt="Program 1">
            <h3>Program 1</h3>
            <p>Program 1 description goes here.</p>
        </div>
        <div class="program">
            <img src="program2.jpg" alt="Program 2">
            <h3>Program 2</h3>
            <p>Program 2 description goes here.</p>
        </div>
    </section>
    <!-- More sections and content here -->
    <footer>
        <p>&copy; 2023 Adaptive Sports Connection</p>
    </footer>
</body>
</html>
CSS/SCSS (styles.scss):

scss
Copy code
/* Reset some default styles */
body, h1, h2, h3, p {
    margin: 0;
    padding: 0;
}

/* Define common styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav li {
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

.hero {
    text-align: center;
    padding: 100px 0;
}

.hero h1 {
    font-size: 36px;
}

.hero p {
    font-size: 18px;
    margin-top: 20px;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    background-color: #333;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px;
    transition: background-color 0.3s;
}

.btn:hover {
    background-color: #555;
}

.programs {
    padding: 40px 0;
    background-color: #fff;
    text-align: center;
}

.program {
    margin-bottom: 40px;
}

.program img {
    max-width: 100%;
}

/* Add more styles for other sections and elements as needed */

footer {
    text-align: center;
    padding: 20px 0;
    background-color: #333;
    color: #fff;
}

/* Media queries for responsive design can be added here */
Make sure to adjust the content, images, and styles according to your specific requirements and branding. This is just a basic starting point for the home page.





