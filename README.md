# Ex.07 Restaurant Website
## Date:14/12/2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

## HTML:

```
restapp.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASIAN RESTAURANT</title>
    <link rel="stylesheet" href="restapp.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="./images/Asian_Restaurant-removebg.png" alt="Little Lemon Logo">
            <h1>ASIAN RESTAURANT</h1>
        </div>
        <nav>
            <ul>
                <li><a href="./restapp.html">Home</a></li>
                <li><a href="./menu.html">Menu</a></li>
                <li><a href="./admin.html">Administration</a></li>
                <li><a href="./contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section class="promo">
        <div class="promo-text">
            <h2>30% Off This Weekend</h2>
            <p>
                Enjoy a flavorful weekend with **30% off** on all dishes at our Asian restaurant! Treat yourself to authentic tastes and modern twists while saving big—this weekend only!
            </p>
        </div>
    </section>
    <main>
        <div class="card-container">
            <div class="card">
                <h3>Menu</h3>
                <img src="./images/menu.webp" alt="Menu">
                <p>
                    Discover the rich and diverse flavors of Asia with our carefully curated menu, featuring a blend of savory, spicy, and aromatic dishes crafted with fresh, authentic ingredients. From hearty noodle bowls to crispy appetizers, every bite delivers a taste of tradition and culinary excellence.
                </p>
                <a href="./menu.html">See our new menu</a>
            </div>
            <div class="card">
                <h3>Book a table</h3>
                <img src="./images/book a table.webp" alt="Reserve Now">
                <p>
                    Reserve your table now for an unforgettable dining experience, where delicious food meets warm hospitality. Secure your spot today and enjoy a relaxing meal at your preferred time!
                </p>
                <a href="./contact.html">Book your table now</a>
            </div>
            <div class="card">
                <h3>Opening Hours</h3>
                <img src="./images/timings.webp" alt="Timings">
                <div class="hours">
                    <p>Mon - Fri: 10AM - 10PM</p>
                    <p>Sat: 2PM - 10PM</p>
                    <p>Sun: 2PM - 10PM</p>
                </div>
            </div>
        </div>
    </main>
    <footer>
        <p>Designed and Developed by <a href="admin.html">Mohamed Rafeek</a></p>
    </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Menu | Little Lemon</title>
    <link rel="stylesheet" href="menu.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="./images/Asian_Restaurant-removebg.png" alt="Little Lemon Logo">
            <h1>ASIAN RESTAURANT</h1>
        </div>
        <nav>
            <ul>
                <li><a href="./restapp.html">Home</a></li>
                <li><a href="./menu.html">Menu</a></li>
                <li><a href="./admin.html">Administration</a></li>
                <li><a href="./contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main class="main-container">
        <section class="page-title">
            <div>Our Menu</div>
            <p>Explore our delicious and freshly prepared dishes.</p>
        </section>
        <section class="menu-items">
            <div class="menu-card">
                <h3>Chicken Pad Thai</h3>
                <img src="./images/chicken-pad-thai.webp" alt="Timings">
                <p>A traditional Thai stir-fried noodle dish made with tender chicken, rice noodles, eggs, and bean sprouts, tossed in a tangy tamarind sauce. Topped with crushed peanuts, lime wedges, and fresh cilantro for an authentic flavor.
                    Price: ₹229</p>
            </div>
            <div class="menu-card">
                <h3>Spicy Ramen Noodles</h3>
                <img src="./images/ramen.webp" alt="Timings">
                <p>A hearty bowl of Japanese ramen served in a spicy, savory broth with tender pork slices, soft-boiled egg, green onions, mushrooms, and a drizzle of chili oil. Perfect for spice lovers!
                    Price: ₹249</p>
            </div>
            <div class="menu-card">
                <h3>Vegetable Spring Rolls</h3>
                <img src="./images/spring-rolls.webp" alt="Timings">
                <p>Crispy golden rolls filled with a mix of fresh vegetables like cabbage, carrots, and glass noodles. Served with a side of sweet chili dipping sauce. Light, crunchy, and flavorful!
                    Price: ₹189</p>
            </div>
        </section>
    </main>
    <footer>
        <p>Designed and Developed by <a href="admin.html">Mohamed Rafeek</a></p>
    </footer>
</body>
</html>

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration | ASIAN RESTAURANT</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="./images/Asian_Restaurant-removebg.png" alt="Little Lemon Logo">
            <h1>ASIAN RESTAURANT</h1>
        </div>
        <nav>
            <ul>
                <li><a href="./restapp.html">Home</a></li>
                <li><a href="./menu.html">Menu</a></li>
                <li><a href="./admin.html">Administration</a></li>
                <li><a href="./contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>

        
        <div class="admin-container">   

            <div class="admin-container-right">
                <section class="page-title">
                    <h2>Administration</h2>
                    <p>Founder Of The Restaurant</p>
                    
                        <div class="admin-containter-left">
                            <img src="./images/manager.jpg" alt="manager Rafeek photo" >
                        </div>
                    
                </section>
                <section class="admin-content">
                    <ul>
                    <p>At just 18, Mohamed Rafeek opened his dream Asian restaurant in 2024, inspired by his grandmother’s recipes. Growing up in a small town, he spent years helping her cook dumplings, stir-fries, and ramen. With his savings, passion, and a small loan, he transformed a cozy corner space into "Asian Restaurant." . Social media buzzed, drawing in food lovers eager for unique flavors. Despite doubts about his age, Rafeek's dedication and authenticity won hearts. By year’s end, "Asian Restaurant" became the town’s favorite spot, proving dreams have no age.</p>
                    </ul>
                </section>
            </div>
        </div> 
        
    </main>
    <footer>
        <p>Designed and Developed by Mohamed Rafeek</p>
    </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us | ASIAN RESTAURANT</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="./images/Asian_Restaurant-removebg.png" alt="Little Lemon Logo">
            <h1>ASIAN RESTAURANT</h1>
        </div>
        <nav>
            <ul>
                <li><a href="./restapp.html">Home</a></li>
                <li><a href="./menu.html">Menu</a></li>
                <li><a href="./admin.html">Administration</a></li>
                <li><a href="./contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="page-title">
            <h2>Contact Us</h2>
            <p>We'd love to hear from you! Reach out via the form or information below.</p>
        </section>
        <section class="contact-form">
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" placeholder="Your Name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" placeholder="Your Email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" rows="5" placeholder="Your Message" required></textarea>
                
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>
    <footer>
        <p>Designed and Developed by <a href="admin.html">Mohamed Rafeek</a></p>
    </footer>
</body>
</html>


```
## CSS:

