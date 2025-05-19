# Gym-management-System
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gym Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('Screenshot_20250115_185103.jpg') no-repeat center center fixed;
            background-size: cover;
            color: white;
        }

        .header {
            display: flex;
            justify-content: space-between;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.6);
        }

        .header .left, .header .middle, .header .right {
            display: flex;
            align-items: center;
        }

        .header .left img {
            width: 110px;
            margin-right: 10px;
        }

        .navbar {
            list-style: none;
            display: flex;
        }

        .navbar li {
            margin: 0 15px;
        }

        .navbar li a {
            text-decoration: none;
            color: white;
            font-size: 18px;
        }

        .navbar li a:hover {
            color: grey;
            text-decoration: underline;
        }

        .btn {
            background-color: black;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            margin: 0 10px;
            cursor: pointer;
        }

        .btn:hover {
            background-color: grey;
        }

        .content {
            padding: 50px 20px;
            text-align: center;
        }

        .container {
            background: rgba(255, 255, 255, 0.9);
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-top: 30px;
        }

        h1, h2 {
            color: #333;
        }

        .form input {
            display: block;
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 2px solid #ddd;
            border-radius: 5px;
        }

        .form input[type="submit"] {
            background-color: black;
            color: white;
            cursor: pointer;
        }

        .form input[type="submit"]:hover {
            background-color: grey;
        }

        .about-container, .services-container, .contact-container, .submit-container {
            text-align: center;
            background-color: rgba(255, 255, 255, 0.8);
            padding: 50px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-top: 30px;
        }

        .about-container h1, .services-container h1, .contact-container h1, .submit-container h1 {
            color: #333;
        }

        .about-container p, .services-container p, .contact-container p {
            color: #555;
            font-size: 18px;
        }

        .contact-container p {
            margin: 10px 0;
        }

        .contact-container a, .submit-container a {
            color: #0066cc;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <div class="header">
        <div class="left">
            <img src="https://th.bing.com/th/id/OIP.OI14akhcCi07jui5pA1b0gAAAA?w=170&h=183&c=7&r=0&o=5&dpr=1.4&pid=1.7" alt="Logo">
            <h2>Kushagra Fitness</h2>
        </div>

        <div class="middle">
            <ul class="navbar">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>

        <div class="right">
            <button class="btn">Call us now</button>
            <button class="btn">Email us</button>
        </div>
    </div>

    <!-- Home Section -->
    <div id="home" class="content">
        <h1>Join the best GYM in your city</h1>
        <div class="container">
            <h2>Sign Up Now</h2>
            <form action="#submit">
                <div class="form">
                    <input type="text" name="name" placeholder="Enter your name">
                </div>
                <div class="form">
                    <input type="text" name="age" placeholder="Enter your Age">
                </div>
                <div class="form">
                    <input type="text" name="gender" placeholder="Enter your Gender">
                </div>
                <div class="form">
                    <input type="text" name="address" placeholder="Enter your Address">
                </div>
                <div class="form">
                    <input type="submit" value="Submit">
                </div>
            </form>
        </div>
    </div>

    <!-- About Section -->
    <div id="about" class="about-container">
        <h1>About Kushagra Fitness</h1>
        <p>We provide the best fitness services in the city, focusing on strength, wellness, and a healthy lifestyle.</p>
        <p><a href="#home">Back to Home</a></p>
    </div>

    <!-- Services Section -->
    <div id="services" class="services-container">
        <h1>Our Fitness Services</h1>
        <p>We offer a range of services including personal training, group classes, and wellness programs to help you achieve your fitness goals.</p>
        <p><a href="#home">Back to Home</a></p>
    </div>

    <!-- Contact Section -->
    <div id="contact" class="contact-container">
        <h1>Contact Us</h1>
        <p><strong>Phone:</strong> +1 234 567 890</p>
        <p><strong>Email:</strong> support@kushagrafitness.com</p>
        <p><strong>Address:</strong> 123 Fitness Street, Healthy City, Wellness State</p>
        <p><a href="#home">Back to Home</a></p>
    </div>

    <!-- Submit Section (Message) -->
    <div id="submit" class="submit-container">
        <h1>File Could Not Load</h1>
        <p>There was an issue processing your submission. Please try again later.</p>
        <p><a href="#home">Back to Home</a></p>
    </div>

</body>
</html>
