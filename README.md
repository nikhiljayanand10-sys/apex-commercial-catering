<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Apex Commercial Catering | Kodambakkam, Chennai</title>

    <meta name="description"
          content="Apex Commercial Catering provides professional catering services in Kodambakkam, Chennai for corporate events, weddings, parties and special occasions.">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.6;
            background: #fffaf3;
            color: #333;
        }

        /* NAVBAR */
        header {
            background: #ffffff;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.08);
        }

        nav {
            max-width: 1200px;
            margin: auto;
            padding: 15px 25px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #8b4513;
        }

        .logo span {
            display: block;
            font-size: 12px;
            color: #777;
            letter-spacing: 2px;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 22px;
            align-items: center;
        }

        .nav-links a {
            text-decoration: none;
            color: #333;
            font-weight: 600;
        }

        .nav-links a:hover {
            color: #c47a25;
        }

        .nav-button {
            background: #8b4513;
            color: white !important;
            padding: 10px 18px;
            border-radius: 25px;
        }

        /* HERO */
        .hero {
            min-height: 90vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 40px 20px;

            background:
                linear-gradient(rgba(0,0,0,0.55), rgba(0,0,0,0.55)),
                url("https://images.unsplash.com/photo-1515003197210-e0cd71810b5f?auto=format&fit=crop&w=1600&q=80");

            background-size: cover;
            background-position: center;
            color: white;
        }

        .hero-content {
            max-width: 800px;
        }

        .hero h1 {
            font-size: 55px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 21px;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            padding: 13px 25px;
            border-radius: 30px;
            text-decoration: none;
            margin: 5px;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn-primary {
            background: #c47a25;
            color: white;
        }

        .btn-secondary {
            background: white;
            color: #8b4513;
        }

        .btn:hover {
            transform: translateY(-3px);
            opacity: 0.9;
        }

        /* GENERAL */
        section {
            padding: 80px 20px;
        }

        .container {
            max-width: 1150px;
            margin: auto;
        }

        .section-title {
            text-align: center;
            margin-bottom: 45px;
        }

        .section-title h2 {
            font-size: 36px;
            color: #8b4513;
            margin-bottom: 10px;
        }

        .section-title p {
            color: #666;
        }

        /* FEATURES */
        .features {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
        }

        .feature-card {
            background: white;
            padding: 30px 20px;
            text-align: center;
            border-radius: 12px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
        }

        .feature-icon {
            font-size: 40px;
            margin-bottom: 15px;
        }

        .feature-card h3 {
            color: #8b4513;
            margin-bottom: 10px;
        }

        /* ABOUT */
        .about {
            background: #f7eee2;
        }

        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 50px;
            align-items: center;
        }

        .about-image img {
            width: 100%;
            border-radius: 15px;
        }

        .about-text h2 {
            color: #8b4513;
            font-size: 38px;
            margin-bottom: 20px;
        }

        .about-text p {
            margin-bottom: 15px;
            color: #555;
        }

        /* SERVICES */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
        }

        .service-card {
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
            transition: 0.3s;
        }

        .service-card:hover {
            transform: translateY(-5px);
        }

        .service-card h3 {
            color: #8b4513;
            margin-bottom: 10px;
        }

        .service-card p {
            color: #666;
            font-size: 14px;
            margin-bottom: 15px;
        }

        /* MENU */
        .menu-section {
            background: #f7eee2;
        }

        .menu-category {
            margin-bottom: 45px;
        }

        .menu-category h3 {
            font-size: 25px;
            color: #8b4513;
            margin-bottom: 20px;
            border-bottom: 2px solid #d5a05b;
            padding-bottom: 8px;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 18px;
        }

        .menu-item {
            background: white;
            padding: 18px;
            border-radius: 10px;
            display: flex;
            justify-content: space-between;
            box-shadow: 0 3px 12px rgba(0,0,0,0.06);
        }

        .menu-item span:first-child {
            font-weight: 600;
        }

        .menu-item span:last-child {
            color: #c47a25;
        }

        .menu-note {
            text-align: center;
            margin-top: 30px;
            font-style: italic;
            color: #666;
        }

        /* GALLERY */
        .gallery {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
        }

        .gallery img {
            width: 100%;
            height: 240px;
            object-fit: cover;
            border-radius: 12px;
            transition: 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.03);
        }

        /* BOOKING */
        .booking {
            background: #f7eee2;
        }

        .booking-container {
            max-width: 850px;
            margin: auto;
            background: white;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 5px 25px rgba(0,0,0,0.08);
        }

        .form-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }

        .form-group {
            display: flex;
            flex-direction: column;
        }

        .form-group.full {
            grid-column: 1 / -1;
        }

        label {
            font-weight: bold;
            margin-bottom: 7px;
            color: #555;
        }

        input,
        select,
        textarea {
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 7px;
            font-size: 15px;
            outline: none;
        }

        input:focus,
        select:focus,
        textarea:focus {
            border-color: #c47a25;
        }

        textarea {
            min-height: 120px;
            resize: vertical;
        }

        .submit-btn {
            width: 100%;
            border: none;
            background: #8b4513;
            color: white;
            padding: 15px;
            border-radius: 30px;
            font-size: 17px;
            font-weight: bold;
            cursor: pointer;
            margin-top: 20px;
        }

        .submit-btn:hover {
            background: #c47a25;
        }

        #successMessage {
            display: none;
            margin-top: 20px;
            padding: 15px;
            background: #e7f6e7;
            color: #286628;
            border-radius: 8px;
            text-align: center;
        }

        /* CONTACT */
        .contact {
            text-align: center;
        }

        .contact-box {
            max-width: 700px;
            margin: auto;
            background: #8b4513;
            color: white;
            padding: 40px;
            border-radius: 15px;
        }

        .contact-box h2 {
            font-size: 32px;
            margin-bottom: 20px;
        }

        .contact-box p {
            margin: 8px;
        }

        .contact-email {
            color: white;
            font-weight: bold;
            text-decoration: none;
        }

        .map {
            margin-top: 25px;
            width: 100%;
            height: 280px;
            border: 0;
            border-radius: 12px;
        }

        /* FOOTER */
        footer {
            background: #2d1b10;
            color: white;
            text-align: center;
            padding: 30px 20px;
        }

        footer h3 {
            margin-bottom: 10px;
        }

        footer a {
            color: #f0c078;
            text-decoration: none;
        }

        /* MOBILE */
        @media (max-width: 900px) {
            .features,
            .services-grid {
                grid-template-columns: repeat(2, 1fr);
            }

            .menu-grid {
                grid-template-columns: repeat(2, 1fr);
            }

            .hero h1 {
                font-size: 42px;
            }
        }

        @media (max-width: 650px) {
            .nav-links {
                display: none;
            }

            .features,
            .services-grid,
            .menu-grid,
            .gallery,
            .about-content,
            .form-grid {
                grid-template-columns: 1fr;
            }

            .hero h1 {
                font-size: 35px;
            }

            .hero p {
                font-size: 17px;
            }

            .booking-container {
                padding: 25px;
            }

            .form-group.full {
                grid-column: auto;
            }
        }
    </style>
