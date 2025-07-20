
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sole Style | Shoes for Every Step</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f0f0f0;
      color: #222;
      line-height: 1.6;
    }
    header {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }
    header h1 {
      font-size: 3em;
    }
    nav {
      background-color: #444;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }
    nav a {
      margin: 0 20px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 40px 20px;
      text-align: center;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 30px;
    }
    .product {
      background-color: white;
      border: 1px solid #ccc;
      border-radius: 15px;
      width: 260px;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .product:hover {
      transform: scale(1.05);
    }
    .product img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Sole Style</h1>
    <p>Step Up with Style — Casual, Formal, and Running Shoes</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#products">Collection</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home">
    <h2>Welcome to Sole Style</h2>
    <p>Discover a curated selection of shoes designed for every occasion. From the streets to the gym to formal gatherings — we've got your feet covered.</p>
  </section>

  <section id="products">
    <h2>Featured Collection</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/250x160.png?text=Casual+Sneakers" alt="Casual Sneakers" />
        <h3>Casual Sneakers</h3>
        <p>Lightweight and comfy — perfect for daily wear and city strolls.</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x160.png?text=Formal+Leather+Shoes" alt="Formal Leather Shoes" />
        <h3>Formal Leather Shoes</h3>
        <p>Class and elegance combined in our handcrafted leather collection.</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x160.png?text=Running+Trainers" alt="Running Trainers" />
        <h3>Running Trainers</h3>
        <p>Engineered for performance, these shoes will keep up with your hustle.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Sole Style was founded with a passion for quality footwear. Every pair we offer is chosen with comfort, durability, and design in mind.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: support@solestyle.com<br>
    Phone: (123) 456-7890<br>
    Instagram: @SoleStyleShoes</p>
  </section>

  <footer>
    &copy; 2025 Sole Style. All rights reserved. Designed for your journey.
  </footer>
</body>
</html>
