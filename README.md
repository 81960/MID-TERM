<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Cake Delights</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Your existing CSS styles */
    </style>
</head>
<body>
    <header>
        <div class="container">
            <img src="p.webp"Cake Delights Logo">
            <h1> cakes</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h2>Welcome to Cake Delights</h2>
            <p>Indulge in the sweetness of life with our delightful cakes and desserts. At Cake Delights, we believe that every moment is worth celebrating, and what better way to celebrate than with a slice of our heavenly creations?</p>
            <p>Our journey began with a simple mission: to spread joy and happiness through our delicious treats. Over the years, we've perfected our recipes, ensuring that each cake is a masterpiece of flavor and texture. From classic favorites like chocolate and vanilla to innovative creations like mango passionfruit and salted caramel, our cakes are sure to tantalize your taste buds and leave you craving for more.</p>
            <a href="#" class="btn">Order Now</a>
        </div>
    </section>

    <section class="featured">
        <div class="container">
            <h2>Featured Cakes</h2>
            <div class="cake-gallery">
                <div class="cake-item">
                    <img src="6.jpg" alt="Cake 1">
                    <h3>Chocolate Fudge Cake</h3>
                    <p>Rich and decadent, perfect for chocolate lovers!</p>
                </div>
                <div class="cake-item">
                    <img src="7.jpg" alt="Cake 2">
                    <h3>Vanilla Berry Cake</h3>
                    <p>Light and refreshing, with a burst of berry flavor.</p>
                </div>
                <div class="cake-item">
                    <img src="9.jpg" alt="Cake 3">
                    <h3>Red Velvet Delight</h3>
                    <p>A classic favorite with its vibrant color and creamy texture.</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Cake Delights. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Cake Delights</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        .image-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }
        .image-container img {
            width: calc(50% - 20px);
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }
        .image-container img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <header>
        
        <div class="container">
            <h1>About Cake Delights</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Welcome to Cake Delights! We are a family-owned bakery dedicated to crafting delicious cakes and desserts for every occasion. With a passion for baking and a commitment to quality, we take pride in creating memorable experiences for our customers.</p>
            <p>At Cake Delights, our mission is simple: to spread joy and sweetness, one slice at a time. Each cake is made with care using only the finest ingredients, ensuring that every bite is a delight for the senses.</p>
            <p>Our bakery offers a wide range of cakes for all occasions, including birthdays, weddings, anniversaries, baby showers, and corporate events. From elegant tiered cakes to themed creations, we can bring your vision to life and make your celebration truly special.</p>
            <p>In addition to cakes, we also offer a variety of desserts, including cupcakes, cookies, brownies, and pastries. Whether you're craving a classic chocolate chip cookie or a decadent red velvet cupcake, we have something to satisfy every sweet tooth.</p>
            <p>At Cake Delights, customer satisfaction is our top priority. We work closely with each customer to understand their preferences and create customized treats that exceed their expectations. With attention to detail and a personal touch, we strive to make every order a memorable experience.</p>
            <div class="image-container">
                <img src="7.jpg" alt="About Image 1">
                <img src="6.jpg" alt="About Image 2">
            </div>
            <p>Experience the joy of Cake Delights and let us sweeten your next celebration. Visit our bakery today or contact us to place your order. We look forward to serving you and creating delicious memories together!</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Cake Delights. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Cake Delights</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    
    <header>
        <img src="p.webp"Cake Delights Logo">
        <div class="container">
            <h1>Contact Cake Delights</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="contact-form">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Get in touch with us to order delicious cakes for your special occasions!</p>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit" class="btn">Send</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Cake Delights. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
