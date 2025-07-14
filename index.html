<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>StudioFlyout – Creative Agency</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Poppins:wght@600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --accent: #f9b416;
      --bg: #181a20;
      --card-bg: rgba(40,44,52,0.75);
      --glass-blur: 18px;
      --nav-bg: rgba(30,33,41,0.7);
      --shadow: 0 8px 32px 0 rgba(0,0,0,0.20);
      --radius: 18px;
      --text: #f6f6f9;
      --muted: #9596a1;
      --card-border: 1.5px solid rgba(255,255,255,0.09);
    }
    * { box-sizing: border-box; }
    body {
      margin: 0; font-family: 'Inter', 'Poppins', sans-serif;
      background: var(--bg);
      color: var(--text);
      min-height: 100vh;
      overflow-x: hidden;
    }
    header {
      position: sticky; top: 0; z-index: 99;
      background: var(--nav-bg);
      backdrop-filter: blur(var(--glass-blur));
      box-shadow: var(--shadow);
    }
    .navbar {
      display: flex; align-items: center; justify-content: space-between;
      max-width: 1200px; margin: 0 auto; padding: 1rem 2rem;
    }
    .logo {
      font-family: 'Poppins', sans-serif;
      font-size: 2rem;
      font-weight: 700;
      letter-spacing: 1px;
      color: var(--accent);
      text-shadow: 0 2px 14px rgba(249,180,22,0.15);
      user-select: none;
    }
    nav {
      display: flex; gap: 2rem;
    }
    nav button {
      background: none;
      border: none;
      color: var(--text);
      font-family: 'Inter', sans-serif;
      font-size: 1.08rem;
      padding: 0.5rem 1rem;
      border-radius: var(--radius);
      cursor: pointer;
      transition: background 0.2s, color 0.2s, box-shadow 0.2s, transform 0.18s;
      box-shadow: 0 0 0 0 transparent;
      position: relative;
      z-index: 1;
    }
    nav button.active, nav button:hover {
      background: linear-gradient(90deg, var(--accent) 0%, #f4c96c 100%);
      color: #1a1816;
      box-shadow: 0 4px 16px 0 rgba(249,180,22,0.18);
      transform: translateY(-2px) scale(1.08);
    }
    main {
      max-width: 1100px;
      margin: 0 auto;
      padding: 2.5rem 1rem 1.5rem 1rem;
      min-height: 70vh;
      position: relative;
    }
    section {
      opacity: 0;
      pointer-events: none;
      position: absolute;
      top: 0; left: 0; width: 100%;
      transition: opacity 0.7s cubic-bezier(.7,.2,.3,1), transform 0.7s cubic-bezier(.6,.4,.2,1);
      transform: translateY(40px) scale(0.97);
      will-change: opacity, transform;
    }
    section.active {
      opacity: 1;
      pointer-events: auto;
      position: relative;
      transform: translateY(0px) scale(1);
      z-index: 2;
    }

    /* Home Section */
    .home-headline {
      font-size: 2.5rem;
      font-family: 'Poppins', sans-serif;
      font-weight: 700;
      color: var(--accent);
      margin-bottom: 0.6rem;
      letter-spacing: .5px;
      text-shadow: 0 2px 18px rgba(249,180,22,0.09);
      animation: fade-in-down 1.2s cubic-bezier(.6,.4,.2,1);
    }
    .home-intro {
      font-size: 1.18rem;
      color: var(--muted);
      margin-bottom: 2.2rem;
      max-width: 560px;
      line-height: 1.6;
      animation: fade-in-up 1.3s cubic-bezier(.6,.4,.2,1);
    }
    .sample-gallery {
      display: flex; flex-wrap: wrap; gap: 1.5rem;
      margin-top: .8rem;
    }
    .sample-img {
      width: 120px; height: 120px;
      border-radius: 16px;
      background: linear-gradient(135deg, #23262f 60%, var(--accent) 120%);
      box-shadow: 0 4px 24px 0 rgba(249,180,22,0.13), var(--shadow);
      display: flex; align-items: center; justify-content: center;
      overflow: hidden; position: relative;
      transition: transform 0.25s cubic-bezier(.5,.2,.3,1), box-shadow 0.18s;
      cursor: pointer;
      border: var(--card-border);
      animation: fade-in-gallery 1.2s cubic-bezier(.6,.4,.2,1);
    }
    .sample-img img {
      width: 90px; height: 90px; object-fit: contain;
      border-radius: 12px;
      filter: drop-shadow(0 0 6px #f9b41633);
      transition: transform 0.23s, filter 0.19s;
    }
    .sample-img:hover {
      transform: scale(1.09) rotate(-2deg);
      box-shadow: 0 8px 32px 0 rgba(249,180,22,0.23), var(--shadow);
      background: linear-gradient(135deg, var(--accent) 40%, #23262f 120%);
    }
    .sample-img:hover img {
      transform: scale(1.15) rotate(3deg);
      filter: brightness(1.07) drop-shadow(0 0 12px #f9b41666);
    }

    /* About Section */
    .about-box {
      background: var(--card-bg);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      border: var(--card-border);
      backdrop-filter: blur(var(--glass-blur));
      padding: 2rem 1.5rem 1.5rem 1.5rem;
      margin-top: 1rem;
      font-size: 1.11rem;
      line-height: 1.7;
      color: var(--text);
      max-width: 700px;
      animation: fade-in-up 1s cubic-bezier(.6,.4,.2,1);
    }

    /* Services Section */
    .services-grid {
      display: flex; gap: 2rem; flex-wrap: wrap; justify-content: center;
      margin-top: 1.3rem;
    }
    .service-card {
      background: var(--card-bg);
      border-radius: var(--radius);
      border: var(--card-border);
      box-shadow: 0 8px 32px 0 rgba(249,180,22,0.09), var(--shadow);
      backdrop-filter: blur(var(--glass-blur));
      min-width: 260px; max-width: 320px; flex: 1 1 260px;
      padding: 2rem 1.3rem 1.5rem 1.3rem;
      display: flex; flex-direction: column; align-items: center;
      transition: transform 0.23s cubic-bezier(.5,.2,.3,1), box-shadow 0.24s;
      position: relative;
      overflow: hidden;
      animation: fade-in-up 1.1s cubic-bezier(.6,.4,.2,1);
      perspective: 800px;
    }
    .service-card:hover {
      transform: scale(1.07) rotateY(-8deg) translateY(-6px);
      box-shadow: 0 16px 40px 0 rgba(249,180,22,0.23), var(--shadow);
      background: linear-gradient(120deg, var(--accent) 15%, #23262f 120%);
      color: #181a20;
    }
    .service-icon {
      font-size: 2.6rem;
      margin-bottom: .8rem;
      filter: drop-shadow(0 2px 8px #f9b41655);
      transition: transform .2s, filter .2s;
    }
    .service-card:hover .service-icon {
      transform: scale(1.23) rotate(-8deg);
      filter: brightness(1.13) drop-shadow(0 2px 16px #f9b41688);
    }
    .service-title {
      font-family: 'Poppins', sans-serif;
      font-size: 1.23rem; font-weight: 600;
      margin-bottom: .3rem;
      text-align: center;
      color: var(--accent);
      letter-spacing: .5px;
      transition: color .2s;
    }
    .service-desc {
      font-size: 1rem; color: var(--text);
      text-align: center;
      margin-bottom: 1rem;
      transition: color .2s;
    }
    .service-price {
      font-size: 1.11rem;
      color: var(--accent);
      font-weight: 600;
      background: rgba(249,180,22,0.08);
      border-radius: 8px;
      padding: .35rem .9rem;
      box-shadow: 0 2px 8px 0 rgba(249,180,22,0.07);
      transition: background .17s;
      margin-bottom: .2rem;
    }

    /* Contact Section */
    .contact-box {
      background: var(--card-bg);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      border: var(--card-border);
      backdrop-filter: blur(var(--glass-blur));
      padding: 2rem 1.5rem 1.5rem 1.5rem;
      margin-top: 1.5rem;
      max-width: 440px;
      font-size: 1.12rem;
      color: var(--text);
      animation: fade-in-down .9s cubic-bezier(.6,.4,.2,1);
    }
    .contact-link {
      color: var(--accent);
      text-decoration: none;
      font-weight: 600;
      transition: color .18s;
      word-break: break-all;
    }
    .contact-link:hover {
      color: #ffd26b;
    }
    .contact-social {
      margin-top: .6rem;
      display: flex; gap: .7rem; align-items: center;
    }
    .contact-social span {
      font-size: 1.2rem;
      color: var(--muted);
    }

    /* Fade/Slide Animations */
    @keyframes fade-in-down {
      0% { opacity: 0; transform: translateY(-30px);}
      100% { opacity: 1; transform: translateY(0);}
    }
    @keyframes fade-in-up {
      0% { opacity: 0; transform: translateY(30px);}
      100% { opacity: 1; transform: translateY(0);}
    }
    @keyframes fade-in-gallery {
      0% { opacity: 0; transform: scale(.8);}
      100% { opacity: 1; transform: scale(1);}
    }

    /* Responsive */
    @media (max-width: 900px) {
      .navbar { padding: 1rem 1rem; }
      main { padding: 2rem .5rem 1rem .5rem; }
      .services-grid { gap: 1rem; }
      .service-card { min-width: 220px; max-width: 100%; }
      .sample-gallery { gap: 1rem; }
    }
    @media (max-width: 600px) {
      .navbar { flex-direction: column; gap: .5rem;}
      .logo { font-size: 1.6rem;}
      nav { gap: 1rem;}
      main { padding: 1.2rem .2rem 1rem .2rem; }
      .home-headline { font-size: 1.45rem;}
      .sample-gallery { justify-content: flex-start;}
      .services-grid { flex-direction: column; gap: 1.3rem;}
      .about-box, .contact-box { padding: 1.2rem .5rem; font-size: 1rem;}
    }
  </style>
</head>
<body>
  <header>
    <div class="navbar">
      <span class="logo">StudioFlyout</span>
      <nav>
        <button class="active" onclick="showSection('home')">Home</button>
        <button onclick="showSection('about')">About</button>
        <button onclick="showSection('services')">Services</button>
        <button onclick="showSection('contact')">Contact</button>
      </nav>
    </div>
  </header>
  <main>
    <!-- Home -->
    <section id="home" class="active">
      <div class="home-headline">Welcome to StudioFlyout</div>
      <div class="home-intro">
        Elevate your brand and content! We craft high-impact visuals and edits for YouTubers, influencers, and startups. 
        Let your creative work fly out and stand out.
      </div>
      <div class="sample-gallery">
        <div class="sample-img" title="Sample Thumbnail">
          <img src="https://via.placeholder.com/90x90.png?text=YT+Thumb" alt="Sample Thumbnail">
        </div>
        <div class="sample-img" title="Sample Logo">
          <img src="https://via.placeholder.com/90x90.png?text=Logo" alt="Sample Logo">
        </div>
        <div class="sample-img" title="Sample Reels">
          <img src="https://via.placeholder.com/90x90.png?text=Reel+Edit" alt="Sample Short Edit">
        </div>
        <div class="sample-img" title="Sample Branding">
          <img src="https://via.placeholder.com/90x90.png?text=Brand+Kit" alt="Sample Branding">
        </div>
      </div>
    </section>

    <!-- About -->
    <section id="about">
      <div class="about-box">
        <strong>StudioFlyout</strong> is a creative agency dedicated to helping digital creators, startups, and entrepreneurs amplify their online presence. Our mission is to deliver clean, modern, and impactful creative assets — from dynamic video edits to eye-catching branding kits — so you can focus on growth and storytelling. If you’re a YouTuber, influencer, or startup founder seeking professional visuals and edits, StudioFlyout is your creative partner.
      </div>
    </section>

    <!-- Services -->
    <section id="services">
      <div class="services-grid">
        <div class="service-card">
          <div class="service-icon">🎬</div>
          <div class="service-title">Short-form Video Editing</div>
          <div class="service-desc">Crisp, engaging edits for Reels, Shorts, and TikTok. Fast turnaround for viral impact.</div>
          <div class="service-price">₹999 / video</div>
        </div>
        <div class="service-card">
          <div class="service-icon">🖼</div>
          <div class="service-title">Custom Thumbnail Design</div>
          <div class="service-desc">Attention-grabbing thumbnails for YouTube and more. Designed to boost clicks and engagement.</div>
          <div class="service-price">₹299 / design</div>
        </div>
        <div class="service-card">
          <div class="service-icon">🚀</div>
          <div class="service-title">Branding Kit</div>
          <div class="service-desc">Complete brand package — logo, colors, fonts, templates. Everything you need to launch and grow.</div>
          <div class="service-price">₹1499 / package</div>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact">
      <div class="contact-box">
        <div><strong>Email:</strong>
          <a class="contact-link" href="mailto:studioflyout@gmail.com">studioflyout@gmail.com</a>
        </div>
        <div class="contact-social">
          <span style="font-size:1.3em;">&#x1F4F7;</span>
          <span><strong>Instagram:</strong>
            <a class="contact-link" href="https://instagram.com/studioflyout" target="_blank">@studioflyout</a>
          </span>
        </div>
      </div>
    </section>
  </main>
  <script>
    // Section navigation with fade/slide animation
    function showSection(id) {
      // Navbar button active state
      document.querySelectorAll('nav button').forEach(btn => btn.classList.remove('active'));
      let btnIndex = {home:0,about:1,services:2,contact:3}[id] || 0;
      document.querySelectorAll('nav button')[btnIndex].classList.add('active');
      // Sections animation
      document.querySelectorAll('main > section').forEach(sec => {
        if (sec.id === id) {
          sec.classList.add('active');
        } else {
          sec.classList.remove('active');
        }
      });
      // Scroll to top (for mobile UX)
      window.scrollTo({top:0,behavior:'smooth'});
    }
    // Animate button ripple effect
    document.querySelectorAll('nav button').forEach(btn => {
      btn.addEventListener('click', function(e){
        let ripple = document.createElement('span');
        ripple.style.position = 'absolute';
        ripple.style.left = (e.offsetX-12)+'px';
        ripple.style.top = (e.offsetY-12)+'px';
        ripple.style.width = ripple.style.height = '24px';
        ripple.style.borderRadius = '50%';
        ripple.style.background = 'rgba(249,180,22,0.17)';
        ripple.style.pointerEvents = 'none';
        ripple.style.zIndex = '0';
        ripple.style.animation = 'ripple-anim .5s linear';
        this.appendChild(ripple);
        setTimeout(()=>ripple.remove(), 500);
      });
    });
    // Ripple animation
    const rippleAnim = document.createElement('style');
    rippleAnim.textContent = `
      @keyframes ripple-anim {
        0% { transform: scale(0.2); opacity: 0.55;}
        70% { transform: scale(2.2); opacity: 0.24;}
        100% { transform: scale(2.8); opacity: 0;}
      }
    `;
    document.head.appendChild(rippleAnim);
  </script>
</body>
</html>
