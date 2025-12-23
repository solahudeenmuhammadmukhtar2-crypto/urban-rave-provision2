<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Urban Rave Business</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f6f8;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #0d6efd, #6610f2);
      color: white;
      padding: 30px 20px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 12px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 30px 20px;
    }
    .container {
      max-width: 1000px;
      margin: auto;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      margin-bottom: 20px;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }
    button {
      background: #0d6efd;
      color: white;
      border: none;
      padding: 12px 20px;
      border-radius: 6px;
      cursor: pointer;
      font-size: 16px;
    }
    button:hover {
      background: #084298;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Urban Rave Provision Store</h1>
    <p>Your trusted provision & grocery supplier</p>
    <nav>
      <a href="#home">Home</a>
      <a href="#services">Products</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home">
    <div class="container">
      <div class="card">
        <h2>Welcome to Urban Rave</h2>
        <p>We provide quality services to help individuals and businesses grow. Reliable, affordable, and professional.</p>
        <button>Get Started</button>
      </div>
    </div>
  </section>

  <section id="services">
    <div class="container">
      <h2>Our Products</h2>
      <div class="services">
        <div class="card">
          <h3><h3>Food Provisions</h3>
          <p>Rice, beans, garri, spaghetti, noodles, oil and other daily food items.</p>
        </div>
        <div class="card">
          <h3><h3>Beverages</h3>
          <p>Soft drinks, bottled water, energy drinks and more.</p>
        </div>
        <div class="card">
          <h3><h3>Household Items</h3>
          <p>Detergents, toiletries, toiletries, and basic home essentials.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="about">
    <div class="container">
      <div class="card">
        <h2>About Us</h2>
        <p>Urban Rave Provision Store is a reliable local provision business focused on supplying quality food items, beverages, and household essentials at affordable prices. We believe in trust, quality, and long-term relationships.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <div class="card">
        <h2>Contact Us</h2>
        <p><strong>Phone:</strong> +234 80X XXX XXXX</p>
        <p><strong>Email:</strong> urbanraveprovision@gmail.com</p>
        <p><strong>Location:</strong> Ilorin, Kwara State</p>
        <a href="https://wa.me/23480XXXXXXX" target="_blank"><button>Order on WhatsApp</button></a>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 Urban Rave. All Rights Reserved.</p>
  </footer>

</body>
</html>
