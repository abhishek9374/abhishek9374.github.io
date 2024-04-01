<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="container">
    <div class="profile">
        <img src="profile.jpg" alt="Profile Picture" class="profile-image">
        <h1 class="name">Your Name</h1>
        <div class="contact-info">
            <p class="address">Address: Your Address</p>
            <p class="phone">Phone: Your Phone Number</p>
        </div>
        <div class="description">
            <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec nisi ac urna luctus viverra.</p>
        </div>
    </div>

    <div class="experience column">
        <h2 class="section-title">Experience</h2>
        <ul class="experience-list">
            <li>Experience details go here...</li>
            <li>Experience details go here...</li>
            <!-- Add more experience items as needed -->
        </ul>
    </div>

    <div class="education column">
        <h2 class="section-title">Education</h2>
        <ul class="education-list">
            <li>Education details go here...</li>
            <li>Education details go here...</li>
            <!-- Add more education items as needed -->
        </ul>
    </div>
</div>

</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

.container {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.profile {
    text-align: center;
}

.profile-image {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 20px;
    border: 5px solid #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.name {
    margin: 0;
    color: #333;
}

.contact-info {
    margin-bottom: 20px;
}

.description {
    margin-bottom: 20px;
    color: #666;
}

.section-title {
    font-size: 24px;
    font-weight: bold;
    color: #333;
    margin-bottom: 10px;
}

.column {
    float: left;
    width: 50%;
    padding: 0 20px;
    box-sizing: border-box;
}

ul {
    list-style: none;
    padding: 0;
}

li {
    margin-bottom: 10px;
    color: #666;
}