</head>

<body>

<!-- NAVIGATION -->
<header>
    <nav>
        <div class="logo">
            Apex Commercial Catering
            <span>KODAMBAKKAM • CHENNAI</span>
        </div>

        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#menu">Menu</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li>
                <a href="#booking" class="nav-button">
                    Book an Appointment
                </a>
            </li>
        </ul>
    </nav>
</header>


<!-- HERO -->
<section class="hero" id="home">
    <div class="hero-content">

        <h1>Exceptional Catering for Every Occasion</h1>

        <p>
            Quality food, professional service and memorable experiences
            in Kodambakkam, Chennai.
        </p>

        <a href="#menu" class="btn btn-primary">
            View Menu
        </a>

        <a href="#booking" class="btn btn-secondary">
            Book an Appointment
        </a>

    </div>
</section>


<!-- FEATURES -->
<section>
    <div class="container">

        <div class="section-title">
            <h2>Why Choose Apex?</h2>
            <p>Professional catering designed around your event.</p>
        </div>

        <div class="features">

            <div class="feature-card">
                <div class="feature-icon">🍽️</div>
                <h3>Quality Food</h3>
                <p>Fresh and carefully prepared food for every occasion.</p>
            </div>

            <div class="feature-card">
                <div class="feature-icon">👨‍🍳</div>
                <h3>Professional Service</h3>
                <p>Reliable catering support from planning to serving.</p>
            </div>

            <div class="feature-card">
                <div class="feature-icon">📋</div>
                <h3>Customised Menus</h3>
                <p>Flexible menu options based on your event requirements.</p>
            </div>

            <div class="feature-card">
                <div class="feature-icon">⭐</div>
                <h3>Customer Focus</h3>
                <p>We focus on creating a smooth and memorable experience.</p>
            </div>

        </div>
    </div>
