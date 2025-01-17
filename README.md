
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forklore Restaurant</title>
    <link rel="icon" href="/pictures/logo3.jpeg" type="image/x-icon" >
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="project_homepage.css">
    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>
    <header class="header">
        <a href="#foodCarousel" ><h1>FORKLORE</h1></a>
        <nav class="navbar navbar-expand-lg navbar-dark navbar-custom">
            <div class="container-fluid">
                <!--<a class="navbar-brand " href="#foodCarousel">FORKLORE</a> -->
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link active" href="#foodCarousel">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#menu-section">Menu</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="about.html">About Us</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#Contact">Contact</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#gallery-section">Gallery</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="about.html#review-section">Reviews</a>
                        </li>
                    </ul>
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item">
                            <a class="nav-link" href="#"><i class="fas fa-user-plus"></i></a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="tel:+123456789"><i class="fas fa-phone-alt"></i></a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero-section">
        <div id="foodCarousel" class="carousel slide" data-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="/pictures/Untitled design.png" class="d-block w-100" alt="Desi Food">
                </div>
                <div class="carousel-item">
                    <img src="/pictures/www.folkloree.com.png" class="d-block w-100" alt="Fast Food">
                </div>
                <div class="carousel-item">
                    <img src="/pictures/juice.png" class="d-block w-100" alt="Juices">
                </div>
            </div>
            <a class="carousel-control-prev" href="#foodCarousel" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#foodCarousel" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
    </section>

    <!-- Mid Section -->
    <section class="mid-section text-center">
        <div class="container">
            <h2 class="section-title">Experience the Taste of Tradition</h2>
            <p class="section-description">At Forklore, we bring you the finest and most exquisite cuisines from around the world. Our chefs are passionate about food and create dishes that are not only flavorful but also healthy.</p>
            <a href="#menu-section" class="btn btn-primary">Explore Our Menu</a>
        </div>
    </section>

<!-- Menu Section -->
<section id="menu-section" class="menu-section text-center">
    <div class="container">
        <h2 class="section-title">Our Menu</h2>
        <p class="section-description">Discover our delicious selection of meals, crafted to perfection.</p>

        <!-- Image Grid Section -->
        <div class="menu-gallery">
            <figure class="row">
                <div class="col-md-3 col-sm-6">
                    <img src="/pictures/Forklore.png" class="img-fluid" alt="Menu Item 1">
                </div>
                <div class="col-md-3 col-sm-6">
                    <img src="/pictures/Forklore1.png" class="img-fluid" alt="Menu Item 2">
                </div>
                <div class="col-md-3 col-sm-6">
                    <img src="/pictures/Forklore2.png" class="img-fluid" alt="Menu Item 3">
                </div>
                <div class="col-md-3 col-sm-6">
                    <img src="/pictures/Forklore3.png" class="img-fluid" alt="Menu Item 4">
                </div>
            </figure>
        </div>

        <!-- Existing Menu Items (Optional) -->
        <div class="row">
            <div class="col-md-4">
                <div class="menu-item">
                    <h3>Starter</h3>
                    <p>Fish Crackers - $4</p>
                    <p>Garlic Bread - $5</p>
                    <p>Soup of the Day - $5.5</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="menu-item">
                    <h3>Main Course</h3>
                    <p>Grilled Chicken - $18</p>
                    <p>Beef Steak - $22</p>
                    <p>Alfredo Pasta - $16</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="menu-item">
                    <h3>Desserts</h3>
                    <p>Chocolate Cake - $9</p>
                    <p>Donuts - $8</p>
                    <p>Ice Cream Sundae - $7</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Gallery Section -->
<section id="gallery-section" class="gallery-section text-center">
    <div class="container">
        <h2 class="section-title">Our Gallery</h2>
        <p class="section-description">A glimpse of our delicious meals and inviting ambiance.</p>
        <div class="row">
            <div class="col-md-4 col-sm-6">
                <img src="/pictures/BBQ.jpeg" class="img-fluid" alt="Dish 1">
            </div>
            <div class="col-md-4 col-sm-6">
                <img src="/pictures/pasta.jpeg" class="img-fluid" alt="Dish 2">
            </div>
            <div class="col-md-4 col-sm-6">
                <img src="/pictures/dish.jpeg" class="img-fluid" alt="Dish 3">
            </div>
            <div class="col-md-4 col-sm-6">
                <img src="/pictures/gallery.png" class="img-fluid" alt="Dish 4">
            </div>
            <div class="col-md-4 col-sm-6">
                <img src="/pictures/gallery1.png" class="img-fluid" alt="Restaurant Interior 1">
            </div>
            <div class="col-md-4 col-sm-6">
                <img src="/pictures/gallery2.png" class="img-fluid" alt="Restaurant Interior 2">
            </div>
        </div>
    </div>
</section>


<footer class="footer bg-dark text-light">
    <div class="container">
        <div class="row">
            <!-- Contact and Links -->
            <div id="Contact" class="col-md-6">
                <h4>Contact Us</h4>
                <p>If you have any questions or would like to make a reservation, feel free to reach out!</p>
            </div>

            <!-- Social Media and Subscription -->
            <div class="col-md-6 text-md-right">
                <h4>Follow Us</h4>
                <div class="social-links">
                    <a href="https://instagram.com" class="text-light mr-3"><i class="fab fa-instagram"></i></a>
                    <a href="https://facebook.com" class="text-light mr-3"><i class="fab fa-facebook"></i></a>
                </div>
                <div class="newsletter">
                    <h4>Subscribe to our Newsletter</h4>
                    <form action="#" method="POST" class="subscribe-form">
                        <input type="email" name="email" placeholder="Enter your email" required>
                        <button type="submit" class="btn btn-primary">Subscribe</button>
                    </form>
                </div>
            </div>
        </div>
    </div>
</footer>

 <!-- Bootstrap JavaScript and dependencies -->
 <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
 <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@1.16.1/dist/umd/popper.min.js"></script>
 <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</html>
