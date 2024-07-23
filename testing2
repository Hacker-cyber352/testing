<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./css/bootstrap.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playwrite+CL:wght@100..400&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <title>Document</title>
    <style>
        /* Reset and global styles */
        
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        *,
        *::after,
        *::before {
            box-sizing: border-box;
            padding: 0;
            margin: 0;
        }
        /* Header styles */
        
        .header {
            background-color: black;
            color: white;
            padding: 8px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        .header h1 {
            margin: 0;
            font-size: 50px;
        }
        
        .header img {
            height: 500px;
            width: auto;
            margin-left: 10px;
        }
        /* Navbar styles */
        
        .navbar {
            position: fixed;
            width: 100%;
            background: #070707;
            color: #fffcfc;
            opacity: 0.85;
            z-index: 100;
            height: 64px;
        }
        
        .navbar-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 100%;
            max-width: 1200px;
            /* Adjust as needed */
            margin: auto;
            /* Center the navbar */
            padding: 0 20px;
        }
        
        .logo {
            font-size: 2.3rem;
            color: darkorange;
        }
        
        .navbar a {
            color: #fffcfc;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease-in-out;
        }
        
        .navbar a:hover {
            color: #d67010;
        }
        
        .menu-items {
            display: flex;
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        
        .menu-items li {
            margin-left: 1.5rem;
            font-size: 1.3rem;
        }
        
        .menu-items li:first-child {
            margin-left: 0;
        }
        
        .menu-items li a {
            color: #fffcfc;
            text-decoration: none;
            transition: color 0.3s ease-in-out;
        }
        
        .menu-items li a:hover {
            color: #d67010;
        }
        /* Responsive Navbar styles */
        
        @media (max-width: 768px) {
            .navbar {
                opacity: 0.95;
            }
            .navbar-container {
                padding: 0 10px;
            }
            .menu-items {
                display: none;
                flex-direction: column;
                position: absolute;
                top: 64px;
                left: 0;
                background-color: #fff;
                width: 100%;
                max-width: 300px;
                box-shadow: 5px 0px 10px 0px #aaa;
                transform: translateX(-100%);
                transition: transform 0.5s ease-in-out;
                z-index: 99;
            }
            .menu-items.active {
                transform: translateX(0);
            }
            .menu-items li {
                margin-left: 0;
                margin-bottom: 1.8rem;
                text-align: center;
                font-size: 1.1rem;
            }
            .logo {
                position: absolute;
                top: 10px;
                left: 15px;
                /* Adjust left position as needed */
                font-size: 2.5rem;
            }
        }
        /* Container and other styles */
        
        .container-1 {
            font-family: "Playwrite CL", cursive;
            font-weight: normal;
            /* Adjust as per your font requirement */
            font-style: normal;
            color: #d67010;
            text-align: center;
            margin-top: 100px;
            /* Adjust spacing */
            padding: 0 20px;
        }
        
        .container-2 h1 {
            text-align: center;
            color: #070707;
            font-family: Arial, sans-serif;
        }
        
        .card-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        
        .card {
            width: 18rem;
            border: 1px solid #ccc;
            border-radius: 10px;
            box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.2);
            text-align: center;
            font-family: Arial, sans-serif;
        }
        
        .card-body {
            padding: 20px;
        }
        
        .card-title {
            font-size: 1.25rem;
            margin-bottom: 0.5rem;
        }
        
        .card-subtitle {
            font-size: 1rem;
            color: #6c757d;
            margin-bottom: 1rem;
        }
        
        .card-text {
            font-size: 0.875rem;
            color: #333;
            margin-bottom: 1rem;
        }
        
        .card-link {
            font-size: 0.875rem;
            color: #007bff;
            text-decoration: none;
            margin-right: 10px;
        }
        
        .card-link:hover {
            text-decoration: underline;
        }
        
        .About {
            font-size: 20px;
            text-align: center;
            margin-top: 20px;
        }
        
        .content {
            font-family: sans-serif;
            font-size: 15px;
            color: black;
            text-align: justify;
            margin: 20px;
        }
        
        .info-row {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }
        
        .left-content {
            font-size: 1.5rem;
            color: #333;
        }
        
        .right-content {
            display: flex;
            align-items: center;
        }
        
        .years-number {
            font-size: 1.5rem;
            color: rgba(255, 188, 2, 0.979);
        }
        
        .years-text {
            font-size: 1.5rem;
            color: #333;
        }
        
        .button-wrapper {
            text-align: center;
            margin-top: 20px;
        }
        
        .button-wrapper button {
            padding: 10px 20px;
            background-color: #f0b208;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 16px;
            border-radius: 4px;
            transition: background-color 0.3s ease;
            font-family: sans-serif;
        }
        
        .button-wrapper button:hover {
            background-color: #eca50c;
        }
        
        .Food.menu {
            font-family: "Playwrite CL", cursive;
            color: #d67010;
            text-align: center;
        }
        
        .container-3,
        .container-4 {
            border-radius: 8px;
            transition: box-shadow 0.3s ease;
            margin-bottom: 20px;
            /* Optional: adds space between containers */
        }
        
        .card:hover {}
        
        .card .card-title {
            color: #333;
            font-size: 1.2rem;
            font-weight: bold;
            display: flex;
        }
        
        .card .card-text {
            color: #666;
            font-size: 1rem;
            line-height: 1.4;
        }
        
        .card-1 {
            background-color: #f8f9fa;
        }
        
        .card-2 {
            background-color: #e9ecef;
        }
        
        .card-3 {
            background-color: #d1ecf1;
        }
        
        .card-4 {
            background-color: #f3f3f4;
        }
        
        .card-5 {
            background-color: #fff;
        }
        
        .card-6 {
            background-color: #f8f9fa;
        }
        
        .video-booking-section {
            background-color: #343a40;
            /* Dark blue background color */
            color: #fff;
            /* Text color for light text on dark background */
        }
        
        .booking-section {
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        .booking-section h2 {
            font-size: 1.8rem;
            color: #333;
            margin-bottom: 20px;
        }
        
        .booking-section form {
            margin-bottom: 0;
        }
        
        .booking-section .form-group {
            margin-bottom: 15px;
        }
        
        .booking-section label {
            font-weight: bold;
            color: #555;
        }
        
        .booking-section input[type="date"],
        .booking-section input[type="time"],
        .booking-section input[type="number"],
        .booking-section button {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
            margin-bottom: 10px;
        }
        
        .booking-section button {
            background-color: #f5bd08;
            color: #fff;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        
        .booking-section button:hover {
            background-color: #da990e;
        }
        
        .container-7 {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
        }
        
        .content {
            flex: 1;
            margin-right: 20px;
        }
        
        .image-container {
            flex: 1;
            display: flex;
            flex-wrap: wrap;
        }
        
        .image-container img {
            width: 50%;
            margin-bottom: 10px;
        }
        
        .card-container {
            display: flex;
            justify-content: space-around;
            align-items: flex-start;
            flex-wrap: wrap;
            margin: 10px;
            max-width: 1200px;
            gap: 20px;
        }
        
        .card-9 {
            flex: 0 0 calc(33.33% - 20px);
            /* Each card takes up 33.33% of the container width minus gaps */
            max-width: calc(33.33% - 20px);
            /* Ensure max-width matches flex basis */
            background-color: #f8f9fa;
            border: 1px solid #ccc;
            border-radius: 8px;
            margin: 10px;
            text-align: center;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        .card-content {
            margin-top: 10px;
        }
        
        .card-content h2 {
            font-size: 1.5rem;
        }
        
        .card-content p {
            font-size: 1rem;
            /* Adjust paragraph size */
            color: #666;
            /* Optional text color */
        }
        
        .Team-members {
            color: darkorange;
            text-align: center;
            font-family: 'Playwrite CL', cursive;
        }
        
        .section-footer {
            background-color: #f5f5f5;
            padding: 20px;
            display: flex;
            justify-content: space-around;
            align-items: center;
            /* Center items vertically */
            flex-wrap: wrap;
            /* Wrap items if they exceed the width */
        }
        
        .section-footer h4 {
            margin-bottom: 10px;
        }
        
        .footer-contact,
        .footer-opening,
        .footer-newsletter,
        .footer-legal {
            max-width: 300px;
            margin-bottom: 20px;
        }
        
        .footer-contact a {
            text-decoration: none;
            color: #333;
        }
        
        .footer-newsletter form {
            display: flex;
        }
        
        .footer-newsletter input[type="email"] {
            flex: 1;
            padding: 8px;
            margin-right: 8px;
        }
        
        .footer-newsletter button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 8px 12px;
            cursor: pointer;
        }
        
        .footer-legal p {
            font-size: 12px;
            color: #666;
            margin: 5px 0;
        }
        
        .container-5 {
            height: 400%;
            width: 310%;
            background-color: #070707;
            font-family: "Playwrite CL", cursive;
            font-weight: normal;
            /* Adjust as per your font requirement */
            font-style: normal;
            color: #d67010;
            text-align: center;
            margin-top: 100px;
            /* Adjust spacing */
            padding: 0 20px;
        }
    </style>
</head>

<body>
    <nav class="navbar">
        <div class="navbar-container container">
            <h1 class="logo">Resturants-2024</h1>

            <label for="navbar-toggle" class="hamburger-lines">
                <span class="line line1"></span>
                <span class="line line2"></span>
                <span class="line line3"></span>
            </label>
            <ul class="menu-items">
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Category</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Testimonial</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </div>
    </nav>

    <header class="header">
        <h1>Enjoy Our Delicious Meal</h1>
        <img src="./assest/mahyar-motebassem-pGA4zHvpo5E-unsplash-removebg-preview.png" alt="Delicious Meal Image">
    </header>

    <div class="container-1">
        <h4>------Our Services----</h4>

        <div class="card-container">
            <div class="card">
                <div class="card-body">
                    <h5 class="card-title">Card Title 1</h5>
                    <h6 class="card-subtitle mb-2 text-body-secondary">Card Subtitle 1</h6>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    <a href="#" class="card-link">Card Link 1</a>
                    <a href="#" class="card-link">Another Link 1</a>
                </div>
            </div>

            <div class="card">
                <div class="card-body">
                    <h5 class="card-title">Card Title 2</h5>
                    <h6 class="card-subtitle mb-2 text-body-secondary">Card Subtitle 2</h6>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    <a href="#" class="card-link">Card Link 2</a>
                    <a href="#" class="card-link">Another Link 2</a>
                </div>
            </div>

            <div class="card">
                <div class="card-body">
                    <h5 class="card-title">Card Title 3</h5>
                    <h6 class="card-subtitle mb-2 text-body-secondary">Card Subtitle 3</h6>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    <a href="#" class="card-link">Card Link 3</a>
                    <a href="#" class="card-link">Another Link 3</a>
                </div>
            </div>
        </div>

        <div class="About">
            <h5>About Us_______</h5>
            <h1>
                <marquee>Welcome to Restoran </marquee>
            </h1>
        </div>
        <div class="container-7">
            <div class="content">
                <p>
                    Restaurants are vibrant hubs where culinary artistry meets social interaction, offering a diverse array of dining experiences. From cozy cafes to upscale fine dining establishments, each restaurant crafts its unique ambiance and menu to cater to diverse
                    tastes and preferences. These venues not only serve delicious food but also foster community gatherings, business meetings, and celebrations.
                </p>
                <p>
                    Restaurants often showcase cultural diversity through their cuisine, providing patrons with a global culinary journey. They are spaces where chefs innovate with ingredients, techniques, and presentation, constantly evolving to meet changing food trends
                    and dietary preferences. Ultimately, restaurants embody the intersection of gastronomy, hospitality, and culture, enriching our dining experiences and memories.
                </p>
            </div>

            <div class="image-container">
                <img src="./assest/alexander-kovacs-TivEEYzzhik-unsplash.jpg" alt="Restaurant Image 1">
                <img src="./assest/daniel-bradley-y_WDEY9e6mA-unsplash.jpg" alt="Restaurant Image 2">
                <img src="./assest/rohan-g--mwNJswDlXE-unsplash.jpg" alt="Restaurant Image 3">
                <img src="./assest/alexander-kovacs-TivEEYzzhik-unsplash.jpg" alt="Restaurant Image 4">
            </div>
        </div>

        <div class="info-row">
            <div class="left-content">
                <strong><span class="highlight-yellow">50</span></strong> popular MASTER CHEFS
            </div>
            <div class="right-content">
                <div class="years-number"><strong>15</strong></div>
                <div class="years-text">years of experience</div>
            </div>
        </div>


        <div class="button-wrapper">
            <button>Read more</button>
        </div>
    </div>
    </div>
    <br>
    <div class="Food menu">
        <h5>
            _____Food Menu_______
        </h5>
    </div>
    <h1 style="text-align: center;">Most popular item</h1>
    <div class="container-3">
        <div class="row">
            <div class="col-sm-4 mb-3 mb-sm-0">
                <div class="card card-1">
                    <div class="card-body">
                        <h5 class="card-title">Special title treatment</h5>
                        <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                    </div>
                </div>
            </div>
            <div class="col-sm-4 mb-3 mb-sm-0">
                <div class="card card-2">
                    <div class="card-body">
                        <h5 class="card-title">Special title treatment</h5>
                        <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                    </div>
                </div>
            </div>
            <div class="col-sm-4">
                <div class="card card-3">
                    <div class="card-body">
                        <h5 class="card-title">Special title treatment</h5>
                        <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="container-4">
        <div class="row">
            <div class="col-sm-4 mb-3 mb-sm-0">
                <div class="card card-4">
                    <div class="card-body">
                        <h5 class="card-title">Special title treatment</h5>
                        <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                    </div>
                </div>
            </div>
            <div class="col-sm-4 mb-3 mb-sm-0">
                <div class="card card-5">
                    <div class="card-body">
                        <h5 class="card-title">Special title treatment</h5>
                        <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                    </div>
                </div>
            </div>
            <div class="col-sm-4">
                <div class="card card-6">
                    <div class="card-body">
                        <h5 class="card-title">Special title treatment</h5>
                        <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="video-booking-section bg-dark py-5">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 mb-4">
                    <div class="embed-responsive embed-responsive-16by9">
                        <iframe class="embed-responsive-item" src="https://youtu.be/FgSArK9hazA" allowfullscreen></iframe>
                    </div>
                </div>

                <div class="col-lg-6 mb-4">
                    <div class="booking-section bg-white p-4">
                        <h2 class="mb-4">Book A Table Online</h2>
                        <form action="#" method="POST">
                            <div class="form-group">
                                <label for="date">Select Date:</label>
                                <input type="date" id="date" name="date" class="form-control">
                            </div>
                            <div class="form-group">
                                <label for="time">Select Time:</label>
                                <input type="time" id="time" name="time" class="form-control">
                            </div>
                            <div class="form-group">
                                <label for="persons">Number of Persons:</label>
                                <input type="number" id="persons" name="persons" class="form-control" min="1">
                            </div>
                            <button type="submit" class="btn btn-primary btn-block">Book Now</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <br>
    <div class="Team-members">
        <h4>------Team Members------</h4>
    </div>
    <div class="Our master chefs">
        <h1 style="text-align: center;">Our Master Chefs</h1>
    </div>
    <div class="card-container ">
        <div class="card ">
            <div class="card-body ">
                <h5 class="card-title ">Card Title 1</h5>
                <h6 class="card-subtitle mb-2 text-body-secondary ">Card Subtitle 1</h6>
                <p class="card-text ">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                <a href="# " class="card-link ">Card Link 1</a>
                <a href="# " class="card-link ">Another Link 1</a>
            </div>
        </div>
        <div class="card ">
            <div class="card-body ">
                <h5 class="card-title ">Card Title 2</h5>
                <h6 class="card-subtitle mb-2 text-body-secondary ">Card Subtitle 2</h6>
                <p class="card-text ">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                <a href="# " class="card-link ">Card Link 2</a>
                <a href="# " class="card-link ">Another Link 2</a>
            </div>
        </div>

        <div class="card ">
            <div class="card-body ">
                <h5 class="card-title ">Card Title 3</h5>
                <h6 class="card-subtitle mb-2 text-body-secondary ">Card Subtitle 3</h6>
                <p class="card-text ">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                <a href="# " class="card-link ">Card Link 3</a>
                <a href="# " class="card-link ">Another Link 3</a>
            </div>
        </div>
    </div>
    <div class="Team-members">
        <h4>------Testimonial------</h4>
    </div>
    <div class="Our master chefs">
        <h1 style="text-align: center;">Our Clients says</h1>
    </div>
    <div class="container-fluid">
        <div class="row">
            <div class="col">
                <div class="row row-cols-1 row-cols-md-3 g-4">
                    <div class="col">
                        <div class="card">
                            <img src="..." class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <img src="..." class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <img src="..." class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <img src="..." class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>

                            </div>

                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <img src="./assest/alexander-kovacs-TivEEYzzhik-unsplash.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>

                            </div>

                        </div>

                    </div>
                    <div class="col">
                        <div class="card">
                            <img src="..." class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>

                            </div>

                        </div>

                    </div>

                    <!-- <footer>
                    <footer class="section-footer">
                        <div class="footer-contact">
                            <h4>Contact Us:</h4>
                            <p>Phone: <a href="tel:+1234567890">+123 456 7890</a></p>
                            <p>Email: <a href="mailto:contact@example.com">contact@example.com</a></p>
                            <p>Address: 123 Main St, City, Country</p>
                        </div>
                        <div class="footer-opening">
                            <h4>Welcome to Our Website!</h4>
                            <p>Explore our services designed to exceed your expectations.</p>
                        </div>
                        <div class="footer-newsletter">
                            <h4>Subscribe to Our Newsletter:</h4>
                            <form action="#" method="post">
                                <input type="email" name="email" placeholder="Enter your email" required>
                                <button type="submit">Subscribe</button>
                                <div class="footer-legal">
                                    <p>&copy; 2024 Your Company Name. All Rights Reserved.</p>
                                    <p>Terms of Service | Privacy Policy</p>
                                </div> -->

                    <!-- </footer> -->
                    <footer>
                        <div class="container-5">
                            <div class="container-fluid">
                                <div class="row">
                                    <div class="col-md-3">
                                        <p>Company--------</p>
                                        <div class="container-9">
                                            <p> About us</p>
                                            <p>Contact us</p>
                                            <p>Reservation</p>
                                            <p>privcacy policy</p>
                                            <p></p>
                                        </div>
                                    </div>
                                </div>
                    </footer>






                    <script src="./js/bootstrap.min.js "></script>
</body>

</html>