</section>


<!-- ABOUT -->
<section class="about" id="about">

    <div class="container">

        <div class="about-content">

            <div class="about-image">
                <img
                    src="https://images.unsplash.com/photo-1555244162-803834f70033?auto=format&fit=crop&w=900&q=80"
                    alt="Professional catering buffet">
            </div>

            <div class="about-text">

                <h2>About Apex Commercial Catering</h2>

                <p>
                    Apex Commercial Catering is a professional catering
                    service based in Kodambakkam, Chennai.
                </p>

                <p>
                    We provide catering solutions for corporate events,
                    weddings, parties, meetings, celebrations and bulk
                    food requirements.
                </p>

                <p>
                    Our focus is on quality food, hygiene, professional
                    service and customer satisfaction.
                </p>

                <a href="#booking" class="btn btn-primary">
                    Plan Your Event
                </a>

            </div>

        </div>

    </div>

</section>


<!-- SERVICES -->
<section id="services">

    <div class="container">

        <div class="section-title">
            <h2>Our Catering Services</h2>
            <p>Solutions for different events and business requirements.</p>
        </div>

        <div class="services-grid">

            <div class="service-card">
                <h3>Corporate Catering</h3>
                <p>
                    Professional food services for corporate offices,
                    business events and company functions.
                </p>
                <a href="#booking">Enquire Now →</a>
            </div>

            <div class="service-card">
                <h3>Office Lunch</h3>
                <p>
                    Convenient catering options for office lunches
                    and employee meals.
                </p>
                <a href="#booking">Enquire Now →</a>
            </div>

            <div class="service-card">
                <h3>Wedding Catering</h3>
                <p>
                    Customised food and catering support for weddings
                    and receptions.
                </p>
                <a href="#booking">Enquire Now →</a>
            </div>

            <div class="service-card">
                <h3>Birthday Events</h3>
                <p>
                    Delicious food options for birthday celebrations
                    and private parties.
                </p>
                <a href="#booking">Enquire Now →</a>
            </div>

            <div class="service-card">
                <h3>Party Catering</h3>
                <p>
                    Flexible catering packages for private and
                    social gatherings.
                </p>
                <a href="#booking">Enquire Now →</a>
            </div>

            <div class="service-card">
                <h3>Bulk Food Orders</h3>
                <p>
                    Catering solutions for large-volume food
                    requirements.
                </p>
                <a href="#booking">Enquire Now →</a>
            </div>

            <div class="service-card">
                <h3>Meetings & Conferences</h3>
                <p>
                    Food and beverage arrangements for meetings,
                    seminars and conferences.
                </p>
                <a href="#booking">Enquire Now →</a>
            </div>

            <div class="service-card">
                <h3>Custom Packages</h3>
                <p>
                    Build a catering package based on your event,
                    guest count and menu preferences.
                </p>
                <a href="#booking">Enquire Now →</a>
            </div>

        </div>

    </div>

