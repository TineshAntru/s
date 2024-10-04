<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>FACT Systems</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <style>
    /* Global Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      text-align: center; /* Centers text globally */
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
      background-color: #333;
      color: #fff;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav ul li {
      display: inline;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }

    /* Hero Section */
    .hero {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: url('hero-image.jpg') no-repeat center center/cover;
      color: #fff;
      text-align: center;
    }

    .hero h2 {
      font-size: 2.5em;
    }

    /* Button Styles */
    .cta {
      margin-top: 20px;
      padding: 15px 30px;
      background: url('button-background.jpg') no-repeat center center/cover;
      color: white;
      border: none;
      font-size: 1.2em;
      cursor: pointer;
      text-decoration: none;
      font-weight: bold;
      border-radius: 8px;
    }

    .cta:hover {
      opacity: 0.9;
    }

    /* About Section */
    .about, .services, .contact {
      padding: 50px;
      background-color: #f4f4f4;
      text-align: center;
    }

    .about p {
      max-width: 800px;
      margin: 0 auto;
    }

    /* Services Section */
    .service-items {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .service-item {
      flex: 1;
      max-width: 300px;
      padding: 20px;
      background-color: white;
      border-radius: 8px;
      box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    }

    .service-item i {
      font-size: 2.5em;
      color: #0066cc; /* Changed icon color to blue */
    }

    /* Contact Section */
    #contact {
      background: linear-gradient(to right, green, blue); /* Gradient from green to blue */
      padding: 100px 50px;
      color: white;
      text-align: center;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 500px;
      margin: 0 auto;
    }

    form input, form textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    form button {
      padding: 10px;
      background-color: #0066cc; /* Button remains blue */
      color: white;
      border: none;
      cursor: pointer;
      font-size: 1em;
    }

    /* Footer */
    footer {
      padding: 20px;
      background-color: #0066cc; /* Changed footer background to blue */
      color: white;
      text-align: center;
    }

    .social-icons a {
      margin: 0 10px;
      color: white;
      font-size: 1.5em;
    }

    .social-icons a:hover {
      color: #ff6600;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <header>
    <nav>
      <div class="logo">
        <h1>FACT Systems</h1>
      </div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="hero-content">
      <h2>Your Trusted Partner in Technology and Safety</h2>
      <p>We provide advanced security and automation solutions to safeguard your assets and ensure your peace of mind.</p>
      <a href="#contact" class="cta">Contact Us Today</a>
    </div>
  </section>

  <!-- About Us Section -->
  <section id="about" class="about">
    <h2>About FACT Systems</h2>
    <p>FACT Systems was founded by Mrs. Vijaya Reddy and is currently managed by Mr. Prakash Reddy. With over a decade of collective experience, we specialize in providing cutting-edge building automation, security, and fire protection solutions. We are committed to offering our customers the best technology solutions backed by exceptional service and support.</p>
    <p>We work with leading international brands such as Edwards System Technology, Honeywell, Notifier, Bosch, and more to ensure the highest standards of safety and performance. From system design to installation, testing, and maintenance, FACT Systems is your reliable partner for comprehensive safety and automation solutions.</p>
  </section>

  <!-- Services Section -->
  <section id="services" class="services">
    <h2>Our Services</h2>
    <div class="service-items">
      <div class="service-item">
        <i class="fas fa-shield-alt"></i>
        <h3>Security Solutions</h3>
        <p>Advanced security systems, including CCTV, access control, and intrusion detection to protect your premises.</p>
      </div>
      <div class="service-item">
        <i class="fas fa-fire-extinguisher"></i>
        <h3>Fire Protection Systems</h3>
        <p>State-of-the-art fire detection, suppression, and alarm systems to ensure maximum fire safety for your facilities.</p>
      </div>
      <div class="service-item">
        <i class="fas fa-building"></i>
        <h3>Building Automation</h3>
        <p>Integration of automation systems, including HVAC, lighting, and energy management, for smarter and more efficient operations.</p>
      </div>
      <div class="service-item">
        <i class="fas fa-tools"></i>
        <h3>Maintenance and Support</h3>
        <p>Comprehensive maintenance contracts and support services to ensure your systems are always operating at peak efficiency.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Get in Touch</h2>
    <p>If you have any questions or would like to inquire about our services, feel free to reach out to us. We look forward to working with you.</p>
    <form action="submit">
      <label for="name">Name</label>
      <input type="text" id="name" name="name" required placeholder="Enter your full name">

      <label for="email">Email</label>
      <input type="email" id="email" name="email" required placeholder="Enter your email address">

      <label for="message">Message</label>
      <textarea id="message" name="message" required placeholder="Enter your message"></textarea>

      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2024 FACT Systems. All rights reserved.</p>
    <div class="social-icons">
      <a href="#" aria-label="Facebook"><i class="fab fa-facebook-f"></i></a>
      <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
      <a href="#" aria-label="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
    </div>
  </footer>

</body>
</html>
