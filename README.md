<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SecureCam Solutions</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"/>
  <style>
    body { margin:0; font-family: 'Roboto', sans-serif; color:#333; }
    header { background:#1A1A1A; color:#FFF; padding:2rem 1rem; text-align:center; }
    nav a { color:#FFF; margin:0 0.5rem; text-decoration:none; font-weight:700; }
    .hero { background:#f4f4f4; padding:4rem 1rem; text-align:center; }
    .hero h1 { margin-bottom:0.5rem; }
    .hero p { margin-top:0; color:#555; }
    section { padding:3rem 1rem; max-width:1000px; margin:0 auto; }
    h2 { text-align:center; margin-bottom:1.5rem; }
    .services, .testimonials { display:grid; grid-template-columns:1fr 1fr; gap:1.5rem; }
    .service, .testimonial { background:#fafafa; padding:1.5rem; border-radius:6px; box-shadow:0 2px 6px rgba(0,0,0,0.1); }
    .service h3, .testimonial h3 { margin-top:0; }
    form { display:flex; flex-direction:column; gap:1rem; max-width:500px; margin:0 auto; }
    form input, form textarea { padding:0.75rem; border:1px solid #ccc; border-radius:4px; width:100%; }
    form button { padding:0.75rem; border:none; background:#1A1A1A; color:#FFF; font-weight:700; cursor:pointer; border-radius:4px; }
    footer { background:#333; color:#ddd; text-align:center; padding:1.5rem 1rem; }
    @media(max-width:700px) {
      .services, .testimonials { grid-template-columns:1fr; }
    }
  </style>
</head>
<body>

  <header>
    <h1>SecureCam Solutions</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#testimonials">Reviews</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h1>Professional CCTV Installation & Servicing</h1>
    <p>Keeping your home and business safe across Mauritius.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service">
        <h3>Custom CCTV Installation</h3>
        <p>Wired & wireless camera setups tailored to your property’s layout.</p>
      </div>
      <div class="service">
        <h3>System Configuration</h3>
        <p>Network integration, DVR/NVR setup, and remote-viewing access.</p>
      </div>
      <div class="service">
        <h3>Repair & Troubleshooting</h3>
        <p>Prompt diagnostics and fixes for faulty cameras and recorders.</p>
      </div>
      <div class="service">
        <h3>Maintenance Plans</h3>
        <p>Scheduled check-ups to ensure your surveillance never misses a moment.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About SecureCam Solutions</h2>
    <p>
      Founded by a certified lab technologist with a passion for precision, SecureCam Solutions delivers
      professional, reliable security services across Moka and beyond. We pride ourselves on clear communication,
      transparent pricing, and technical excellence.
    </p>
  </section>

  <section id="testimonials">
    <h2>What Clients Say</h2>
    <div class="testimonials">
      <div class="testimonial">
        <h3>“Excellent Service!”</h3>
        <p>Quick installation and thorough maintenance. I feel safer already.—Jane D., Port Louis</p>
      </div>
      <div class="testimonial">
        <h3>“Highly Recommended”</h3>
        <p>Transparent pricing and super responsive. Our system never falters.—Raj P., Quatre Bornes</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Get in Touch</h2>
    <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
      <input type="text" name="Name" placeholder="Your Name" required/>
      <input type="email" name="Email" placeholder="Your Email" required/>
      <textarea name="Message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 SecureCam Solutions • Moka, Mauritius • +230 5X XXX XXX</p>
  </footer>

</body>
</html>
