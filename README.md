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
        <a href="#">About</a>
        <a href="#">Careers</a>
        <a href="#">Press</a>
      </div>
    </div>
  </div>
  <div class="footer-bottom">
    <p>© 2026 TopTech Audio Pvt. Ltd. All rights reserved.</p>
    <p>Made loud in India.</p>
  </div>
</footer>

</body>
</html>

/* ===== TOKENS ===== */
:root{
  --bg: #0B0D10;
  --bg-alt: #14171B;
  --surface: #1B1F24;
  --surface-2: #22262C;
  --text: #F2F0EA;
  --muted: #8A8F98;
  --accent: #D4FF3D;
  --accent-2: #FF3E4D;
  --border: rgba(242,240,234,0.1);

  --font-display: 'Archivo Black', sans-serif;
  --font-body: 'Space Grotesk', sans-serif;
  --font-mono: 'JetBrains Mono', monospace;

  --container: 1180px;
}

*{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{
  background:var(--bg);
  color:var(--text);
  font-family:var(--font-body);
  line-height:1.5;
  overflow-x:hidden;
}
a{color:inherit;text-decoration:none;}
ul{list-style:none;}
img{max-width:100%;display:block;}

@media (prefers-reduced-motion: reduce){
  *{animation-duration:0.01ms !important; animation-iteration-count:1 !important; transition-duration:0.01ms !important; scroll-behavior:auto !important;}
}

/* subtle grain overlay for texture */
.noise-overlay{
  position:fixed;inset:0;pointer-events:none;z-index:999;opacity:0.035;
  background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='120' height='120'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='2' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
}

:focus-visible{
  outline:2px solid var(--accent);
  outline-offset:3px;
}

/* ===== NAV ===== */
.nav{
  position:sticky;top:0;z-index:100;
  background:rgba(11,13,16,0.85);
  backdrop-filter:blur(10px);
  border-bottom:1px solid var(--border);
}
.nav-inner{
  position:relative;
  max-width:var(--container);margin:0 auto;padding:18px 24px;
  display:flex;align-items:center;justify-content:space-between;gap:24px;
}
.logo{
  font-family:var(--font-display);
  font-size:20px;letter-spacing:0.5px;
}
.logo span{color:var(--accent);}
.nav-links{display:flex;gap:32px;font-size:14px;}
.nav-links a{color:var(--muted);transition:color 0.2s;}
.nav-links a:hover{color:var(--text);}
.nav-cta{
  font-family:var(--font-mono);font-size:13px;font-weight:500;
  background:var(--accent);color:var(--bg);
  padding:10px 18px;border-radius:2px;
  transition:transform 0.15s;
}
.nav-cta:hover{transform:translateY(-2px);}
.menu-check{display:none;}
.menu-toggle{display:none;flex-direction:column;gap:5px;cursor:pointer;padding:4px;}
.menu-toggle span{width:22px;height:2px;background:var(--text);display:block;transition:transform 0.2s, opacity 0.2s;}

/* ===== HERO ===== */
.hero{
  position:relative;
  padding:120px 24px 100px;
  overflow:hidden;
  border-bottom:1px solid var(--border);
}
.eq-field{
  position:absolute;inset:0;z-index:0;
  display:flex;align-items:flex-end;justify-content:center;
  opacity:0.5;
  mask-image:linear-gradient(to bottom, transparent, black 60%, transparent);
}
.eq-bars{
  display:flex;gap:6px;align-items:flex-end;height:70%;width:100%;justify-content:center;
}
.eq-bars span{
  width:8px;height:40%;
  background:linear-gradient(to top, var(--accent), transparent 90%);
  border-radius:2px 2px 0 0;
  transform-origin:bottom;
  animation:eq 1.1s ease-in-out infinite;
}
/* vary height, speed and phase per bar so the field doesn't pulse in unison */
.eq-bars span:nth-child(3n+1){height:30%; animation-duration:0.9s;}
.eq-bars span:nth-child(3n+2){height:55%; animation-duration:1.3s;}
.eq-bars span:nth-child(3n){height:75%; animation-duration:1.05s;}
.eq-bars span:nth-child(4n){animation-delay:-0.2s;}
.eq-bars span:nth-child(5n){animation-delay:-0.5s;}
.eq-bars span:nth-child(7n){animation-delay:-0.8s;}
.eq-bars span:nth-child(2n){animation-delay:-1s;}

@keyframes eq{
  0%,100%{transform:scaleY(0.2);}
  50%{transform:scaleY(1);}
}
.hero-inner{
  position:relative;z-index:1;
  max-width:var(--container);margin:0 auto;
}
.eyebrow{
  font-family:var(--font-mono);color:var(--accent);font-size:13px;
  letter-spacing:1px;margin-bottom:24px;
}
.hero-title{
  font-family:var(--font-display);
  font-size:clamp(52px, 10vw, 128px);
  line-height:0.92;
  letter-spacing:-1px;
  margin-bottom:32px;
}
.hero-title .outline{
  -webkit-text-stroke:2px var(--text);
  color:transparent;
}
.hero-sub{
  font-size:18px;color:var(--muted);max-width:520px;margin-bottom:40px;
}
.hero-actions{display:flex;gap:16px;flex-wrap:wrap;margin-bottom:64px;}
.btn{
  font-family:var(--font-mono);font-size:14px;font-weight:500;
  padding:16px 28px;border-radius:2px;display:inline-block;
  transition:transform 0.15s, background 0.15s;
  border:1px solid transparent;
}
.btn-primary{background:var(--accent);color:var(--bg);}
.btn-primary:hover{transform:translateY(-2px);}
.btn-ghost{border-color:var(--border);color:var(--text);}
.btn-ghost:hover{border-color:var(--text);}
.btn.large{padding:20px 40px;font-size:15px;}

.hero-stats{
  display:flex;gap:56px;flex-wrap:wrap;
  border-top:1px solid var(--border);padding-top:32px;
}
.stat{display:flex;flex-direction:column;gap:4px;}
.stat-num{font-family:var(--font-display);font-size:28px;color:var(--accent);}
.stat-label{font-family:var(--font-mono);font-size:12px;color:var(--muted);}

/* ===== MARQUEE ===== */
.marquee{
  background:var(--accent);color:var(--bg);
  overflow:hidden;white-space:nowrap;padding:12px 0;
  border-bottom:1px solid var(--border);
}
.marquee-track{
  display:inline-flex;gap:16px;
  font-family:var(--font-mono);font-size:14px;font-weight:500;
  animation:scroll 22s linear infinite;
}
@keyframes scroll{
  from{transform:translateX(0);}
  to{transform:translateX(-50%);}
}

/* ===== SECTION HEAD ===== */
.section-head{
  max-width:var(--container);margin:0 auto;padding:90px 24px 48px;
}
.section-head h2{
  font-family:var(--font-display);font-size:clamp(32px,5vw,52px);
  letter-spacing:-0.5px;margin-bottom:12px;
}
.section-head p{color:var(--muted);font-size:16px;}
.section-head.light h2{color:var(--bg);}
.section-head.light p{color:rgba(11,13,16,0.65);}

/* ===== PRODUCTS ===== */
.products{padding-bottom:40px;}
.product-grid{
  max-width:var(--container);margin:0 auto;padding:0 24px;
  display:grid;grid-template-columns:repeat(3,1fr);gap:24px;
}
.product-card{
  position:relative;
  background:var(--surface);
  border:1px solid var(--border);
  border-radius:4px;
  padding:32px;
  display:flex;flex-direction:column;gap:16px;
  transition:transform 0.2s, border-color 0.2s;
}
.product-card:hover{transform:translateY(-6px);border-color:var(--accent);}
.product-card.featured{background:var(--surface-2);border-color:var(--accent);}
.ribbon{
  position:absolute;top:20px;right:-32px;
  background:var(--accent-2);color:var(--text);
  font-family:var(--font-mono);font-size:11px;font-weight:500;
  padding:4px 40px;transform:rotate(45deg);
}
.card-visual{
  height:140px;display:flex;align-items:center;justify-content:center;
  background:var(--bg);border-radius:4px;
}
.bud{
  width:44px;height:56px;border-radius:50% 50% 40% 40%;
  background:linear-gradient(160deg, var(--accent), #7a9a1f);
  position:relative;
}
.bud::after{
  content:"";position:absolute;top:-4px;right:6px;width:14px;height:24px;
  background:var(--accent);border-radius:6px;transform:rotate(20deg);
}
.headphone{
  width:90px;height:70px;border:8px solid var(--accent);border-bottom:none;
  border-radius:60px 60px 0 0;position:relative;
}
.headphone::before,.headphone::after{
  content:"";position:absolute;bottom:-14px;width:20px;height:28px;
  background:var(--accent);border-radius:6px;
}
.headphone::before{left:-14px;}
.headphone::after{right:-14px;}
.speaker{
  width:80px;height:80px;border-radius:12px;
  background:var(--surface-2);border:2px solid var(--accent);
  position:relative;
}
.speaker::before{
  content:"";position:absolute;inset:14px;border-radius:50%;
  border:3px solid var(--accent);
}
.speaker::after{
  content:"";position:absolute;inset:30px;border-radius:50%;
  background:var(--accent);
}
.product-card h3{font-family:var(--font-display);font-size:20px;}
.card-desc{color:var(--muted);font-size:14px;flex-grow:1;}
.card-specs{display:flex;gap:8px;flex-wrap:wrap;}
.card-specs span{
  font-family:var(--font-mono);font-size:11px;color:var(--accent);
  border:1px solid var(--border);padding:4px 8px;border-radius:2px;
}
.card-foot{display:flex;align-items:center;justify-content:space-between;padding-top:8px;border-top:1px solid var(--border);}
.price{font-family:var(--font-mono);font-size:16px;font-weight:500;}
.card-link{font-family:var(--font-mono);font-size:13px;color:var(--accent);}

/* ===== SPECS ===== */
.specs{background:var(--accent);color:var(--bg);padding-bottom:80px;}
.spec-table{
  max-width:var(--container);margin:0 auto;padding:0 24px;
  font-family:var(--font-mono);font-size:14px;
}
.spec-row{
  display:grid;grid-template-columns:2fr 1fr 1fr 1fr 1fr;
  padding:16px 0;border-bottom:1px solid rgba(11,13,16,0.2);
}
.spec-row-head{font-weight:700;text-transform:uppercase;font-size:12px;letter-spacing:0.5px;}

/* ===== REVIEWS ===== */
.review-grid{
  max-width:var(--container);margin:0 auto;padding:0 24px 100px;
  display:grid;grid-template-columns:repeat(3,1fr);gap:24px;
}
.review-card{
  background:var(--surface);border:1px solid var(--border);border-radius:4px;
  padding:28px;display:flex;flex-direction:column;gap:16px;
}
.review-card p{font-size:15px;color:var(--text);}
.review-card cite{font-family:var(--font-mono);font-size:12px;color:var(--muted);font-style:normal;}

/* ===== CTA BAND ===== */
.cta-band{
  text-align:center;padding:110px 24px;
  border-top:1px solid var(--border);border-bottom:1px solid var(--border);
}
.cta-band h2{
  font-family:var(--font-display);font-size:clamp(32px,6vw,56px);
  line-height:1.05;margin-bottom:40px;
}

/* ===== FOOTER ===== */
.footer{padding:64px 24px 32px;}
.footer-top{
  max-width:var(--container);margin:0 auto;
  display:flex;justify-content:space-between;flex-wrap:wrap;gap:48px;
  padding-bottom:48px;border-bottom:1px solid var(--border);
}
.footer-cols{display:flex;gap:64px;flex-wrap:wrap;}
.footer-col{display:flex;flex-direction:column;gap:12px;}
.footer-col h4{font-family:var(--font-mono);font-size:12px;color:var(--muted);letter-spacing:0.5px;margin-bottom:4px;}
.footer-col a{font-size:14px;color:var(--text);}
.footer-col a:hover{color:var(--accent);}
.footer-bottom{
  max-width:var(--container);margin:0 auto;padding-top:24px;
  display:flex;justify-content:space-between;flex-wrap:wrap;gap:8px;
  font-family:var(--font-mono);font-size:12px;color:var(--muted);
}

/* ===== RESPONSIVE ===== */
@media (max-width:900px){
  .product-grid{grid-template-columns:1fr;}
  .review-grid{grid-template-columns:1fr;}
  .spec-row{grid-template-columns:1.5fr 1fr 1fr;font-size:12px;}
  .spec-row span:nth-child(4), .spec-row span:nth-child(5){display:none;}
}
@media (max-width:720px){
  .nav-cta{display:none;}
  .menu-toggle{display:flex;}

  .nav-links{
    position:absolute;top:100%;left:0;right:0;
    flex-direction:column;gap:0;
    background:var(--bg-alt);border-bottom:1px solid var(--border);
    max-height:0;overflow:hidden;
    transition:max-height 0.3s ease;
  }
  .nav-links a{padding:16px 24px;border-top:1px solid var(--border);}

  /* checkbox hack: show menu when checked */
  .menu-check:checked ~ .nav-links{max-height:300px;}
  .menu-check:checked ~ .menu-toggle span:nth-child(1){transform:translateY(7px) rotate(45deg);}
  .menu-check:checked ~ .menu-toggle span:nth-child(2){opacity:0;}
  .menu-check:checked ~ .menu-toggle span:nth-child(3){transform:translateY(-7px) rotate(-45deg);}

  .hero{padding:90px 20px 70px;}
  .hero-stats{gap:32px;}
  .footer-top{flex-direction:column;}
}

## OUTPUT
![alt text](<../Desktop/app develop/image.png>)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
