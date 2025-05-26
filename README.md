# Ex.07 Restaurant Website
## Date:

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
HTML CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Maison de Karthik</title>
  <link rel="stylesheet" href="styles.css"/>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&family=Inter&display=swap" rel="stylesheet">
</head>
<body>
  <header class="header">
    <h1>Maison de Karthik</h1>
    <nav>
      <a href="#">Menu</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <div class="round-images">
      <!-- Add circular image thumbnails here -->
      <img src="img1.jpg" alt="Pastry" />
      <img src="img2.jpg" alt="Dish" />
      <img src="img3.jpg" alt="Roll" />
      <img src="img4.jpg" alt="Cake" />
    </div>
    <p>Welcome to Maison de Karthik — your home for luxurious handcrafted pastries.</p>
    <img src="shop.jpg" alt="Bakery Interior" class="hero-image"/>
  </section>

  <section class="chef-intro">
    <img src="chef.jpg" alt="Chef" class="chef-photo"/>
    <div class="chef-text">
      <h2>Your Favorite Chef Karthik 🍰</h2>
      <p>Bringing years of artisan baking to your table. Crafted with love and French finesse.</p>
      <button>Know More</button>
    </div>
  </section>

  <section class="quote-section">
    <div class="quote-box">
      <h3>"Pastries are not just food, they’re memories wrapped in flavor."</h3>
    </div>
  </section>

  <section class="menu-section">
    <h2>À la pâtisserie</h2>
    <div class="menu-grid">
      <!-- Example item -->
      <div class="item-card">
        <img src="croissant.jpg" alt="Croissant" />
        <p>Croissant</p>
      </div>
      <!-- Repeat for each item -->
    </div>

    <h2>Specialty Drinks</h2>
    <div class="menu-grid">
      <div class="item-card">
        <img src="latte.jpg" alt="Latte" />
        <p>Vanilla Latte</p>
      </div>
    </div>

    <h2>Favorites</h2>
    <div class="menu-grid">
      <div class="item-card">
        <img src="macaron.jpg" alt="Macaron" />
        <p>Macaron Set</p>
      </div>
    </div>
  </section>

  <section class="reservation">
    <h2>Reserve a Table</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Email" required />
      <input type="date" />
      <input type="time" />
      <button type="submit">Book Now</button>
    </form>
    <img src="location.jpg" alt="Café Location" />
  </section>

  <footer>
    <p>© 2025 Maison de Karthik. All rights reserved.</p>
    <div class="social-gallery">
      <img src="footer1.jpg" alt="Dessert" />
      <img src="footer2.jpg" alt="Coffee" />
      <img src="footer3.jpg" alt="Interior" />
    </div>
  </footer>
</body>
</html>
```
CSS CODE:
```
body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  color: #3e2a1c;
  background-color: #fffaf6;
}

.header {
  display: flex;
  justify-content: space-between;
  padding: 1rem 2rem;
  background: #fff0e6;
  font-family: 'Playfair Display', serif;
}

.header h1 {
  font-size: 2rem;
}

.header nav a {
  margin: 0 1rem;
  text-decoration: none;
  color: #7a503c;
}

.hero {
  text-align: center;
  padding: 2rem;
}

.round-images img {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin: 0.5rem;
}

.hero-image {
  width: 80%;
  max-width: 500px;
  border-radius: 1rem;
  margin-top: 1rem;
}

.chef-intro {
  display: flex;
  align-items: center;
  padding: 2rem;
  background: #fff3e6;
}

.chef-photo {
  width: 200px;
  border-radius: 1rem;
  margin-right: 2rem;
}

.chef-text h2 {
  font-family: 'Playfair Display', serif;
  font-size: 1.8rem;
}

.chef-text button {
  margin-top: 1rem;
  padding: 0.5rem 1rem;
  background: #7a503c;
  color: white;
  border: none;
  border-radius: 0.5rem;
}

.quote-section {
  background: #5c3a2d;
  color: white;
  padding: 2rem;
  text-align: center;
}

.menu-section {
  padding: 2rem;
}

.menu-section h2 {
  font-family: 'Playfair Display', serif;
  margin-top: 2rem;
}

.menu-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}

.item-card {
  flex: 1 0 120px;
  text-align: center;
}

.item-card img {
  width: 100px;
  border-radius: 0.5rem;
}

.reservation {
  padding: 2rem;
  background: #fff0e6;
  display: flex;
  justify-content: space-between;
}

.reservation form {
  flex: 1;
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
}

.reservation img {
  width: 40%;
  border-radius: 1rem;
}

footer {
  background: #3e2a1c;
  color: white;
  padding: 1rem;
  text-align: center;
}

.social-gallery img {
  width: 60px;
  margin: 0.3rem;
  border-radius: 0.5rem;
}

```
## OUTPUT:
![Screenshot 2025-05-26 094059](https://github.com/user-attachments/assets/84521d85-e405-4364-bb65-1412818da62f)
![Screenshot 2025-05-26 094112](https://github.com/user-attachments/assets/42072c45-6ab0-4953-b938-14b404ce5039)
![Screenshot 2025-05-26 094124](https://github.com/user-attachments/assets/83b8c89c-3b26-449f-a65f-fd4e7ac5cbf3)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
