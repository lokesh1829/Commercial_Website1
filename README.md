# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TopTech — Sound Built Different</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Archivo+Black&family=Space+Grotesk:wght@400;500;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<link rel="stylesheet" href="style.css">
</head>
<body>

<div class="noise-overlay"></div>

<!-- NAV -->
<header class="nav">
  <div class="nav-inner">
    <a href="#top" class="logo">TOP<span>TECH</span></a>
    <input type="checkbox" id="menuCheck" class="menu-check">
    <nav class="nav-links">
      <a href="#products">Products</a>
      <a href="#specs">Spec Sheet</a>
      <a href="#reviews">Reviews</a>
      <a href="#footer">Support</a>
    </nav>
    <label for="menuCheck" class="menu-toggle" aria-label="Toggle menu">
      <span></span><span></span><span></span>
    </label>
    <a href="#products" class="nav-cta">Shop Now</a>
  </div>
</header>

<!-- HERO -->
<section class="hero" id="top">
  <div class="eq-field" aria-hidden="true">
    <div class="eq-bars">
      <span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span>
      <span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span>
      <span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span>
      <span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span>
    </div>
  </div>
  <div class="hero-inner">
    <p class="eyebrow">// AUDIO GEAR FOR THE LOUD-MINDED</p>
    <h1 class="hero-title">TURN IT<br>UP TO<br><span class="outline">FULL</span></h1>
    <p class="hero-sub">TopTech makes earbuds, headphones and speakers engineered around one number: how it feels at max volume. 40hr battery. Deep bass tuning. Prices that don't punish you.</p>
    <div class="hero-actions">
      <a href="#products" class="btn btn-primary">Browse the lineup</a>
      <a href="#specs" class="btn btn-ghost">Read the spec sheet ↓</a>
    </div>
    <div class="hero-stats">
      <div class="stat"><span class="stat-num">40H</span><span class="stat-label">battery life</span></div>
      <div class="stat"><span class="stat-num">₹999</span><span class="stat-label">starting price</span></div>
      <div class="stat"><span class="stat-num">2.1M+</span><span class="stat-label">units sold</span></div>
    </div>
  </div>
</section>

<!-- MARQUEE DIVIDER -->
<div class="marquee">
  <div class="marquee-track">
    <span>BASS BOOSTED</span><span>•</span><span>ENC MIC</span><span>•</span><span>IPX5 RATED</span><span>•</span><span>40HR ANC</span><span>•</span><span>LOW LATENCY</span><span>•</span>
    <span>BASS BOOSTED</span><span>•</span><span>ENC MIC</span><span>•</span><span>IPX5 RATED</span><span>•</span><span>40HR ANC</span><span>•</span><span>LOW LATENCY</span><span>•</span>
  </div>
</div>

<!-- PRODUCTS -->
<section class="products" id="products">
  <div class="section-head">
    <h2>THE LINEUP</h2>
    <p>Three ways to listen loud.</p>
  </div>
  <div class="product-grid">

    <article class="product-card">
      <div class="card-visual"><div class="bud"></div></div>
      <h3>Airdopes Rumble</h3>
      <p class="card-desc">True wireless earbuds with 13mm drivers tuned for bass-heavy tracks. ENC mic keeps calls clean on the street.</p>
      <div class="card-specs">
        <span>35H</span><span>IPX5</span><span>ENC</span>
      </div>
      <div class="card-foot">
        <span class="price">₹1,299</span>
        <a href="#" class="card-link">View →</a>
      </div>
    </article>

    <article class="product-card featured">
      <div class="ribbon">BEST SELLER</div>
      <div class="card-visual"><div class="headphone"></div></div>
      <h3>Rockerz 750 ANC</h3>
      <p class="card-desc">Over-ear ANC headphones built for commutes and studio sessions alike. 40hr battery, foldable frame.</p>
      <div class="card-specs">
        <span>40H</span><span>ANC</span><span>40mm</span>
      </div>
      <div class="card-foot">
        <span class="price">₹2,499</span>
        <a href="#" class="card-link">View →</a>
      </div>
    </article>

    <article class="product-card">
      <div class="card-visual"><div class="speaker"></div></div>
      <h3>Stone Blast 2</h3>
      <p class="card-desc">Portable Bluetooth speaker with RGB pulse lighting and 12hr playback. Party-ready, backyard-proof.</p>
      <div class="card-specs">
        <span>12H</span><span>IPX7</span><span>TWS</span>
      </div>
      <div class="card-foot">
        <span class="price">₹1,799</span>
        <a href="#" class="card-link">View →</a>
      </div>
    </article>

  </div>
