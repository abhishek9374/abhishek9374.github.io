<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub README</title>
    <style>
        /* Reset styles */
        body, h1, h2, h3, p, ul, li {
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        .header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
        }

        .header-title {
            margin: 0;
        }

        .header-nav ul {
            list-style: none;
        }

        .header-nav ul li {
            display: inline;
            margin-right: 20px;
        }

        .header-nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        .section-title {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 20px;
        }

        .profile {
            display: flex;
            align-items: center;
        }

        .profile-image {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-right: 20px;
        }

        .profile-info {
            flex-grow: 1;
        }

        .footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        /* Inline code styling */
        p code {
            background-color: #f8f8f8;
            padding: 2px 5px;
            border-radius: 3px;
            font-family: Consolas, monospace;
            font-size: 14px;
        }
    </style>
</head>
<body>

<header class="header">
    <div class="container">
        <h1 class="header-title">Welcome to My GitHub README</h1>
        <nav class="header-nav">
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#education">Education</a></li>
            </ul>
        </nav>
    </div>
</header>

<section id="about" class="section">
    <div class="container">
        <h2 class="section-title">About Me</h2>
        <div class="profile">
            <img src="profile.jpg" alt="Profile Picture" class="profile-image">
            <div class="profile-info">
                <h3 class="name">Your Name</h3>
                <p class="address">Address: Your Address</p>
                <p class="phone">Phone: Your Phone Number</p>
                <p class="description">Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec nisi ac urna luctus viverra.</p>
            </div>
        </div>
    </div>
</section>

<section id="experience" class="section">
    <div class="container">
        <h2 class="section-title">Experience</h2>
        <ul class="experience-list">
            <li>Experience details go here...</li>
            <li>Experience details go here...</li>
            <!-- Add more experience items as needed -->
        </ul>
    </div>
</section>

<section id="education" class="section">
    <div class="container">
        <h2 class="section-title">Education</h2>
        <ul class="education-list">
            <li>Education details go here...</li>
            <li>Education details go here...</li>
            <!-- Add more education items as needed -->
        </ul>
    </div>
</section>

<footer class="footer">
    <div class="container">
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </div>
</footer>

</body>
</html>
