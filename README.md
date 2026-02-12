<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="KPandCo – Black female-owned supply and delivery business providing professional, reliable services across South Africa.">
  <title>KPandCo – Supply & Delivery Solutions</title>
  <style>
    /* Brand Colors */
    :root {
      --royal-blue: #2B3A67;
      --gold: #D4AF37;
      --cream: #FDF4E3;
      --charcoal: #333333;
      --light-blue: #A3C4F3;
    }

    /* Reset & Typography */
    * { margin:0; padding:0; box-sizing:border-box; font-family: Arial, sans-serif; }
    body { background-color: var(--cream); color: var(--charcoal); line-height: 1.6; }
    a { color: var(--royal-blue); text-decoration: none; }
    a:hover { color: var(--gold); }

    header { background-color: var(--royal-blue); color: var(--cream); padding: 20px 0; text-align: center; }
    header img { max-width: 80px; display: block; margin: 0 auto 10px; }
    header h1 { font-size: 2rem; }

    nav { text-align: center; margin-bottom: 20px; }
    nav a { margin: 0 15px; font-weight: bold; }

    section { padding: 60px 20px; max-width: 1000px; margin: auto; }
    section h2 { font-size: 1.8rem; color: var(--royal-blue); margin-bottom: 20px; }
    section p { font-size: 1.1rem; margin-bottom: 15px; }

    footer { background-color: var(--charcoal); color: var(--cream); text-align: center; padding: 20px 0; margin-top: 40px; }
    footer a { color: var(--gold); }

    form input, form textarea { width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid var(--charcoal); border-radius: 5px; }
    form button { background-color: var(--gold); color: var(--charcoal); border: none; padding: 10px 20px; cursor: pointer; font-weight: bold; border-radius: 5px; }
    form button:hover { background-color: var(--royal-blue); color: var(--cream); }

    @media(max-width:600px) {
      nav a { display:block; margin:10px 0; }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <img src="crown.png" alt="KPandCo Crown Logo">
    <h1>KPandCo</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Home Section -->
  <section id="home">
    <h2>Welcome to KPandCo</h2>
    <p>KPandCo is a **Black female-owned supply and delivery business**, providing professional, reliable, and personalized services across South Africa. We empower communities, support local businesses, and deliver excellence in every order.</p>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Us</h2>
    <p>KPandCo is committed to making supply and delivery **simple, efficient, and trustworthy** for businesses and individuals alike. We bring a personal touch, accountability, and professionalism to every client relationship.</p>
    <p>Our mission is to **streamline operations, save time, and ensure your products and supplies reach their destination safely and on schedule**.</p>
  </section>

  <!-- Services Section -->
  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li><strong>Reliable Supply Services:</strong> sourcing and delivering quality products on time.</li>
      <li><strong>Efficient Delivery:</strong> fast, secure, and fully trackable.</li>
      <li><strong>Flexible Solutions:</strong> customized services for businesses of all sizes.</li>
      <li><strong>Personalized Attention:</strong> treating every client like a partner.</li>
    </ul>
    <h3>Why Choose KPandCo?</h3>
    <ul>
      <li><strong>Integrity:</strong> transparent operations and dependable service.</li>
      <li><strong>Excellence:</strong> high-quality service and attention to detail.</li>
      <li><strong>Empowerment:</strong> supporting local communities and women-led businesses.</li>
    </ul>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email us at <a href="mailto:kefi@kpandco.co.za">kefi@kpandco.co.za</a> or <a href="mailto:info@kpandco.co.za">info@kpandco.co.za</a></p>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 KPandCo. All rights reserved.</p>
    <p><a href="#home">Back to top</a></p>
  </footer>

</body>
</html>
