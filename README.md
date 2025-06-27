<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Melinis Cakes</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; color: #333; }
    header { background: #f8e8f4; padding: 20px; text-align: center; }
    header h1 { margin: 0; font-size: 2.5rem; color: #d87fb5; }
    nav ul { list-style: none; padding: 0; margin: 10px 0; display: flex; justify-content: center; }
    nav li { margin: 0 15px; }
    nav a { text-decoration: none; color: #555; font-weight: bold; }
    .hero { background: url('images/hero-bg.jpg') center/cover no-repeat; height: 60vh; display: flex; align-items: center; justify-content: center; }
    .hero h2 { background: rgba(255,255,255,0.8); padding: 15px 30px; border-radius: 8px; font-size: 2rem; }
    section { padding: 60px 20px; max-width: 960px; margin: auto; }
    .gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; }
    .gallery img { width: 100%; border-radius: 8px; }
    .contact-form { display: flex; flex-direction: column; max-width: 400px; margin: auto; }
    .contact-form input, .contact-form textarea { margin-bottom: 15px; padding: 10px; border: 1px solid #ccc; border-radius: 4px; }
    .contact-form button { padding: 10px; border: none; border-radius: 4px; background: #d87fb5; color: white; font-size: 1rem; cursor: pointer; }
    footer { background: #f2f2f2; text-align: center; padding: 20px; font-size: 0.9rem; }
  </style>
</head>
<body>
  <header>
    <h1>Melinis Cakes</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#gallery">Gallery</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>
  <div class="hero">
    <h2>Delicious & Affordable Cakes for Every Occasion</h2>
  </div>
  <section id="about">
    <h2>About Us</h2>
    <p>Welcome to Melinis Cakes! We specialize in crafting a variety of cheap and affordable cakes for all occasions. Whether it’s a birthday, wedding, or casual gathering, we’ve got you covered. Browse our gallery for inspiration and reach out for a quote—we’re more than happy to help!</p>
  </section>
  <section id="gallery">
    <h2>Our Cakes</h2>
    <div class="gallery">
      <img src="images/IMG_3891.JPG" alt="Cake 1">
      <img src="images/IMG_3979.JPG" alt="Cake 2">
      <img src="images/IMG_8404.JPG" alt="Cake 3">
      <img src="images/IMG_5542.JPG" alt="Cake 4">
    </div>
  </section>
  <section id="contact">
    <h2>Contact Us</h2>
    <form class="contact-form">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message / Inquiry" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>
  <footer>
    <p>&copy; 2025 Melinis Cakes. All Rights Reserved.</p>
  </footer>
</body>
</html>
<div class="gallery">
  <img src="images/IMG_3891.JPG" alt="Cake 1">
  <img src="images/IMG_3979.JPG" alt="Cake 2">
  <img src="images/IMG_8404.JPG" alt="Cake 3">
  <img src="images/IMG_5542.JPG" alt="Cake 4">
</div>
