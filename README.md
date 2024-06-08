<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CodeWarrior LLC</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            color: #fff;
            background: url('https://github.com/CodeWarriorLLC/CodeWarriorLLC/assets/170987014/1dd43a63-da32-4ed0-a122-9680cc7ef417') no-repeat center center fixed;
            background-size: cover;
            scroll-behavior: smooth;
            height: 100%;
        }
        .navbar {
            position: fixed;
            width: 100%;
            background: rgba(0, 0, 0, 0.8);
            padding: 10px 0;
            display: flex;
            justify-content: center;
            z-index: 1000;
        }
        .navbar ul {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }
        .navbar li {
            margin: 0 15px;
        }
        .navbar a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            display: block;
            font-size: 16px;
            transition: background 0.3s;
        }
        .navbar a:hover {
            background: #44C7F3;
            border-radius: 5px;
        }
        .section {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }
        .section h1 {
            margin-bottom: 20px;
            font-size: 3em;
        }
        .section .buttons {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .section a.button {
            background: #44C7F3;
            color: #fff;
            padding: 15px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 1.2em;
            transition: background 0.3s;
        }
        .section a.button:hover {
            background: #357ebd;
        }
    </style>
</head>
<body>

    <div class="navbar">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </div>

    <div id="home" class="section">
        <div>
            <h1>Welcome to CodeWarrior LLC</h1>
            <a href="index.html" class="button">Learn More</a>
        </div>
    </div>

    <div id="products" class="section">
        <div>
            <h1>Our Products</h1>
            <div class="buttons">
                <a href="custom-programming.html" class="button">Custom Programming</a>
                <a href="software-development.html" class="button">Software Development</a>
                <a href="microsoft-office.html" class="button">Microsoft Office Expert</a>
                <a href="financial-analysis.html" class="button">Financial Analysis</a>
                <a href="arcgis.html" class="button">ArcGIS</a>
                <a href="geospatial-databases.html" class="button">Geospatial Databases</a>
                <a href="api-integration.html" class="button">API Integration</a>
                <a href="system-integration.html" class="button">System Integration</a>
                <a href="data-analytics.html" class="button">Data Analytics & Visualization</a>
                <a href="business-intelligence.html" class="button">Business Intelligence</a>
                <a href="web-development.html" class="button">Web Development</a>
                <a href="technical-solutions.html" class="button">Technical Solutions</a>
                <a href="software-training.html" class="button">Software Training</a>
                <a href="versatile-industries.html" class="button">Versatile Across Industries</a>
            </div>
        </div>
    </div>

    <div id="about" class="section">
        <div>
            <h1>About Us</h1>
            <div class="buttons">
                <a href="our-story.html" class="button">Our Story</a>
                <a href="our-team.html" class="button">Our Team</a>
                <a href="our-board.html" class="button">Our Board</a>
                <a href="careers.html" class="button">Careers</a>
            </div>
        </div>
    </div>

    <div id="contact" class="section">
        <div>
            <h1>Contact Us</h1>
            <a href="contact-us.html" class="button">Get in Touch</a>
        </div>
    </div>

</body>
</html>