</section>

<!-- SPEC SHEET -->
<section class="specs" id="specs">
  <div class="section-head light">
    <h2>SPEC SHEET</h2>
    <p>No marketing fluff. Just the numbers.</p>
  </div>
  <div class="spec-table">
    <div class="spec-row spec-row-head">
      <span>MODEL</span><span>DRIVER</span><span>BATTERY</span><span>CHARGE TIME</span><span>WEIGHT</span>
    </div>
    <div class="spec-row">
      <span>Airdopes Rumble</span><span>13mm</span><span>35 hrs</span><span>1.5 hrs</span><span>4.2g / bud</span>
    </div>
    <div class="spec-row">
      <span>Rockerz 750 ANC</span><span>40mm</span><span>40 hrs</span><span>2 hrs</span><span>230g</span>
    </div>
    <div class="spec-row">
      <span>Stone Blast 2</span><span>2x 45mm</span><span>12 hrs</span><span>2.5 hrs</span><span>620g</span>
    </div>
  </div>
</section>

<!-- REVIEWS -->
<section class="reviews" id="reviews">
  <div class="section-head">
    <h2>WHAT PEOPLE ARE SAYING</h2>
  </div>
  <div class="review-grid">
    <blockquote class="review-card">
      <p>"Bass on the Rumble hits harder than earbuds twice the price. ENC actually works on my scooter commute."</p>
      <cite>— Ananya R., Verified Buyer</cite>
    </blockquote>
    <blockquote class="review-card">
      <p>"Wore the Rockerz through a 9 hour flight, ANC held up the whole way and it still had juice left."</p>
      <cite>— Karthik S., Verified Buyer</cite>
    </blockquote>
    <blockquote class="review-card">
      <p>"Stone Blast 2 survived a monsoon on my terrace. Genuinely didn't expect that from the IPX7 rating."</p>
      <cite>— Meera D., Verified Buyer</cite>
    </blockquote>
  </div>
</section>

<!-- CTA -->
<section class="cta-band">
  <h2>YOUR NEXT UPGRADE<br>IS ONE TAP AWAY.</h2>
  <a href="#products" class="btn btn-primary large">Shop the lineup</a>
</section>

<!-- FOOTER -->
<footer class="footer" id="footer">
  <div class="footer-top">
    <a href="#top" class="logo">TOP<span>TECH</span></a>
    <div class="footer-cols">
      <div class="footer-col">
        <h4>Shop</h4>
        <a href="#">Earbuds</a>
        <a href="#">Headphones</a>
        <a href="#">Speakers</a>
      </div>
      <div class="footer-col">
        <h4>Support</h4>
        <a href="#">Warranty</a>
        <a href="#">Track Order</a>
        <a href="#">Contact Us</a>
      </div>
      <div class="footer-col">
        <h4>Company</h4>
        <a href="#">Aboutt</a>
        <a href="#">Careers</a>
        <a href="#">Press</a>
      </div>
    </div>
  </div>
  <div class="footer-bottom">
    <p>© 2026 TopTech Audio Pvt. Ltd. All rights reserved.</p>
    <p>Made loud in India .</p>
  </div>
</footer>

</body>
</html>

## OUTPUT
![alt text](<../Desktop/app develop/image.png>)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
