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

    header h1 {
      margin: 10px 0;
      font-size: 3em;
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

    footer {
      background: #212121;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    @media (max-width: 768px) {
      header h1 { font-size: 2em; }
      .hero h2 { font-size: 1.8em; }
    }
  </style>
</head>
<body>

  <header>
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
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p><strong>Email:</strong> <a href="mailto:fowlerproductinltd@gmail.com">fowlerproductinltd@gmail.com</a></p>
    <p><strong>Phone:</strong> +256 706 349208 / +256 700 715713</p>
  </section>

  <footer>
    <p>&copy; 2025 Fowler Productions Ltd. All rights reserved.</p>
  </footer>

</body>
</html>
