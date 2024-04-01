<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        .profile-image {
            width: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }
        .contact-info {
            margin-bottom: 20px;
        }
        .description {
            margin-bottom: 20px;
        }
        .section-title {
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 10px;
        }
        .column {
            float: left;
            width: 50%;
            padding: 0 10px;
        }
        .clearfix::after {
            content: "";
            clear: both;
            display: table;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="profile">
        <img src="profile.jpg" alt="Profile Picture" class="profile-image">
        <h1>Name</h1>
        <div class="contact-info">
            <p>Address: Your Address</p>
            <p>Phone: Your Phone Number</p>
        </div>
        <div class="description">
            <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec nisi ac urna luctus viverra.</p>
        </div>
    </div>

    <div class="experience column">
        <h2 class="section-title">Experience</h2>
        <p>Experience details go here...</p>
    </div>

    <div class="education column">
        <h2 class="section-title">Education</h2>
        <p>Education details go here...</p>
    </div>
</div>

<div class="clearfix"></div>

</body>
</html>
