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
    --gold: #c9a96e;
    --gold-light: #e8d5a3;
    --serif: 'Cormorant Garamond', serif;
    --sans: 'DM Sans', sans-serif;
  }
  *, *::before, *::after { margin:0; padding:0; box-sizing:border-box; }
  html { scroll-behavior: smooth; }
  body { font-family: var(--sans); background: var(--black); color: var(--white); line-height:1.6; overflow-x:hidden; }
  .page { position: relative; z-index:1; }

  .top-bar { background: var(--gold); padding:0.6rem 1rem; text-align:center; font-size:0.75rem; text-transform:uppercase; font-weight:600; color: var(--black); }

  .hero { padding:3rem 1.5rem; text-align:center; }
  .hero h1 { font-family: var(--serif); font-size:2.4rem; line-height:1.1; margin-bottom:1rem; }
  .hero h1 em { color: var(--gold-light); font-style:italic; }
  .hero p { margin-bottom:2rem; color: rgba(250,250,247,0.7); }

  .countdown { display:flex; justify-content:center; gap:1rem; margin-bottom:2rem; font-family: var(--serif); }
  .count-block { text-align:center; padding:1rem; border:1px solid rgba(201,169,110,0.25); min-width:60px; }
  .count-num { font-size:2rem; color: var(--gold); }
  .count-label { font-size:0.7rem; color: rgba(250,250,247,0.5); margin-top:0.2rem; display:block; }

  .cta-btn { display:inline-block; background:var(--gold); color:var(--black); text-transform:uppercase; font-weight:600; padding:1rem 2rem; text-decoration:none; border-radius:4px; margin-bottom:1rem; }
  .cta-note { display:block; font-size:0.7rem; color: rgba(250,250,247,0.5); }

  /* Simple Sections */
  .section { max-width:900px; margin:4rem auto; padding:0 1.5rem; }
  .section h2 { font-family: var(--serif); font-size:1.8rem; margin-bottom:1rem; }
  .section p { color: rgba(250,250,247,0.7); margin-bottom:1rem; }
  .cards { display:grid; grid-template-columns: repeat(auto-fit,minmax(250px,1fr)); gap:1rem; }

  .card { border:1px solid rgba(201,169,110,0.25); padding:1.5rem; background: rgba(201,169,110,0.03); border-radius:6px; }
</style>
</head>
<body>
<div class="page">

  <!-- TOP BAR -->
  <div class="top-bar">⚡ Limited Spots Available — Exclusive Style Masterclass</div>

  <!-- HERO -->
  <section class="hero">
    <h1>Discover How to Build a <em>Signature Wardrobe</em> That Commands <strong>Respect & Attention</strong></h1>
    <p>Even if you've never known your personal style — or think fashion is too expensive.</p>

    <!-- Countdown -->
    <div class="countdown">
      <div class="count-block"><span class="count-num" id="days">00</span><span class="count-label">Days</span></div>
      <div class="count-block"><span class="count-num" id="hours">00</span><span class="count-label">Hours</span></div>
      <div class="count-block"><span class="count-num" id="minutes">00</span><span class="count-label">Mins</span></div>
      <div class="count-block"><span class="count-num" id="seconds">00</span><span class="count-label">Secs</span></div>
    </div>

    <a href="#register" class="cta-btn">Reserve My Free Spot</a>
    <span class="cta-note">No credit card required · <strong>100% Free</strong></span>
  </section>

  <!-- FOR YOU -->
  <section class="section">
    <h2>This Masterclass is for You If…</h2>
    <div class="cards">
      <div class="card"><strong>Lost in your wardrobe:</strong> You own clothes but still feel like you have nothing to wear.</div>
      <div class="card"><strong>Look expensive on a budget:</strong> Learn to look luxurious without spending a fortune.</div>
      <div class="card"><strong>Command respect:</strong> Make your style speak before you do.</div>
      <div class="card"><strong>Ready for transformation:</strong> Build a curated wardrobe that reflects you.</div>
    </div>
  </section>

</div>

<script>
// Set the countdown date
const targetDate = new Date();
targetDate.setDate(targetDate.getDate() + 5); // 5 days from now
function updateCountdown() {
  const now = new Date();
  const diff = targetDate - now;
  if(diff < 0) return;
  const days = Math.floor(diff / (1000*60*60*24));
  const hours = Math.floor((diff / (1000*60*60)) % 24);
  const minutes = Math.floor((diff / (1000*60)) % 60);
  const seconds = Math.floor((diff / 1000) % 60);
  document.getElementById("days").textContent = String(days).padStart(2,'0');
  document.getElementById("hours").textContent = String(hours).padStart(2,'0');
  document.getElementById("minutes").textContent = String(minutes).padStart(2,'0');
  document.getElementById("seconds").textContent = String(seconds).padStart(2,'0');
}
setInterval(updateCountdown,1000);
updateCountdown();
</script>
</body>
</html>
