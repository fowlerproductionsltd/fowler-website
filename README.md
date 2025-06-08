<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Fowler Productions Ltd</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background: #fff;
      color: #333;
    }

    header {
      background-color: #d32f2f;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header img {
      width: 80px;
      margin-bottom: 10px;
    }

    nav {
      background: #b71c1c;
      display: flex;
      justify-content: center;
      padding: 10px;
      flex-wrap: wrap;
    }

    nav a {
      color: white;
      margin: 10px 20px;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1532634726-8b9fb99825c7?auto=format&fit=crop&w=1500&q=80') no-repeat center center/cover;
      height: 60vh;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
    }

    .hero h2 {
      font-size: 2.5em;
      background-color: rgba(0, 0, 0, 0.5);
      padding: 10px 20px;
      border-radius: 10px;
    }

    .section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .section h2 {
      color: #d32f2f;
      margin-bottom: 20px;
    }

    ul {
      padding-left: 20px;
    }

    .cta {
      text-align: center;
      margin-top: 30px;
    }

    .cta a {
      background: #d32f2f;
      color: white;
      padding: 12px 25px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
    }

    .social {
      display: flex;
      justify-content: center;
      margin-top: 20px;
      gap: 15px;
    }

    .social img {
      width: 30px;
      height: 30px;
    }

    footer {
      background: #212121;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    /* WhatsApp Floating Button */
    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      z-index: 100;
    }

    .whatsapp-float img {
      width: 60px;
      height: 60px;
    }

    @media (max-width: 768px) {
      header h1 { font-size: 2em; }
      .hero h2 { font-size: 1.8em; }
    }
  </style>
</head>
<body>

  <header>
    <img src="https://via.placeholder.com/80x80.png?text=F" alt="Fowler Logo">
    <h1>Fowler Productions Ltd</h1>
    <p>Driven by Passion. Built on Purpose.</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Innovating Uganda’s Future: Agriculture, Real Estate & Printing</h2>
  </section>

  <section class="section" id="about">
    <h2>About Us</h2>
    <p>Fowler Productions Ltd is a bold and diversified Ugandan company that leads in printing, agriculture, transport, and real estate. We empower communities with reliable services and purpose-driven innovation.</p>
  </section>

  <section class="section" id="services">
    <h2>Our Services</h2>
    <ul>
      <li><strong>Printing & Stationery:</strong> Custom prints for schools and businesses.</li>
      <li><strong>Agriculture:</strong> Supplying produce and running 7 acres of maize farming.</li>
      <li><strong>School Book Supply:</strong> Branded and delivered each school term.</li>
      <li><strong>Real Estate:</strong> Affordable, quality rentals (ground + first floor).</li>
      <li><strong>Transport:</strong> Toyota Premio for local business and delivery services.</li>
      <li><strong>Piggery (Coming Soon):</strong> Affordable pork production & supply.</li>
    </ul>
    <div class="cta">
      <a href="https://wa.me/256706349208?text=Hello%20Fowler%20Productions%20Ltd!%20I%20would%20like%20a%20quote%20for%20your%20services." target="_blank">Request a Quote</a>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p><strong>Email:</strong> <a href="mailto:fowlerproductinltd@gmail.com">fowlerproductinltd@gmail.com</a></p>
    <p><strong>Phone:</strong> +256 706 349208 / +256 700 715713</p>

    <div class="social">
      <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook">
      <img src="https://cdn-icons-png.flaticon.com/512/1384/1384063.png" alt="Instagram">
      <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Fowler Productions Ltd. All rights reserved.</p>
  </footer>

  <!-- WhatsApp Chat Button -->
  <div class="whatsapp-float">
    <a href="https://wa.me/256706349208" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/220/220236.png" alt="Chat with us on WhatsApp">
    </a>
  </div>

</body>
</html>