</section>


<!-- MENU -->
<section class="menu-section" id="menu">

    <div class="container">

        <div class="section-title">
            <h2>Our Menu</h2>
            <p>Choose from a variety of vegetarian and non-vegetarian options.</p>
        </div>


        <!-- STARTERS -->
        <div class="menu-category">

            <h3>🥗 Starters</h3>

            <div class="menu-grid">

                <div class="menu-item">
                    <span>Vegetable Cutlet</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Gobi 65</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Paneer Tikka</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Chicken 65</span>
                    <span>●</span>
                </div>

            </div>
        </div>


        <!-- VEG -->
        <div class="menu-category">

            <h3>🍛 Main Course – Vegetarian</h3>

            <div class="menu-grid">

                <div class="menu-item">
                    <span>Vegetable Biryani</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Paneer Butter Masala</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Mixed Vegetable Curry</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Dal Tadka</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Steamed Rice</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Chapati / Naan</span>
                    <span>●</span>
                </div>

            </div>
        </div>


        <!-- NON VEG -->
        <div class="menu-category">

            <h3>🍗 Main Course – Non-Vegetarian</h3>

            <div class="menu-grid">

                <div class="menu-item">
                    <span>Chicken Biryani</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Chicken Curry</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Chicken Tikka Masala</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Mutton Curry</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Egg Curry</span>
                    <span>●</span>
                </div>

            </div>
        </div>


        <!-- SOUTH INDIAN -->
        <div class="menu-category">

            <h3>🥘 South Indian</h3>

            <div class="menu-grid">

                <div class="menu-item">
                    <span>Idli</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Vada</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Sambar</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Pongal</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Lemon Rice</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Curd Rice</span>
                    <span>●</span>
                </div>

            </div>
        </div>


        <!-- DESSERT -->
        <div class="menu-category">

            <h3>🍰 Desserts</h3>

            <div class="menu-grid">

                <div class="menu-item">
                    <span>Gulab Jamun</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Payasam</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Fruit Custard</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Ice Cream</span>
                    <span>●</span>
                </div>

            </div>
        </div>


        <!-- BEVERAGES -->
        <div class="menu-category">

            <h3>☕ Beverages</h3>

            <div class="menu-grid">

                <div class="menu-item">
                    <span>Fresh Lime Juice</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Fresh Fruit Juice</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Filter Coffee</span>
                    <span>●</span>
                </div>

                <div class="menu-item">
                    <span>Tea</span>
                    <span>●</span>
                </div>

            </div>
        </div>

        <p class="menu-note">
            Menu items can be customised based on event requirements
            and customer preferences.
        </p>

    </div>

</section>


<!-- GALLERY -->
<section id="gallery">

    <div class="container">

        <div class="section-title">
            <h2>Gallery</h2>
            <p>A glimpse of catering and food presentation.</p>
        </div>

        <div class="gallery">

            <img src="https://images.unsplash.com/photo-1555244162-803834f70033?auto=format&fit=crop&w=700&q=80"
                 alt="Catering buffet">

            <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=700&q=80"
                 alt="Indian food">

            <img src="https://images.unsplash.com/photo-1515003197210-e0cd71810b5f?auto=format&fit=crop&w=700&q=80"
                 alt="Catering food">

            <img src="https://images.unsplash.com/photo-1547592180-85f173990554?auto=format&fit=crop&w=700&q=80"
                 alt="Healthy catering">

            <img src="https://images.unsplash.com/photo-1563379926898-05f4575a45d8?auto=format&fit=crop&w=700&q=80"
                 alt="Pasta dish">

            <img src="https://images.unsplash.com/photo-1559339352-11d035aa65de?auto=format&fit=crop&w=700&q=80"
                 alt="Restaurant food">

        </div>

    </div>

</section>


