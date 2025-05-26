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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>PRIYESH KITCHEN</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: #FFF8DC;
      color: #2F2F2F;
      scroll-behavior: smooth;
    }

    header {
      text-align: center;
    }

    .banner {
      width: 100%;
      height: auto;
    }

    nav ul {
      display: flex;
      justify-content: center;
      background-color: #4B0082;
      padding: 10px;
      list-style: none;
      margin: 0;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      text-decoration: none;
      color: #FFD700;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      border-bottom: 2px solid #FFD700;
    }

    h1, h2 {
      text-align: center;
      color: #191970;
    }

    .menu-grid, .admin-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .menu-item, .admin-card {
      background-color: #ffffff;
      border: 2px solid #FFD700;
      padding: 15px;
      text-align: center;
      border-radius: 8px;
    }

    .menu-item img, .admin-card img {
      width: 100%;
      height: auto;
      border-radius: 5px;
    }

    footer {
      background-color: #191970;
      color: white;
      text-align: center;
      padding: 10px;
    }

    .nav-anchor {
      display: block;
      height: 80px;
      margin-top: -80px;
      visibility: hidden;
    }
  </style>
</head>
<body>

  <header>
    <img src="rest.jpg" alt="Banner" class="banner">
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#menu">Menu</a></li>
        <li><a href="#admin">Administration</a></li>
        <li><a href="#contact">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <!-- Home Page -->
  <div class="nav-anchor" id="home"></div>
  <section>
    <h1>Welcome to Royal Feast</h1>
    <p style="text-align: center;">Where every meal is fit for royalty. Enjoy world-class cuisine crafted with passion and elegance.</p>
  </section>

  <!-- Menu Page -->
  <div class="nav-anchor" id="menu"></div>
  <section>
    <h2>Our Royal Menu</h2>
    <div class="menu-grid">
      <!-- Repeat for 12 items -->
      <div class="menu-item">
        <img src="p.jpeg" alt="Pasta">
        <h3>Royal Pasta</h3>
        <p>Creamy Alfredo with truffle essence.</p>
      </div>
      <div class="menu-item">
        <img src="biri.jpeg" alt="Biryani">
        <h3>Royal Biryani</h3>
        <p>Layered basmati rice and saffron chicken.</p>
      </div>
      <!-- Add 10 more dishes -->
    </div>
  </section>

  <!-- Admin Page -->
  <div class="nav-anchor" id="admin"></div>
  <section>
    <h2>Our Royal Staff</h2>
    <div class="admin-grid">
      <!-- Repeat for 6 staff -->
      <div class="admin-card">
        <img src="r.jpg" alt="Chef Arya">
        <h3>RANGARAJ</h3>
        <p>Chef</p>
      </div>
      <div class="admin-card">
        <img src="d.jpg" alt="Manager Raj">
        <h3>DHAMU</h3>
        <p>HEAD CHEF</p>
      </div>
      <div class="admin-card">
        <img src="b.jpeg" alt="Manager Raj">
        <h3>BALA</h3>
        <p>General Manager</p>
      </div>
      <!-- Add 4 more staff -->
    </div>
  </section>

  <!-- Contact Page -->
  <div class="nav-anchor" id="contact"></div>
  <section>
    <h2>Contact Us</h2>
    <p style="text-align: center;">
      <strong>Address:</strong> 123 Palace Avenue, Royal City<br>
      <strong>Phone:</strong> +91 98765 43210<br>
      <strong>Email:</strong> contact@royalfeast.com
    </p>
  </section>

  <footer>
    <p>&copy; 2025 Royal Feast | Designed by [Your Name]</p>
  </footer>

</body>
</html>

```
## OUTPUT:
![Screenshot 2025-05-26 094059](https://github.com/user-attachments/assets/84521d85-e405-4364-bb65-1412818da62f)
![Screenshot 2025-05-26 094112](https://github.com/user-attachments/assets/42072c45-6ab0-4953-b938-14b404ce5039)
![Screenshot 2025-05-26 094124](https://github.com/user-attachments/assets/83b8c89c-3b26-449f-a65f-fd4e7ac5cbf3)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
