
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>MKjet – Same-Day Deliveries in Scotland</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background-color: #f4f7fa;
      color: #222;
    }
    header {
      background-color: #003366;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      margin-top: 10px;
      text-align: center;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    .cta {
      background-color: #007bff;
      color: white;
      padding: 20px;
      text-align: center;
      border-radius: 10px;
    }
    form {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    label {
      display: block;
      margin-bottom: 10px;
      font-weight: bold;
    }
    input, textarea, button {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #003366;
      color: white;
      font-weight: bold;
      cursor: pointer;
    }
    footer {
      background: #003366;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .lang-switch {
      text-align: right;
      margin: 10px 20px;
    }
    .lang-switch a {
      margin-left: 10px;
      text-decoration: none;
      color: #003366;
      font-weight: bold;
    }
    @media (max-width: 600px) {
      nav a { display: block; margin: 10px 0; }
    }
  </style>
</head>
<body>

<div class="lang-switch">
  <a href="index.html">Lietuvių</a>
</div>

<header>
  <h1>MKjet</h1>
  <p>Same-day parcel deliveries across Scotland</p>
</header>

<nav>
  <a href="#services">Services</a>
  <a href="#form">Book</a>
  <a href="#contact">Contact</a>
</nav>

<section id="services">
  <h2>Our Services</h2>
  <ul>
    <li>Fast collection and same-day delivery</li>
    <li>Flexible solutions for businesses and private clients</li>
    <li>Delivery area: all of Scotland</li>
  </ul>
  <div class="cta">📞 Book now: <strong>07775174072</strong></div>
</section>

<section id="form">
  <h2>Booking Form</h2>
  <form action="https://formspree.io/f/xkgbpgle" method="POST">
    <label>Name
      <input type="text" name="name" required />
    </label>
    <label>Phone Number
      <input type="tel" name="phone" required />
    </label>
    <label>Parcel Details
      <textarea name="message" rows="4" required></textarea>
    </label>
    <button type="submit">Send Request</button>
  </form>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Phone: 07775174072</p>
  <p>Email: mkdelivery@outlook.com</p>
  <p>WhatsApp | Viber | Messenger</p>
</section>

<footer>
  &copy; 2025 MKjet – Same-day delivery across Scotland
</footer>

</body>
</html>
