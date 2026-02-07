<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Premium Perfume</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header class="hero">
  <div class="hero-text">
    <h4>Premium</h4>
    <h1>PERFUME</h1>
    <p>Fragrance that defines your presence.</p>
    <a href="tel:+918941072207" class="btn">Call to Order</a>
  </div>

  <div class="hero-img">
    <img src="perfume.png" alt="Premium Perfume">
  </div>
</header>

<section class="features">
  <div class="feature">✨ Long Lasting Fragrance</div>
  <div class="feature">🚚 Free Delivery on First Order</div>
  <div class="feature">💎 Premium Quality</div>
</section>

<section class="cta">
  <h2>Now Available</h2>
  <p>📞 Call: +91 894 107 2207</p>
  <p>📧 Email: roy487639@gmail.com</p>
</section>

<footer>
  <p>© 2026 Premium Perfume. All Rights Reserved.</p>
</footer>

</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Georgia", serif;
}

body {
  background: linear-gradient(135deg, #3b1f14, #7a3e25);
  color: #fff;
}

/* HERO SECTION */
.hero {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-around;
  min-height: 100vh;
  padding: 40px;
}

.hero-text h4 {
  font-style: italic;
  letter-spacing: 2px;
}

.hero-text h1 {
  font-size: 64px;
  margin: 10px 0;
}

.hero-text p {
  font-size: 18px;
  margin-bottom: 25px;
  opacity: 0.9;
}

.btn {
  text-decoration: none;
  background: #d4af37;
  color: #000;
  padding: 12px 30px;
  border-radius: 30px;
  font-weight: bold;
}

.hero-img img {
  max-width: 320px;
  filter: drop-shadow(0 20px 30px rgba(0,0,0,0.6));
}

/* FEATURES */
.features {
  display: flex;
  justify-content: center;
  gap: 30px;
  padding: 40px;
  background: rgba(0,0,0,0.2);
}

.feature {
  background: rgba(255,255,255,0.08);
  padding: 20px 30px;
  border-radius: 20px;
  font-size: 16px;
}

/* CTA */
.cta {
  text-align: center;
  padding: 60px 20px;
}

.cta h2 {
  font-size: 36px;
  margin-bottom: 15px;
}

.cta p {
  font-size: 18px;
  margin: 5px 0;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 20px;
  background: rgba(0,0,0,0.4);
  font-size: 14px;
}

/* MOBILE */
@media (max-width: 768px) {
  .hero-text h1 {
    font-size: 44px;
  }
  .features {
    flex-direction: column;
    align-items: center;
  }
}

