<!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Copy That Converts — Free Masterclass</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400;1,600&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --black: #080807;
    --white: #fafaf7;
    --cream: #f5f0e8;
    --gold: #c9a96e;
    --gold-light: #e8d5a3;
    --gold-dark: #9a7a47;
    --gold-glow: rgba(201,169,110,0.18);
    --text-muted: #8a8478;
    --serif: 'Cormorant Garamond', serif;
    --sans: 'DM Sans', sans-serif;
  }*, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; } html { scroll-behavior: smooth; } body { font-family: var(--sans); background: var(--black); color: var(--white); overflow-x: hidden; line-height: 1.6; } body::before { content: ''; position: fixed; inset: 0; z-index: 0; pointer-events: none; background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E"); opacity: 0.35; } .page { position: relative; z-index: 1; }

.top-bar { background: var(--gold); padding: 0.6rem 1rem; text-align: center; font-size: 0.75rem; letter-spacing: 0.2em; text-transform: uppercase; color: var(--black); font-weight: 600; animation: pulse-bar 3s ease-in-out infinite; } @keyframes pulse-bar { 0%,100%{opacity:1;}50%{opacity:0.85;} }

.hero { position: relative; padding: 5rem 1.5rem 4rem; text-align: center; overflow: hidden; } .hero::before { content: ''; position: absolute; inset: 0; background: radial-gradient(ellipse 80% 60% at 50% 0%, rgba(201,169,110,0.12) 0%, transparent 70%), radial-gradient(ellipse 60% 40% at 20% 100%, rgba(201,169,110,0.06) 0%, transparent 60%); } .hero-eyebrow { display: inline-flex; align-items: center; gap: 0.8rem; font-size: 0.7rem; letter-spacing: 0.3em; text-transform: uppercase; color: var(--gold); margin-bottom: 1.8rem; border: 1px solid rgba(201,169,110,0.3); padding: 0.45rem 1.2rem; animation: fadeDown 0.8s ease both; } .hero-eyebrow span { width: 18px; height: 1px; background: var(--gold); display: block; } .hero-headline { font-family: var(--serif); font-size: clamp(2.4rem, 7vw, 5.5rem); font-weight: 300; line-height: 1.08; color: var(--white); margin-bottom: 1rem; animation: fadeDown 0.9s 0.1s ease both; } .hero-headline em { font-style: italic; color: var(--gold-light); } .hero-headline strong { font-weight: 600; } .hero-sub { font-family: var(--serif); font-style: italic; font-size: clamp(1.1rem, 2.5vw, 1.5rem); color: rgba(250,250,247,0.55); margin-bottom: 2.5rem; max-width: 640px; margin-left: auto; margin-right: auto; animation: fadeDown 0.9s 0.2s ease both; }

.event-date { display: inline-flex; align-items: center; gap: 0.6rem; font-size: 0.72rem; letter-spacing: 0.15em; text-transform: uppercase; color: rgba(250,250,247,0.45); margin-bottom: 2.5rem; animation: fadeDown 0.9s 0.35s ease both; } .event-dot { width: 7px; height: 7px; border-radius: 50%; background: var(--gold); display: block; animation: blink 1.5s ease-in-out infinite; } @keyframes blink { 0%,100%{opacity:1;}50%{opacity:0.3;} }

.countdown-wrap { display: flex; justify-content: center; gap:0; margin-bottom: 3rem; animation: fadeDown 0.9s 0.3s ease both; } .count-block { display: flex; flex-direction: column; align-items: center; padding: 1.2rem 1.6rem; border: 1px solid rgba(201,169,110,0.25); min-width: 90px; background: rgba(201,169,110,0.04); position: relative; } .count-block + .count-block { border-left: none; } .count-num { font-family: var(--serif); font-size: 3rem; font-weight: 300; line-height: 1; color: var(--gold); letter-spacing: -0.02em; transition: all 0.3s; } .count-label { font-size: 0.58rem; letter-spacing: 0.22em; text-transform: uppercase; color: rgba(250,250,247,0.35); margin-top: 0.5rem; } .count-sep { font-family: var(--serif); font-size: 2.5rem; color: rgba(201,169,110,0.3); align-self: center; padding: 0 0.3rem; line-height: 1; }

.cta-btn { display:inline-block; background:var(--gold); color:var(--black); font-size:0.8rem; letter-spacing:0.2em; text-transform:uppercase; font-weight:600; font-family:var(--sans); padding:1.15rem 3.5rem; text-decoration:none; border:none; cursor:pointer; position:relative; overflow:hidden; transition:transform 0.3s, box-shadow 0.3s; animation:fadeDown 0.9s 0.45s ease both; } .cta-btn::before { content: ''; position:absolute; inset:0; background:linear-gradient(90deg,transparent,rgba(255,255,255,0.2),transparent); transform:translateX(-100%); transition: transform 0.5s; } .cta-btn:hover::before { transform:translateX(100%); } .cta-btn:hover { transform:translateY(-3px); box-shadow:0 20px 50px rgba(201,169,110,0.35); } .cta-note { display:block; font-size:0.68rem; color:rgba(250,250,247,0.3); margin-top:1rem; letter-spacing:0.1em; animation:fadeDown 0.9s 0.55s ease both; } .cta-note strong { color:var(--gold); }

.host-section { max-width:820px; margin:0 auto; padding:0 1.5rem 5rem; display:grid; grid-template-columns:1fr 1.6fr; gap:4rem; align-items:center; } .host-img-wrap { position:relative; } .host-img-wrap::before { content:''; position:absolute; inset:-12px; border:1px solid rgba(201,169,110,0.2); transform:rotate(2deg); } .host-img-wrap::after { content:''; position:absolute; inset:-24px; border:1px solid rgba(201,169,110,0.08); transform:rotate(-1deg); } .host-img { width:100%; aspect-ratio:3/4; object-fit:cover; filter:grayscale(20%) contrast(1.05); display:block; position:relative; z-index:1; } .host-label { font-size:0.65rem; letter-spacing:0.3em; text-transform:uppercase; color:var(--gold); margin-bottom:0.8rem; } .host-name { font-family:var(--serif); font-size:clamp(2rem,4vw,3rem); font-weight:300; line-height:1.1; margin-bottom:0.4rem; } .host-title { font-family:var(--serif); font-style:italic; font-size:1.05rem; color:rgba(250,250,247,0.45); margin-bottom:1.8rem; } .host-bio { font-size:0.9rem; color:rgba(250,250,247,0.6); line-height:1.85; } .host-stats { display:flex; gap:2rem; margin-top:2rem; border-top:1px solid rgba(201,169,110,0.15); padding-top:1.8rem; } .host-stat-num { font-family:var(--serif); font-size:2rem; font-weight:300; color:var(--gold); line-height:1; } .host-stat-label { font-size:0.7rem; color:rgba(250,250,247,0.35); letter-spacing:0.1em; text-transform:uppercase; margin-top:0.3rem; }

.reveal { opacity:0; transform:translateY(30px); transition: opacity 0.8s ease, transform 0.8s ease; } .reveal.visible { opacity:1; transform:translateY(0); }

@media(max-width:700px){.host-section{grid-template-columns:1fr; gap:2.5rem;}.host-img-wrap{max-width:280px;margin:0 auto;}.count-block{min-width:65px;padding:1rem;}.count-num{font-size:2.2rem;}.host-stats{gap:1.2rem;}} </style>

</head>
<body>
<div class="page">  <div class="top-bar">⚡ Limited Spots — Copy That Converts Masterclass</div>  <section class="hero">
    <div class="hero-eyebrow"><span></span>Free Masterclass<span></span></div>
    <h1 class="hero-headline">Copywriting Skills That<br><em>Sell Your Ideas</em> & Command Attention</h1>
    <p class="hero-sub">Learn the psychology behind persuasive copy, email sequences, and headlines that convert — even if you’ve never written professionally.</p><div class="event-date">
  <span class="event-dot"></span>
  Live Masterclass · Saturday, March 15, 2025
</div>
<div class="countdown-wrap">
  <div class="count-block"><span class="count-num" id="cd-days">00</span><span class="count-label">Days</span></div>
  <span class="count-sep">:</span>
  <div class="count-block"><span class="count-num" id="cd-hours">00</span><span class="count-label">Hours</span></div>
  <span class="count-sep">:</span>
  <div class="count-block"><span class="count-num" id="cd-mins">00</span><span class="count-label">Mins</span></div>
  <span class="count-sep">:</span>
  <div class="count-block"><span class="count-num" id="cd-secs">00</span><span class="count-label">Secs</span></div>
</div>

<a href="https://chat.whatsapp.com/CVBw3kRrwtDIrJWW0JMWhN?mode=gi_t" class="cta-btn">Join Now on WhatsApp</a>
<span class="cta-note">No credit card required · <strong>100% Free</strong></span>

  </section>  <!-- HOST -->  <div class="host-section reveal">
    <div class="host-img-wrap">
      <img src="ola" alt="Olayinka Ashaye" class="host-img" />
    </div>
    <div class="host-info">
      <p class="host-label">Your Host</p>
      <h2 class="host-name">Olayinka Ashaye</h2>
      <p class="host-title">Copywriting Coach · Persuasion Expert</p>
      <p class="host-bio">Olayinka has trained hundreds of marketers and entrepreneurs, helping them craft copy that converts. She’s passionate about making persuasive writing simple and actionable for everyone.</p>
      <div class="host-stats">
        <div><div class="host-stat-num">500+</div><div class="host-stat-label">Students Trained</div></div>
        <div><div class="host-stat-num">7 Yrs</div><div class="host-stat-label">Experience</div></div>
        <div><div class="host-stat-num">95%</div><div class="host-stat-label">Success Rate</div></div>
      </div>
    </div>
  </div>  <!-- Countdown Script -->  <script>
    const endDate = new Date('March 15, 2025 12:00:00').getTime();
    const daysEl = document.getElementById('cd-days');
    const hoursEl = document.getElementById('cd-hours');
    const minsEl = document.getElementById('cd-mins');
    const secsEl = document.getElementById('cd-secs');

    function updateCountdown() {
      const now = new Date().getTime();
      const distance = endDate - now;
      if(distance < 0){daysEl.innerHTML='00'; hoursEl.innerHTML='00'; minsEl.innerHTML='00'; secsEl.innerHTML='00'; return;}
      const days = Math.floor(distance / (1000*60*60*24));
      const hours = Math.floor((distance % (1000*60*60*24))/(1000*60*60));
      const mins = Math.floor((distance % (1000*60*60))/(1000*60));
      const secs = Math.floor((distance % (1000*60))/1000);
      daysEl.innerHTML = String(days).padStart(2,'0');
      hoursEl.innerHTML = String(hours).padStart(2,'0');
      minsEl.innerHTML = String(mins).padStart(2,'0');
      secsEl.innerHTML = String(secs).padStart(2,'0');
    }
    setInterval(updateCountdown, 1000); updateCountdown();
  </script></div>
</body>
</html>