```
restapp.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f7f7f7;
    color: #333;
}

header {
    background-color: #ffffff;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 2px solid #ddd;
}

header .logo {
    display: flex;
    align-items: center;
}

header .logo img {
    height: 50px;
    margin-right: 10px;
}

header h1 {
    font-size: 1.8rem;
    color: #345c46;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-size: 1rem;
    font-weight: bold;
    padding: 5px 10px;
    border-radius: 5px;
}

nav ul li a:hover {
    background-color: #ddd;
}

.promo {
    background: url('pasta.jpg') no-repeat center center/cover;
    text-align: center;
    padding: 50px 20px;
}

.promo-text h2 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

.promo-text p {
    max-width: 600px;
    margin: 0 auto;
    line-height: 1.6;
}

main {
    padding: 20px;
}

.card-container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
}

.card {
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
    text-align: center;
    flex: 1 1 calc(33.333% - 20px);
    max-width: calc(33.333% - 20px);
}

.card h3 {
    background-color: #fdebd0;
    padding: 15px;
    color: #333;
    font-size: 1.3rem;
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.card p {
    padding: 15px;
    font-size: 0.95rem;
    color: #555;
}

.card a {
    display: block;
    color: #2c7c72;
    font-weight: bold;
    text-decoration: none;
    padding: 10px;
}

.card a:hover {
    color: #345c46;
    text-decoration: underline;
}

.hours p {
    margin: 5px 0;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #f1f1f1;
    color: #555;
    margin-top: 20px;
}

footer a {
    text-decoration: none;
    color: #345c46;
    font-weight: bold;
}

footer a:hover {
    text-decoration: underline;
}

menu.css

header {
    background-color: #ffffff;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 2px solid #ddd;
}

header .logo {
    display: flex;
    align-items: center;
}

header .logo img {
    height: 50px;
    margin-right: 10px;
}

header h1 {
    font-size: 1.8rem;
    color: #345c46;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-size: 1rem;
    font-weight: bold;
    padding: 5px 10px;
    border-radius: 5px;
}

nav ul li a:hover {
    background-color: #ddd;
}


.menu-title {
    text-align: center;
    margin: 30px 0;
    padding: 10px;
    background-color: #fdebd0;
    color: #345c46;
    font-weight: bold;
    border-radius: 8px;
}

/* Menu Items Container */
.menu-container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
    margin: 20px auto;
    padding: 20px;
    max-width: 1200px;
}

.menu-card {
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
    text-align: center;
    flex: 1 1 calc(33.333% - 20px);
    max-width: calc(33.333% - 20px);
    transition: transform 0.3s ease;
}

.menu-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.menu-card h3 {
    background-color: #fdebd0;
    padding: 15px;
    color: #333;
    font-size: 1.3rem;
    margin: 0;
}

.menu-card p {
    padding: 15px;
    font-size: 0.95rem;
    color: #555;
}

.menu-card:hover {
    transform: scale(1.03);
}

.menu-items {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.page-title {
    text-align: center;
}

.page-title div {
    font-size: 22px;
    margin-top: 30px;
    font-weight: bold;
}

main {
    height: 75vh;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #f1f1f1;
    color: #555;
    margin-top: 20px;
}

footer a {
    text-decoration: none;
    color: #345c46;
    font-weight: bold;
}

footer a:hover {
    text-decoration: underline;
}


/* Responsive Design */
@media (max-width: 768px) {
    .menu-card {
        flex: 1 1 calc(50% - 20px);
        max-width: calc(50% - 20px);
    }
}

@media (max-width: 480px) {
    .menu-card {
        flex: 1 1 100%;
        max-width: 100%;
    }
}

admin.css

.admin-title {
    text-align: center;
    margin: 30px 0;
    padding: 10px;
    background-color: #fdebd0;
    color: #345c46;
    font-size: 2rem;
    font-weight: bold;
    border-radius: 8px;
}

/* Administration List */
.admin-container {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    height: fit-content;

}

h2 {
    margin: 0;
}

p {
    margin: 0;
}

.admin-list {
    list-style: none;
    padding: 0;
}

.admin-list li {
    background-color: #f7f7f7;
    margin: 10px 0;
    padding: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
    text-align: center;
    font-size: 1.1rem;
    font-weight: bold;
    color: #333;
    transition: all 0.3s ease;
}

.admin-list li:hover {
    background-color: #fdebd0;
    color: #345c46;
    cursor: pointer;
}

header {
    background-color: #ffffff;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 2px solid #ddd;
}

header .logo {
    display: flex;
    align-items: center;
}

header .logo img {
    height: 50px;
    margin-right: 10px;
}

header h1 {
    font-size: 1.8rem;
    color: #345c46;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-size: 1rem;
    font-weight: bold;
    padding: 5px 10px;
    border-radius: 5px;
}

nav ul li a:hover {
    background-color: #ddd;
}



footer {
    text-align: center;
    padding: 20px;
    background-color: #f1f1f1;
    color: #555;
    margin-top: 20px;
}

footer a {
    text-decoration: none;
    color: #345c46;
    font-weight: bold;
}

footer a:hover {
    text-decoration: underline;
}

.page-title {
    text-align: center;
    display: flex;
    align-items: center;
    flex-direction: column;
    gap: 10px;
}

.page-title div {
    font-size: 22px;
    font-weight: bold;
}

.admin-container .admin-containter-left {
    width: 300px;
    height: auto;
}

.admin-container .admin-containter-left img {
    width: 100%;
    border-radius: 18px;
    margin-top: 10px
}

.admin-content ul p {
    text-align: center;
}

contact.css

.contact-title {
    text-align: center;
    margin: 30px 0;
    padding: 10px;
    background-color: #fdebd0;
    color: #345c46;
    font-size: 2rem;
    font-weight: bold;
    border-radius: 8px;
}

/* Contact Form */
.contact-container {
    max-width: 600px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.contact-form label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
    color: #333;
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-size: 1rem;
}

.contact-form button {
    background-color: #345c46;
    color: white;
    font-size: 1rem;
    font-weight: bold;
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
    margin: 0 auto;
    display: flex;
}

.contact-form button:hover {
    background-color: #2c7c72;
}

/* Responsive Adjustment */
@media (max-width: 480px) {
    .contact-container {
        padding: 15px;
    }
}


header {
    background-color: #ffffff;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 2px solid #ddd;
}

header .logo {
    display: flex;
    align-items: center;
}

header .logo img {
    height: 50px;
    margin-right: 10px;
}

header h1 {
    font-size: 1.8rem;
    color: #345c46;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-size: 1rem;
    font-weight: bold;
    padding: 5px 10px;
    border-radius: 5px;
}

nav ul li a:hover {
    background-color: #ddd;
}

.page-title {
    text-align: center;
}

.page-title div {
    font-size: 22px;
    margin-top: 30px;
    font-weight: bold;
}

main {
    height: 75vh;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #f1f1f1;
    color: #555;
    margin-top: 20px;
}

footer a {
    text-decoration: none;
    color: #345c46;
    font-weight: bold;
}

footer a:hover {
    text-decoration: underline;
}

.contact-form {
    width: 800px;
    margin: 0 auto;
    margin-top: 30px;
}

.contact-form form button{
    display: flex;
}

```

## OUTPUT:
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (29).png>)
![alt text](<Screenshot (30).png>)
![alt text](<Screenshot (32).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
