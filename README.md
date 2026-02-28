<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Essy Haven — Exclusive Style Masterclass</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400;1,600&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --black: #080807;
    --white: #fafaf7;
    --cream: #f5f0e8;
    --gold: #c9a96e;
    --gold-light: #e8d5a3;
    --text-muted: #8a8478;
    --serif: 'Cormorant Garamond', serif;
    --sans: 'DM Sans', sans-serif;
  }
  *,*::before,*::after{margin:0;padding:0;box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{font-family:var(--sans);background:var(--black);color:var(--white);line-height:1.6;overflow-x:hidden;}
  body::before{content:'';position:fixed;inset:0;z-index:0;pointer-events:none;background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");opacity:0.35;}
  .page{position:relative;z-index:1;}
  .top-bar{background:var(--gold);padding:.6rem 1rem;text-align:center;font-size:.75rem;letter-spacing:.2em;text-transform:uppercase;color:var(--black);font-weight:600;animation:pulse-bar 3s ease-in-out infinite;}
  @keyframes pulse-bar{0%,100%{opacity:1}50%{opacity:.85}}
  .hero{position:relative;padding:5rem 1.5rem 4rem;text-align:center;overflow:hidden;}
  .hero::before{content:'';position:absolute;inset:0;background:radial-gradient(ellipse 80% 60% at 50% 0%,rgba(201,169,110,0.12) 0%,transparent 70%),radial-gradient(ellipse 60% 40% at 20% 100%,rgba(201,169,110,0.06) 0%,transparent 60%);}
  .hero-eyebrow{display:inline-flex;align-items:center;gap:.8rem;font-size:.7rem;letter-spacing:.3em;text-transform:uppercase;color:var(--gold);margin-bottom:1.8rem;border:1px solid rgba(201,169,110,.3);padding:.45rem 1.2rem;animation:fadeDown .8s ease both;}
  .hero-eyebrow span{width:18px;height:1px;background:var(--gold);display:block;}
  .hero-headline{font-family:var(--serif);font-size:clamp(2.4rem,7vw,5.5rem);font-weight:300;line-height:1.08;color:var(--white);margin-bottom:1rem;animation:fadeDown .9s .1s ease both;}
  .hero-headline em{font-style:italic;color:var(--gold-light);}
  .hero-headline strong{font-weight:600;}
  .hero-sub{font-family:var(--serif);font-style:italic;font-size:clamp(1.1rem,2.5vw,1.5rem);color:rgba(250,250,247,.55);margin-left:auto;margin-right:auto;margin-bottom:2.5rem;animation:fadeDown .9s .2s ease both;max-width:640px;}
  .event-date{display:inline-flex;align-items:center;gap:.6rem;font-size:.72rem;letter-spacing:.15em;text-transform:uppercase;color:rgba(250,250,247,.45);margin-bottom:2.5rem;animation:fadeDown .9s .35s ease both;}
  .event-dot{width:7px;height:7px;border-radius:50%;background:var(--gold);display:block;animation:blink 1.5s ease-in-out infinite;}
  @keyframes blink{0%,100%{opacity:1}50%{opacity:.3}}
  .countdown-wrap{display:flex;justify-content:center;gap:0;margin-bottom:3rem;animation:fadeDown .9s .3s ease both;}
  .count-block{display:flex;flex-direction:column;align-items:center;padding:1.2rem 1.6rem;border:1px solid rgba(201,169,110,.25);min-width:90px;background:rgba(201,169,110,.04);position:relative;}
  .count-block+.count-block{border-left:none;}
  .count-num{font-family:var(--serif);font-size:3rem;font-weight:300;line-height:1;color:var(--gold);letter-spacing:-.02em;transition:all .3s;}
  .count-label{font-size:.58rem;letter-spacing:.22em;text-transform:uppercase;color:rgba(250,250,247,.35);margin-top:.5rem;}
  .count-sep{font-family:var(--serif);font-size:2.5rem;color:rgba(201,169,110,.3);align-self:center;padding:0 .3rem;line-height:1;}
  .cta-btn{display:inline-block;background:var(--gold);color:var(--black);font-size:.8rem;letter-spacing:.2em;text-transform:uppercase;font-weight:600;font-family:var(--sans);padding:1.15rem 3.5rem;text-decoration:none;border:none;cursor:pointer;position:relative;overflow:hidden;transition:transform .3s,box-shadow .3s;animation:fadeDown .9s .45s ease both;}
  .cta-btn::before{content:'';position:absolute;inset:0;background:linear-gradient(90deg,transparent,rgba(255,255,255,.2),transparent);transform:translateX(-100%);transition:transform .5s;}
  .cta-btn:hover::before{transform:translateX(100%);}
  .cta-btn:hover{transform:translateY(-3px);box-shadow:0 20px 50px rgba(201,169,110,.35);}
  .cta-note{display:block;font-size:.68rem;color:rgba(250,250,247,.3);margin-top:1rem;letter-spacing:.1em;animation:fadeDown .9s .55s ease both;}
  .cta-note strong{color:var(--gold);}
  @keyframes fadeDown{from{opacity:0;transform:translateY(-20px)}to{opacity:1;transform:translateY(0)}}
</style>
</head>
<body>
<div class="page">
  <div class="top-bar">⚡ Limited Spots Available — Exclusive Style Masterclass</div>
  <section class="hero">
    <div class="hero-eyebrow"><span></span>Free Live Training<span></span></div>
    <h1 class="hero-headline">
      Discover How to Build a<br>
      <em>Signature Wardrobe</em> That Commands<br>
      <strong>Respect & Attention</strong>
    </h1>
    <p class="hero-sub">Even if you've never known your personal style — or think fashion is too expensive.</p>
    <div class="event-date">
      <span class="event-dot"></span>
      Live Masterclass · Saturday, March 15, 2026
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
    <a href="#register" class="cta-btn">Reserve My Free Spot</a>
    <span class="cta-note">No credit card required · <strong>100% Free</strong> · Only 50 spots left</span>
  </section>
</div>

<script>
// Countdown timer
const countdownDate = new Date("March 15, 2026 10:00:00").getTime();
const cdDays = document.getElementById('cd-days');
const cdHours = document.getElementById('cd-hours');
const cdMins = document.getElementById('cd-mins');
const cdSecs = document.getElementById('cd-secs');

setInterval(() => {
  const now = new Date().getTime();
  const distance = countdownDate - now;

  if(distance < 0) return;

  const days = Math.floor(distance / (1000*60*60*24));
  const hours = Math.floor((distance % (1000*60*60*24)) / (1000*60*60));
  const mins = Math.floor((distance % (1000*60*60)) / (1000*60));
  const secs = Math.floor((distance % (1000*60)) / 1000);

  cdDays.innerText = days.toString().padStart(2,'0');
  cdHours.innerText = hours.toString().padStart(2,'0');
  cdMins.innerText = mins.toString().padStart(2,'0');
  cdSecs.innerText = secs.toString().padStart(2,'0');
}, 1000);
</script>
</body>
</html>
