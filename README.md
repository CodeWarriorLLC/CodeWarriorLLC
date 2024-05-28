<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CodeWarrior LLC</title>
    <style>
        body, html {
            height: 100%;
            margin: 0;
            font-family: Arial, sans-serif;
            background: url('https://github.com/CodeWarriorLLC/CodeWarriorLLC/assets/170987014/1dd43a63-da32-4ed0-a122-9680cc7ef417') no-repeat center center fixed;
            background-size: cover;
        }
        .company-name {
            position: absolute;
            top: 20px;
            width: 100%;
            text-align: center;
            font-size: 36px;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .dropdown {
            position: absolute;
            top: 50%;
            left: 10%;
            transform: translateY(-50%);
            display: inline-block;
        }
        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #f9f9f9;
            min-width: 200px;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 1;
        }
        .dropdown-content a {
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }
        .dropdown-content a:hover {
            background-color: #f1f1f1;
        }
        .dropdown:hover .dropdown-content {
            display: block;
        }
        .dropdown-btn {
            padding: 10px 20px;
            font-size: 16px;
            color: #fff;
            background-color: #007bff;
            border: none;
            border-radius: 5px;
            text-align: center;
            text-decoration: none;
        }
        .dropdown-btn:hover {
            background-color: #0056b3;
        }
        .contact-link {
            position: absolute;
            top: 20px;
            right: 20px;
            font-size: 16px;
            color: #007bff;
            text-decoration: none;
            background-color: rgba(255, 255, 255, 0.8);
            padding: 10px;
            border-radius: 5px;
        }
        .contact-link:hover {
            text-decoration: underline;
            background-color: rgba(255, 255, 255, 1);
        }
    </style>
</head>
<body>
    <div class="company-name">CodeWarrior</div>
    <div class="dropdown">
        <button class="dropdown-btn">Services</button>
        <div class="dropdown-content">
            <a href="custom-programming.html">Custom Programming</a>
            <a href="software-development.html">Software Development</a>
            <a href="microsoft-office.html">Microsoft Office Expert</a>
            <a href="financial-analysis.html">Financial Analysis</a>
            <a href="arcgis.html">ArcGIS</a>
            <a href="geospatial-databases.html">Geospatial Databases</a>
            <a href="api-integration.html">API Integration</a>
            <a href="system-integration.html">System Integration</a>
            <a href="data-analytics.html">Data Analytics & Visualization</a>
            <a href="business-intelligence.html">Business Intelligence</a>
            <a href="web-development.html">Web Development</a>
            <a href="technical-solutions.html">Technical Solutions</a>
            <a href="software-training.html">Software Training</a>
            <a href="versatile-industries.html">Versatile Across Industries</a>
        </div>
    </div>
    <a href="contact.html" class="contact-link">Contact Me</a>
</body>
</html>
