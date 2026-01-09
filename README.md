<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hoosier Web Design | Websites for Indiana Businesses</title>
  <meta name="description" content="Professional website design for Indiana businesses. We help Hoosiers grow with fast, modern, and affordable websites." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #1c2a44;        /* deep navy */
      --secondary: #0b1220;      /* near-black blue */
      --accent: #d4af37;         /* luxury gold */
      --bg: #0e1628;             /* dark luxury background */
      --card: #111c33;           /* dark card surface */
      --text: #f8fafc;           /* soft white text */
      --muted: #9aa4b2;          /* muted silver */
      --radius: 18px;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: linear-gradient(180deg, #0b1220, #0e1628);
      color: var(--text);
      line-height: 1.6;
    }

    a { text-decoration: none; color: inherit; }

    header {
      background: radial-gradient(circle at top, #243b6b, #0b1220 70%);
      color: white;
      padding: 90px 20px;
    }

    .container {
      max-width: 1200px;
      margin: auto;
      padding: 0 20px;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 60px;
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 12px;
      font-weight: 800;
      letter-spacing: 0.5px;
    }

    .logo img {
      width: 42px;
      height: 42px;
    }

    .logo span {
      display: block;
      font-size: 1.4rem;
      line-height: 1.1;
    }

    .logo small {
      display: block;
      font-size: 0.7rem;
      color: var(--accent);
      letter-spacing: 1px;
      text-transform: uppercase;
    }

    .nav-links a {
      margin-left: 24px;
      font-weight: 500;
      opacity: 0.9;
    }

    .hero {
      display: grid;
      grid-template-columns: 1.2fr 0.8fr;
      gap: 40px;
      align-items: center;
    }

    .hero h1 {
      font-size: 3rem;
      line-height: 1.2;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.1rem;
      opacity: 0.95;
      margin-bottom: 30px;
    }

    .btn {
      display: inline-block;
      background: var(--accent);
      color: #111827;
      padding: 14px 26px;
      border-radius: 999px;
      font-weight: 700;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
      box-shadow: 0 10px 20px rgba(0,0,0,0.15);
    }

    .btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 14px 28px rgba(0,0,0,0.2);
    }

    section {
      padding: 90px 20px;
    }

    .section-title {
      text-align: center;
      max-width: 700px;
      margin: 0 auto 60px;
    }

    .section-title h2 {
      font-size: 2.3rem;
      margin-bottom: 12px;
    }

    .section-title p {
      color: var(--muted);
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 28px;
    }

    .card {
      background: linear-gradient(180deg, #111c33, #0e1628);
      padding: 34px 28px;
      border-radius: var(--radius);
      box-shadow: 0 30px 60px rgba(0,0,0,0.6);
      border: 1px solid rgba(212,175,55,0.12);
    }

    .card h3 {
      margin-top: 0;
      margin-bottom: 10px;
    }

    .card p {
      color: var(--muted);
    }

    .local {
      background: linear-gradient(180deg, #0e1628, #0b1220);
    }

    .split {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 50px;
      align-items: center;
    }

    .split img {
      width: 100%;
      border-radius: var(--radius);
      box-shadow: 0 25px 60px rgba(0,0,0,0.12);
    }

    .cta {
      background: linear-gradient(135deg, #1c2a44, #0b1220);
      color: white;
      text-align: center;
      border-radius: var(--radius);
      padding: 80px 30px;
      max-width: 1000px;
      margin: auto;
      box-shadow: 0 40px 80px rgba(0,0,0,0.7);
      border: 1px solid rgba(212,175,55,0.18);
    }

    .cta h2 {
      font-size: 2.4rem;
      margin-bottom: 16px;
    }

    .cta p {
      margin-bottom: 30px;
      opacity: 0.95;
    }

    footer {
      background: radial-gradient(circle at bottom, #0e1628, #020617);
      color: #cbd5f5;
      padding: 60px 20px;
    }

    footer .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 30px;
    }

    footer h4 {
      color: white;
      margin-bottom: 12px;
    }

    footer p, footer a {
      color: #94a3b8;
      font-size: 0.95rem;
    }

    @media (max-width: 900px) {
      .hero { grid-template-columns: 1fr; }
      .split { grid-template-columns: 1fr; }
      .hero h1 { font-size: 2.4rem; }
    }
  </style>
</head>
<body>

<header>
  <div class="container">
    <nav>
      <div class="logo">
        <span>Hoosier Web Design</span>
      </div>
      <div class="nav-links">
        <a href="#services">Services</a>
        <a href="#local">Why Local</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>

    <div class="hero">
      <div>
        <h1>Websites Built for Indiana Businesses</h1>
        <p>We help Hoosiers grow online with fast, modern, and conversion-focused websites designed specifically for local businesses across Indiana.</p>
        <a class="btn" href="#contact">Get a Free Consultation</a>
      </div>
      <div>
        <img src="https://images.unsplash.com/photo-1492724441997-5dc865305da7?auto=format&fit=crop&w=900&q=80" alt="Positive Indiana community scene" />
      </div>
    </div>
  </div>
</header>

<section id="services">
  <div class="container">
    <div class="section-title">
      <h2>Everything Your Business Website Needs</h2>
      <p>From first impression to customer conversion, we build sites that work as hard as you do — with prices starting as low as <strong>$45.99</strong>.</p>
    </div>

    <div class="cards">
      <div class="card">
        <h3>Starter Website</h3>
        <p><strong>Starting at $45.99</strong><br>Perfect for new or small Indiana businesses that need a clean, professional online presence fast.</p>
      </div>
      <div class="card">
        <h3>Custom Website Design</h3>
        <p>No templates. Every site is designed around your brand, your goals, and your Indiana audience.</p>
      </div>
      <div class="card">
        <h3>Mobile & Speed Optimized</h3>
        <p>Lightning-fast, mobile-first websites that look great on phones, tablets, and desktops.</p>
      </div>
      <div class="card">
        <h3>Local SEO Ready</h3>
        <p>Built to rank for Indiana searches so local customers can actually find your business.</p>
      </div>
      <div class="card">
        <h3>Simple Pricing</h3>
        <p>Clear, honest pricing with no confusing tech jargon or surprise fees.</p>
      </div>
    </div>
  </div>
</section>

<section id="local" class="local">
  <div class="container split">
    <div>
      <h2>Made for Hoosiers, By Hoosiers</h2>
      <p>Indiana businesses deserve websites that understand local values: trust, hard work, and real results. We focus on clear messaging, clean design, and strong calls to action that turn visitors into customers.</p>
      <p>Whether you're in Indianapolis, Fort Wayne, Evansville, Bloomington, or a small town anywhere in the state, we build websites that fit your community.</p>
    </div>
    <div>
      <img src="https://images.unsplash.com/photo-1500534314209-a25ddb2bd429?auto=format&fit=crop&w=900&q=80" alt="Indiana countryside" />
    </div>
  </div>
</section>

<section id="contact">
  <div class="container">
    <div class="cta">
      <h2>Ready to Grow Your Business Online?</h2>
      <p>Let’s build a website that makes your Indiana business stand out and bring in more customers.</p>

      <form action="mailto:professional.websites2026@gmail.com" method="post" enctype="text/plain" style="max-width:500px;margin:40px auto 0;">
        <input type="text" name="Name" placeholder="Your Name" required style="width:100%;padding:14px;margin-bottom:12px;border-radius:10px;border:none;" />
        <input type="email" name="Email" placeholder="Your Email" required style="width:100%;padding:14px;margin-bottom:12px;border-radius:10px;border:none;" />
        <textarea name="Message" placeholder="Tell us about your business" required style="width:100%;padding:14px;margin-bottom:18px;border-radius:10px;border:none;min-height:120px;"></textarea>
        <button class="btn" type="submit">Send Message</button>
      </form>

      <p style="margin-top:30px;">Or contact us directly:</p>
      <a class="btn" href="mailto:professional.websites2026@gmail.com">Email Us</a><br><br>
      <a class="btn" href="tel:7656863641">Call 765‑686‑3641</a>
    </div>
  </div>
</section>

<footer>
  <div class="container">
    <div>
      <h4>Hoosier Web Design</h4>
      <p>Professional websites for Indiana businesses who want real results.</p>
      <p><strong>Phone:</strong> <a href="tel:7656863641">765‑686‑3641</a><br>
      <strong>Email:</strong> <a href="mailto:professional.websites2026@gmail.com">professional.websites2026@gmail.com</a></p>
    </div>
    <div>
      <h4>Services</h4>
      <p>Business Websites<br>Local SEO<br>Website Redesigns</p>
    </div>
    <div>
      <h4>Service Area</h4>
      <p>Indianapolis<br>Fort Wayne<br>Bloomington<br>All of Indiana</p>
    </div>
  </div>
</footer>

</body>
</html>