<!-- BOOKING -->
<section class="booking" id="booking">

    <div class="container">

        <div class="section-title">
            <h2>Book an Appointment</h2>
            <p>
                Tell us about your event and catering requirements.
            </p>
        </div>

        <div class="booking-container">

            <form id="bookingForm">

                <div class="form-grid">

                    <div class="form-group">
                        <label for="name">Full Name *</label>
                        <input
                            type="text"
                            id="name"
                            required
                            placeholder="Enter your full name">
                    </div>

                    <div class="form-group">
                        <label for="email">Email Address *</label>
                        <input
                            type="email"
                            id="email"
                            required
                            placeholder="Enter your email">
                    </div>

                    <div class="form-group">
                        <label for="date">Event Date *</label>
                        <input
                            type="date"
                            id="date"
                            required>
                    </div>

                    <div class="form-group">
                        <label for="time">Preferred Appointment Time *</label>
                        <input
                            type="time"
                            id="time"
                            required>
                    </div>

                    <div class="form-group">
                        <label for="event">Event Type *</label>

                        <select id="event" required>

                            <option value="">
                                Select Event Type
                            </option>

                            <option>Corporate Event</option>
                            <option>Wedding</option>
                            <option>Birthday</option>
                            <option>Private Party</option>
                            <option>Meeting / Conference</option>
                            <option>Bulk Food Order</option>
                            <option>Other</option>

                        </select>
                    </div>

                    <div class="form-group">
                        <label for="guests">Number of Guests *</label>

                        <input
                            type="number"
                            id="guests"
                            min="1"
                            required
                            placeholder="Example: 100">
                    </div>

                    <div class="form-group full">

                        <label for="requirements">
                            Catering Requirements
                        </label>

                        <textarea
                            id="requirements"
                            placeholder="Tell us about your menu preferences or catering requirements..."></textarea>

                    </div>

                    <div class="form-group full">

                        <label for="message">
                            Additional Message
                        </label>

                        <textarea
                            id="message"
                            placeholder="Any additional information..."></textarea>

                    </div>

                </div>

                <button type="submit" class="submit-btn">
                    Book Appointment
                </button>

            </form>

            <div id="successMessage">
                <strong>Thank you!</strong><br>
                Your appointment request has been received.
                Our team will get back to you through email.
            </div>

        </div>

    </div>

</section>


<!-- CONTACT -->
<section class="contact" id="contact">

    <div class="container">

        <div class="section-title">
            <h2>Contact Apex Commercial Catering</h2>
        </div>

        <div class="contact-box">

            <h2>Apex Commercial Catering</h2>

            <p>
                📍 Kodambakkam, Chennai, Tamil Nadu, India
            </p>

            <p>
                ✉️
                <a
                    class="contact-email"
                    href="mailto:karshima@apexcatering.com">
                    karshima@apexcatering.com
                </a>
            </p>

            <iframe
                class="map"
                src="https://www.google.com/maps?q=Kodambakkam,Chennai&output=embed"
                loading="lazy">
            </iframe>

        </div>

    </div>

</section>


<!-- FOOTER -->
<footer>

    <h3>Apex Commercial Catering</h3>

    <p>
        Kodambakkam, Chennai, Tamil Nadu
    </p>

    <p>
        <a href="mailto:karshima@apexcatering.com">
            karshima@apexcatering.com
        </a>
    </p>

    <br>

    <p>
        © 2026 Apex Commercial Catering. All Rights Reserved.
    </p>

</footer>


<!-- JAVASCRIPT -->
<script>

    const bookingForm = document.getElementById("bookingForm");
    const successMessage = document.getElementById("successMessage");

    bookingForm.addEventListener("submit", function(event) {

        event.preventDefault();

        // Show confirmation
        successMessage.style.display = "block";

        // Clear the form
        bookingForm.reset();

        // Scroll to confirmation
        successMessage.scrollIntoView({
            behavior: "smooth",
            block: "center"
        });

    });

</script>

</body>
</html>
