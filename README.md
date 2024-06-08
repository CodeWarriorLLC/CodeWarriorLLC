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
            color: #fff;
        }
        .header-2024 {
            background: rgba(0, 0, 0, 0.8);
            padding: 10px;
        }
        .header-wrap {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        .logo svg {
            width: 100px;
            height: auto;
        }
        nav {
            display: flex;
        }
        .nmcnav_primary {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }
        .nmcnav_li {
            position: relative;
        }
        .nmcnav_clickable {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            display: block;
            font-size: 16px;
        }
        .nmcnav_dropdown {
            display: none;
            position: absolute;
            background: rgba(0, 0, 0, 0.9);
            top: 100%;
            left: 0;
            min-width: 200px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
        }
        .nmcnav_dropdown ul {
            list-style: none;
            margin: 0;
            padding: 10px 0;
        }
        .nmcnav_dropdown a {
            color: #fff;
            padding: 10px 20px;
            display: block;
            text-decoration: none;
            font-size: 14px;
        }
        .nmcnav_li:hover .nmcnav_dropdown {
            display: block;
        }
        .nmcnav_text svg {
            fill: #fff;
            margin-left: 5px;
        }
    </style>
</head>
<body>
    <header class="header-2024">
        <div class="header-wrap">
            <div class="logo">
                <a href="/" rel="home" title="homepage" aria-label="homepage">
                    <svg xmlns="http://www.w3.org/2000/svg" width="244" height="153" viewBox="0 0 244 153" fill="none">
                        <!-- Your logo SVG content -->
                    </svg>
                </a>
            </div>
            <nav id="nmcnav_wrap" aria-label="Site Navigation">
                <ul class="nmcnav_primary" aria-label="Primary Navigation">
                    <li class="nmcnav_li">
                        <a href="products.html" class="nmcnav_clickable">Products</a>
                        <div class="nmcnav_dropdown" aria-labelledby="nmcnav_button-products" role="region">
                            <ul>
                                <li><a href="custom-programming.html">Custom Programming</a></li>
                                <li><a href="software-development.html">Software Development</a></li>
                                <li><a href="microsoft-office.html">Microsoft Office Expert</a></li>
                                <li><a href="financial-analysis.html">Financial Analysis</a></li>
                                <li><a href="arcgis.html">ArcGIS</a></li>
                                <li><a href="geospatial-databases.html">Geospatial Databases</a></li>
                                <li><a href="api-integration.html">API Integration</a></li>
                                <li><a href="system-integration.html">System Integration</a></li>
                                <li><a href="data-analytics.html">Data Analytics & Visualization</a></li>
                                <li><a href="business-intelligence.html">Business Intelligence</a></li>
                                <li><a href="web-development.html">Web Development</a></li>
                                <li><a href="technical-solutions.html">Technical Solutions</a></li>
                                <li><a href="software-training.html">Software Training</a></li>
                                <li><a href="versatile-industries.html">Versatile Across Industries</a></li>
                            </ul>
                        </div>
                    </li>
                    <li class="nmcnav_li">
                        <a href="about-us.html" class="nmcnav_clickable">About Us</a>
                        <div class="nmcnav_dropdown" aria-labelledby="nmcnav_button-about" role="region">
                            <ul>
                                <li><a href="our-story.html">Our Story</a></li>
                                <li><a href="our-team.html">Our Team</a></li>
                                <li><a href="our-board.html">Our Board</a></li>
                                <li><a href="careers.html">Careers</a></li>
                                <li><a href="contact-us.html">Contact Us</a></li>
                            </ul>
                        </div>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</body>
</html>
