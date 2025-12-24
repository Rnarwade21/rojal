# rojal
#index.html#
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>BunnyBox – Curated Gifting</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="style.css" />
</head>
<body>

<!-- NAVBAR -->
<header class="navbar">
  <div class="logo">🐰 BunnyBox</div>
  <nav>
    <a href="#">Home</a>
    <a href="#">Shop</a>
    <a href="#">Pricing</a>
    <a href="#">Appointment</a>
    <a href="#">Contact us</a>
  </nav>
  <button class="btn">Contact Us</button>
</header>

<!-- HERO -->
<section class="hero">
  <div class="hero-text">
    <h1>Curate, create,<br>deliver unforgettable experiences</h1>
    <p>Providing customized gift solutions to enhance your gifting experience.</p>
    <button class="btn">Our hampers</button>
  </div>
  <div class="hero-img">
    <img src="https://via.placeholder.com/400" alt="illustration">
  </div>
</section>

<!-- INFO SECTION -->
<section class="info">
  <div class="info-img">
    <img src="https://via.placeholder.com/300" />
  </div>
  <div class="info-text">
    <h2>Top quality products</h2>
    <p>
      Our gift hampers are curated for elegance, quality, and joy.
      Discover what they love and create the perfect gift.
    </p>
  </div>
</section>

<!-- FEATURE CARDS -->
<section class="cards">
  <div class="card">
    <h3>Key Feature</h3>
    <p>Elevating your gifting experience together</p>
  </div>
  <div class="card">
    <h3>Gift Hub</h3>
    <p>Where gifting dreams come true</p>
  </div>
</section>

<!-- CATEGORIES -->
<section class="categories">
  <h2>Creating Memorable Moments</h2>
  <div class="grid">
    <div class="cat">Beauty <button>Explore Now</button></div>
    <div class="cat">Chocolates <button>Explore Now</button></div>
    <div class="cat">Gourmet <button>Explore Now</button></div>
    <div class="cat">Home Decor <button>Explore Now</button></div>
    <div class="cat">Jewellery <button>Explore Now</button></div>
    <div class="cat">Mugs <button>Explore Now</button></div>
    <div class="cat">Personalized <button>Explore Now</button></div>
    <div class="cat">Wellness <button>Explore Now</button></div>
  </div>
</section>

<!-- FAQ -->
<section class="faq">
  <h2>Need assistance?</h2>
  <div class="faq-grid">
    <div>
      <h4>What makes us unique?</h4>
      <p>Personalized gifting solutions tailored to your needs.</p>
    </div>
    <div>
      <h4>Is the website easy to navigate?</h4>
      <p>Designed for seamless browsing.</p>
    </div>
    <div>
      <h4>Can you trust product quality?</h4>
      <p>We partner with renowned brands.</p>
    </div>
  </div>
</section>

<footer>
  © 2025 BunnyBox. All rights reserved.
</footer>

<script src="script.js"></script>
</body>
</html>
#style.css#
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}

body {
  background: linear-gradient(135deg, #fde2ea, #f9d6e3);
  color: #222;
}

/* NAVBAR */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 16px 40px;
  background: white;
  position: sticky;
  top: 0;
  z-index: 100;
}

.navbar nav a {
  margin: 0 12px;
  text-decoration: none;
  color: #333;
  font-weight: 500;
}

.logo {
  font-weight: bold;
  font-size: 20px;
}

.btn {
  background: #c8a6d8;
  border: none;
  padding: 10px 18px;
  border-radius: 8px;
  cursor: pointer;
}

/* HERO */
.hero {
  display: flex;
  padding: 80px;
  align-items: center;
  justify-content: space-between;
}

.hero-text h1 {
  font-size: 48px;
  margin-bottom: 20px;
}

.hero-text p {
  max-width: 400px;
  margin-bottom: 20px;
}

/* INFO */
.info {
  display: flex;
  padding: 80px;
  align-items: center;
}

.info-text {
  margin-left: 40px;
}

/* CARDS */
.cards {
  display: flex;
  gap: 40px;
  padding: 60px 80px;
}

.card {
  background: white;
  padding: 40px;
  border-radius: 20px;
  width: 100%;
}

/* CATEGORIES */
.categories {
  padding: 80px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
  margin-top: 30px;
}

.cat {
  background: #bfbfbf;
  border-radius: 16px;
  padding: 20px;
  position: relative;
}

.cat button {
  margin-top: 10px;
  padding: 6px 12px;
  border-radius: 6px;
  border: none;
}

/* FAQ */
.faq {
  padding: 80px;
}

.faq-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 40px;
}

footer {
  text-align: center;
  padding: 30px;
  background: white;
  margin-top: 60px;
}
#script.js#
// Placeholder for future interactivity
console.log("BunnyBox loaded successfully 🐰");

