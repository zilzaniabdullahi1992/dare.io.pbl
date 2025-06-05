# Mini Project Assessmant: Responsive landing Page design
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Maiduguri Kitchen</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f9f9f9;
    }

    /* Hero Section */
    .hero {
      background-color: #ffce00;
      text-align: center;
      padding: 4rem 2rem;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }

    .cta-button {
      display: inline-block;
      padding: 0.8rem 1.5rem;
      background-color: #000;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

    /* Features Section */
    .features {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2rem;
      padding: 4rem 2rem;
      background-color: #fff;
    }

    .feature {
      flex: 1 1 250px;
      max-width: 300px;
      text-align: center;
    }

    .feature img {
      width: 80px;
      height: 80px;
      margin-bottom: 1rem;
    }

    .feature h2 {
      font-size: 1.5rem;
      margin-bottom: 0.5rem;
    }

    /* Footer Section */
    .footer {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
    }

    /* Responsive */
    @media (max-width: 768px) {
      .features {
        flex-direction: column;
        align-items: center;
      }

      .hero h1 {
        font-size: 2rem;
      }

      .hero p {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <header class="hero">
    <h1>Maiduguri Kitchen</h1>
    <p>Delicious local meals delivered fresh to your doorstep.</p>
    <a href="#features" class="cta-button">Order Now</a>
  </header>

  <!-- Features Section -->
  <section id="features" class="features">
    <div class="feature">
      <img src="https://i.postimg.cc/g2XHpY6Q/Screenshot-20250605-153346-1.jpg" alt="Fast Delivery" />
      <h2>Fast Delivery</h2>
      <p>Meals delivered in under 30 minutes within Maiduguri.</p>
    </div>
    <div class="feature">
      <img src="https://i.postimg.cc/pVBmmgHT/Screenshot-20250605-154927-1.jpg" alt="Fresh Ingredients" />
      <h2>Fresh Ingredients</h2>
      <p>We use only fresh and locally sourced ingredients.</p>
    </div>
    <div class="feature">
      <img src="https://i.postimg.cc/NFMMRj6x/Screenshot-20250605-155735-1.jpg" alt="Easy Ordering" />
      <h2>Easy Ordering</h2>
      <p>Place your order quickly and easily on any device.</p>
    </div>
  </section>

  <!-- Footer Section -->
  <footer class="footer">
    <p>Contact us: maidugurikitchen@gmail.com | +234 806 531 3589</p>
    <p>&copy; 2025 Maiduguri Kitchen. All rights reserved.</p>
  </footer>

</body>
</html>
