<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Free Copywriting Masterclass — Olayinka Ashaye</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,wght@0,400;0,700;0,900;1,400;1,700;1,900&family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0d0d0d;
    --card: #161616;
    --card2: #1e1e1e;
    --green: #22c55e;
    --green-dark: #16a34a;
    --amber: #f59e0b;
    --red: #ef4444;
    --white: #ffffff;
    --gray: #9ca3af;
    --gray2: #6b7280;
    --border: rgba(255,255,255,0.07);
    --serif: 'Fraunces', serif;
    --sans: 'Plus Jakarta Sans', sans-serif;
  }

  *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }
  html { scroll-behavior: smooth; }
  body {
    font-family: var(--sans);
    background: var(--bg);
    color: var(--white);
    overflow-x: hidden;
    padding-bottom: 100px;
  }

  /* ── LIVE BADGE ── */
  .live-badge {
    display: flex; align-items: center; justify-content: center; gap: 0.6rem;
    background: linear-gradient(90deg, #1a0808, #2d0f0f, #1a0808);
    border-bottom: 1px solid rgba(239,68,68,0.25);
    padding: 0.8rem 1rem;
    font-size: 0.7rem; font-weight: 800; letter-spacing: 0.22em;
    text-transform: uppercase; color: #fca5a5;
  }
  .live-dot {
    width: 8px; height: 8px; border-radius: 50%;
    background: var(--red);
    animation: livePulse 1.5s ease-in-out infinite;
  }
  @keyframes livePulse {
    0%   { box-shadow: 0 0 0 0 rgba(239,68,68,0.8); }
    70%  { box-shadow: 0 0 0 8px rgba(239,68,68,0); }
    100% { box-shadow: 0 0 0 0 rgba(239,68,68,0); }
  }

  /* ── HERO ── */
  .hero {
    padding: 3rem 1.3rem 1.5rem;
    text-align: center;
    position: relative; overflow: hidden;
  }
  .hero::before {
    content: '';
    position: absolute; top: -80px; left: 50%; transform: translateX(-50%);
    width: 600px; height: 350px;
    background: radial-gradient(ellipse, rgba(34,197,94,0.07) 0%, transparent 70%);
    pointer-events: none;
  }

  .hero-headline {
    font-family: var(--serif);
    font-size: clamp(2.1rem, 8.5vw, 3.4rem);
    font-weight: 900; line-height: 1.08;
    color: var(--white); margin-bottom: 1.2rem;
    animation: fadeUp 0.7s ease both;
  }
  .hero-headline .green  { color: var(--green); font-style: italic; }
  .hero-headline .amber  { color: var(--amber); font-style: italic; }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(22px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  .hero-sub {
    font-size: 0.97rem; color: var(--gray); line-height: 1.75;
    max-width: 400px; margin: 0 auto 1.8rem;
    animation: fadeUp 0.7s 0.1s ease both;
  }
  .hero-sub strong { color: var(--green); font-weight: 700; }

  .hero-badges {
    display: flex; justify-content: center; gap: 0.7rem; flex-wrap: wrap;
    margin-bottom: 2.2rem;
    animation: fadeUp 0.7s 0.2s ease both;
  }
  .badge {
    display: inline-flex; align-items: center; gap: 0.45rem;
    background: var(--card); border: 1px solid var(--border);
    border-radius: 999px; padding: 0.5rem 1rem;
    font-size: 0.78rem; color: var(--gray);
  }
  .badge strong { color: var(--white); }

  /* ── REGISTER CARD ── */
  .register-card {
    background: var(--card);
    border: 1px solid rgba(34,197,94,0.2);
    border-radius: 18px;
    padding: 2rem 1.5rem 1.8rem;
    max-width: 460px; margin: 0 auto 3rem;
    position: relative; overflow: hidden;
    animation: fadeUp 0.7s 0.25s ease both;
  }
  .register-card::before {
    content: '';
    position: absolute; top: 0; left: 0; right: 0; height: 2px;
    background: linear-gradient(90deg, transparent, var(--green), transparent);
  }
  .free-label {
    display: flex; align-items: center; gap: 0.4rem;
    font-size: 0.68rem; font-weight: 800; letter-spacing: 0.18em;
    text-transform: uppercase; color: var(--green); margin-bottom: 0.7rem;
  }
  .register-card h2 {
    font-family: var(--serif); font-size: 1.9rem; font-weight: 900;
    line-height: 1.1; margin-bottom: 0.5rem;
  }
  .register-card > p {
    font-size: 0.85rem; color: var(--gray); margin-bottom: 1.6rem; line-height: 1.6;
  }

  .cta-btn {
    display: block; width: 100%;
    background: var(--green); color: #000;
    border: none; border-radius: 12px;
    padding: 1.1rem 1rem;
    font-family: var(--sans); font-size: 0.85rem;
    font-weight: 800; letter-spacing: 0.14em;
    text-transform: uppercase; cursor: pointer;
    text-decoration: none; text-align: center;
    transition: transform 0.25s, box-shadow 0.25s, background 0.25s;
    animation: btnPulse 2.5s ease-in-out infinite;
    line-height: 1.4;
  }
  .cta-btn span { display: block; font-size: 0.72rem; opacity: 0.7; margin-top: 0.15rem; font-weight: 500; letter-spacing: 0.05em; }
  @keyframes btnPulse {
    0%,100% { box-shadow: 0 0 0 0 rgba(34,197,94,0.5); }
    50%      { box-shadow: 0 0 0 14px rgba(34,197,94,0); }
  }
  .cta-btn:hover { transform: translateY(-2px); background: #4ade80; box-shadow: 0 8px 30px rgba(34,197,94,0.35); }

  .secure-note {
    display: flex; align-items: center; justify-content: center; gap: 0.4rem;
    font-size: 0.72rem; color: var(--gray2); margin-top: 1rem;
  }
  .spots-bar {
    display: flex; align-items: center; justify-content: center; gap: 0.5rem;
    margin-top: 1rem;
    background: rgba(239,68,68,0.07);
    border: 1px solid rgba(239,68,68,0.2);
    border-radius: 999px; padding: 0.55rem 1rem;
    font-size: 0.74rem; color: #fca5a5; font-weight: 600;
  }
  .spots-dot { width: 6px; height: 6px; border-radius: 50%; background: var(--red); flex-shrink: 0; animation: livePulse 1.5s infinite; }

  /* ── SECTION PILL ── */
  .section-pill {
    display: inline-flex; align-items: center; gap: 0.5rem;
    border: 1px solid var(--border); border-radius: 999px;
    padding: 0.45rem 1.1rem;
    font-size: 0.67rem; font-weight: 700; letter-spacing: 0.2em;
    text-transform: uppercase; color: var(--gray); margin-bottom: 1.2rem;
  }

  /* ── INSTRUCTOR ── */
  .instructor { padding: 3rem 1.3rem; text-align: center; }
  .instructor h2 {
    font-family: var(--serif); font-size: clamp(1.8rem, 7vw, 2.8rem);
    font-weight: 900; line-height: 1.1; margin-bottom: 0.8rem;
  }
  .instructor h2 .name { color: var(--green); font-style: italic; }
  .instructor .tagline {
    font-size: 0.9rem; color: var(--gray); line-height: 1.75;
    max-width: 360px; margin: 0 auto 2.2rem;
  }

  .host-photo-wrap {
    position: relative; display: inline-block; margin-bottom: 2.5rem;
  }
  .glow-ring {
    position: absolute; inset: -4px; border-radius: 20px; z-index: 0;
    background: linear-gradient(135deg, var(--green), #064e3b, var(--amber), var(--green));
    background-size: 300% 300%;
    animation: gradientShift 3s ease infinite;
    filter: blur(1px);
  }
  @keyframes gradientShift {
    0%   { background-position: 0% 50%; }
    50%  { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  .host-photo {
    width: 220px; height: 270px;
    object-fit: cover; object-position: center top;
    border-radius: 16px;
    position: relative; z-index: 1; display: block;
    filter: contrast(1.05);
    animation: floatPhoto 4s ease-in-out infinite;
  }
  @keyframes floatPhoto {
    0%,100% { transform: translateY(0); }
    50%      { transform: translateY(-8px); }
  }
  .host-badge {
    position: absolute; bottom: -14px; left: 50%; transform: translateX(-50%);
    background: var(--green); color: #000;
    font-size: 0.62rem; font-weight: 800; letter-spacing: 0.15em;
    text-transform: uppercase; padding: 0.38rem 1.1rem;
    border-radius: 999px; white-space: nowrap; z-index: 2;
  }

  /* ── ACHIEVEMENT CARDS ── */
  .achievements {
    padding: 0.5rem 1.3rem 3rem;
    display: flex; flex-direction: column; gap: 1rem;
    max-width: 480px; margin: 0 auto;
  }
  .ach-card {
    background: var(--card); border: 1px solid var(--border);
    border-radius: 14px; padding: 1.2rem;
    display: flex; gap: 1rem; align-items: flex-start;
    transition: border-color 0.3s, transform 0.3s;
  }
  .ach-card:hover { border-color: rgba(34,197,94,0.3); transform: translateX(5px); }
  .ach-icon {
    width: 50px; height: 50px; border-radius: 12px;
    background: var(--green); flex-shrink: 0;
    display: flex; align-items: center; justify-content: center;
    font-size: 1.4rem;
  }
  .ach-title { font-size: 1rem; font-weight: 700; margin-bottom: 0.35rem; }
  .ach-desc  { font-size: 0.83rem; color: var(--gray); line-height: 1.65; }

  /* ── CURRICULUM ── */
  .curriculum { padding: 3rem 1.3rem; text-align: center; }
  .curriculum h2 {
    font-family: var(--serif); font-size: clamp(1.8rem, 7vw, 2.8rem);
    font-weight: 900; line-height: 1.1; margin-bottom: 0.7rem;
  }
  .curriculum h2 .highlight { color: var(--amber); font-style: italic; }
  .curriculum .sub {
    font-size: 0.88rem; color: var(--gray); line-height: 1.7;
    max-width: 360px; margin: 0 auto 2rem;
  }
  .steps {
    display: flex; flex-direction: column; gap: 1rem;
    max-width: 480px; margin: 0 auto;
    text-align: left;
  }
  .step-card {
    background: var(--card); border: 1px solid var(--border);
    border-radius: 14px; padding: 1.4rem 1.2rem;
    display: flex; gap: 1rem; align-items: flex-start;
    transition: border-color 0.3s;
  }
  .step-card:hover { border-color: rgba(34,197,94,0.25); }
  .step-num {
    width: 42px; height: 42px; border-radius: 10px;
    background: var(--green); flex-shrink: 0;
    display: flex; align-items: center; justify-content: center;
    font-size: 1.1rem; font-weight: 900; color: #000;
  }
  .step-title { font-size: 1rem; font-weight: 700; margin-bottom: 0.35rem; }
  .step-desc  { font-size: 0.83rem; color: var(--gray); line-height: 1.65; }

  /* ── TESTIMONIALS / PROOFS ── */
  .testimonials { padding: 3rem 1.3rem; text-align: center; }
  .testimonials h2 {
    font-family: var(--serif); font-size: clamp(1.8rem, 7vw, 2.8rem);
    font-weight: 900; line-height: 1.1; margin-bottom: 0.5rem;
  }
  .testimonials h2 .highlight { color: var(--green); font-style: italic; }
  .proofs {
    display: flex; flex-direction: column; gap: 1.2rem;
    max-width: 480px; margin: 2rem auto 0;
  }
  .proof-card {
    background: var(--card); border: 1px solid var(--border);
    border-radius: 14px; overflow: hidden;
    transition: border-color 0.3s, transform 0.3s;
  }
  .proof-card:hover { border-color: rgba(34,197,94,0.3); transform: scale(1.01); }
  .proof-chat {
    background: #111; padding: 1.2rem;
    border-bottom: 1px solid var(--border);
    text-align: left;
  }
  .proof-chat-header {
    display: flex; align-items: center; gap: 0.6rem;
    margin-bottom: 0.9rem;
  }
  .proof-avatar {
    width: 32px; height: 32px; border-radius: 50%;
    background: linear-gradient(135deg, var(--green), #064e3b);
    display: flex; align-items: center; justify-content: center;
    font-size: 0.75rem; font-weight: 700; color: #000; flex-shrink: 0;
  }
  .proof-chat-name { font-size: 0.78rem; font-weight: 700; }
  .proof-chat-group { font-size: 0.68rem; color: var(--gray2); }
  .proof-bubble {
    background: #1e1e1e; border-radius: 10px; padding: 0.9rem;
    font-size: 0.83rem; line-height: 1.65; color: rgba(255,255,255,0.85);
    margin-bottom: 0.5rem; text-align: left;
  }
  .proof-bubble .earnings { color: var(--green); font-weight: 700; font-size: 0.95rem; }
  .proof-stars {
    padding: 0.8rem 1.2rem;
    display: flex; justify-content: flex-end; gap: 0.15rem;
    color: var(--amber); font-size: 0.85rem;
  }

  /* ── FINAL CTA ── */
  .final-cta {
    padding: 3.5rem 1.3rem;
    text-align: center;
    position: relative; overflow: hidden;
  }
  .final-cta::before {
    content: '';
    position: absolute; inset: 0;
    background: radial-gradient(ellipse 80% 60% at 50% 50%, rgba(34,197,94,0.06) 0%, transparent 70%);
    pointer-events: none;
  }
  .closing-badge {
    display: inline-flex; align-items: center; gap: 0.5rem;
    background: rgba(239,68,68,0.08); border: 1px solid rgba(239,68,68,0.22);
    border-radius: 999px; padding: 0.5rem 1.1rem;
    font-size: 0.68rem; font-weight: 700; letter-spacing: 0.18em;
    text-transform: uppercase; color: #fca5a5; margin-bottom: 1.4rem;
  }
  .final-cta h2 {
    font-family: var(--serif); font-size: clamp(1.8rem, 7vw, 2.8rem);
    font-weight: 900; line-height: 1.1; margin-bottom: 1rem;
  }
  .final-cta h2 .highlight { color: var(--green); font-style: italic; }
  .final-cta p {
    font-size: 0.92rem; color: var(--gray); line-height: 1.75;
    max-width: 380px; margin: 0 auto 2rem;
  }
  .final-secure {
    font-size: 0.72rem; color: var(--gray2); margin-top: 0.9rem;
  }

  /* ── STICKY BOTTOM BAR ── */
  .sticky-bar {
    position: fixed; bottom: 0; left: 0; right: 0; z-index: 999;
    background: #1a2e1a;
    border-top: 1px solid rgba(34,197,94,0.3);
    padding: 0.7rem 1.2rem;
  }
  .sticky-inner {
    max-width: 480px; margin: 0 auto;
    display: flex; flex-direction: column; align-items: center; gap: 0.4rem;
  }
  .sticky-date {
    font-size: 0.72rem; color: rgba(255,255,255,0.6); font-weight: 500;
    text-align: center;
  }
  .sticky-countdown {
    display: flex; align-items: center; gap: 0.3rem;
  }
  .sc-block {
    display: flex; flex-direction: column; align-items: center;
    min-width: 42px;
  }
  .sc-num {
    font-family: var(--serif); font-size: 1.6rem; font-weight: 900;
    color: var(--white); line-height: 1;
  }
  .sc-label {
    font-size: 0.52rem; letter-spacing: 0.12em; text-transform: uppercase;
    color: rgba(255,255,255,0.45); margin-top: 0.1rem;
  }
  .sc-sep { font-size: 1.3rem; font-weight: 900; color: var(--green); padding: 0 0.1rem; margin-bottom: 8px; }
  .sticky-btn {
    display: block; width: 100%; max-width: 300px;
    background: var(--white); color: #000;
    border: none; border-radius: 8px;
    padding: 0.7rem 1rem;
    font-family: var(--sans); font-size: 0.75rem;
    font-weight: 800; letter-spacing: 0.14em;
    text-transform: uppercase; cursor: pointer;
    text-decoration: none; text-align: center;
    transition: background 0.2s;
  }
  .sticky-btn:hover { background: var(--green); color: #000; }

  /* ── REGISTRATION MODAL ── */
  .modal-overlay {
    display: none;
    position: fixed; inset: 0; z-index: 9999;
    background: rgba(0,0,0,0.85);
    align-items: center; justify-content: center;
    padding: 1rem;
    backdrop-filter: blur(6px);
  }
  .modal-overlay.open { display: flex; }
  .modal {
    background: var(--card);
    border: 1px solid rgba(34,197,94,0.25);
    border-radius: 20px; padding: 2.2rem 1.8rem;
    width: 100%; max-width: 420px;
    position: relative;
    animation: modalIn 0.35s cubic-bezier(0.22,1,0.36,1) both;
  }
  @keyframes modalIn {
    from { opacity: 0; transform: scale(0.9) translateY(20px); }
    to   { opacity: 1; transform: scale(1) translateY(0); }
  }
  .modal::before {
    content: '';
    position: absolute; top: 0; left: 0; right: 0; height: 2px;
    border-radius: 20px 20px 0 0;
    background: linear-gradient(90deg, transparent, var(--green), transparent);
  }
  .modal-close {
    position: absolute; top: 1rem; right: 1rem;
    background: none; border: none; color: var(--gray2);
    font-size: 1.3rem; cursor: pointer; line-height: 1;
    transition: color 0.2s;
  }
  .modal-close:hover { color: var(--white); }
  .modal-icon { font-size: 2.5rem; margin-bottom: 0.8rem; }
  .modal h3 {
    font-family: var(--serif); font-size: 1.7rem; font-weight: 900;
    margin-bottom: 0.4rem;
  }
  .modal p {
    font-size: 0.84rem; color: var(--gray); margin-bottom: 1.5rem; line-height: 1.6;
  }
  .form-group { margin-bottom: 1rem; }
  .form-group label {
    display: block; font-size: 0.73rem; font-weight: 700;
    letter-spacing: 0.1em; text-transform: uppercase;
    color: var(--gray); margin-bottom: 0.4rem;
  }
  .form-group input {
    width: 100%; background: #222; border: 1px solid var(--border);
    border-radius: 10px; padding: 0.85rem 1rem;
    font-family: var(--sans); font-size: 0.9rem; color: var(--white);
    outline: none; transition: border-color 0.25s;
  }
  .form-group input:focus { border-color: var(--green); }
  .form-group input::placeholder { color: var(--gray2); }
  .modal-submit {
    display: block; width: 100%;
    background: var(--green); color: #000;
    border: none; border-radius: 10px;
    padding: 1rem; margin-top: 0.5rem;
    font-family: var(--sans); font-size: 0.85rem;
    font-weight: 800; letter-spacing: 0.12em;
    text-transform: uppercase; cursor: pointer;
    transition: background 0.25s, transform 0.25s;
  }
  .modal-submit:hover { background: #4ade80; transform: translateY(-1px); }
  .modal-note {
    display: flex; align-items: center; justify-content: center; gap: 0.4rem;
    font-size: 0.7rem; color: var(--gray2); margin-top: 0.9rem;
  }

  /* ── SCROLL REVEAL ── */
  .reveal {
    opacity: 0; transform: translateY(28px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .reveal.visible { opacity: 1; transform: translateY(0); }

  /* ── DISCLAIMER ── */
  .disclaimer {
    text-align: center; padding: 2rem 1.3rem 1rem;
    font-size: 0.68rem; color: var(--gray2); line-height: 1.7;
    border-top: 1px solid var(--border); max-width: 480px; margin: 0 auto;
  }
</style>
</head>
<body>

<!-- LIVE BADGE -->
<div class="live-badge">
  <span class="live-dot"></span>
  Live Training Starting Soon
</div>

<!-- HERO -->
<section class="hero">
  <h1 class="hero-headline">
    How Smart Nigerians Are<br>
    Earning <span class="green">₦500K –</span><br>
    <span class="amber">₦2M Monthly</span><br>
    Writing Ads &amp; Emails<br>
    For Brands
  </h1>
  <p class="hero-sub">
    Join this <strong>FREE live masterclass</strong> and discover the exact copywriting system that helped complete beginners land paying clients — even with zero experience or a large following.
  </p>
  <div class="hero-badges">
    <div class="badge"><span class="icon">👥</span> <strong>1,200+</strong>&nbsp;enrolled</div>
    <div class="badge"><span class="icon">⭐</span> <strong>4.9/5</strong>&nbsp;rating</div>
  </div>

  <!-- REGISTER CARD -->
  <div class="register-card">
    <div class="free-label">✔ 100% Free — No Card Required</div>
    <h2>Reserve Your Seat</h2>
    <p>Limited spots available. Register now before it fills up.</p>
    <button class="cta-btn" onclick="openModal()">
      YES! SAVE MY SEAT NOW
      <span>→ Click to register for free</span>
    </button>
    <div class="secure-note">🔒 Your information is 100% secure. We respect your privacy.</div>
    <div class="spots-bar">
      <span class="spots-dot"></span>
      Only 43 spots remaining
    </div>
  </div>
</section>

<!-- INSTRUCTOR -->
<section class="instructor reveal">
  <div class="section-pill">✦ Your Instructor</div>
  <h2>Meet <span class="name">Olayinka</span> —<br>Your Guide to Copywriting Freedom</h2>
  <p class="tagline">From zero clients to writing high-converting ads for top brands — here's how he built a thriving copywriting career from scratch.</p>

  <div class="host-photo-wrap">
    <div class="glow-ring"></div>
    <img
      src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEASABIAAD/4gIoSUNDX1BST0ZJTEUAAQEAAAIYAAAAAAQwAABtbnRyUkdCIFhZWiAAAAAAAAAAAAAAAABhY3NwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAA9tYAAQAAAADTLQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAlkZXNjAAAA8AAAAHRyWFlaAAABZAAAABRnWFlaAAABeAAAABRiWFlaAAABjAAAABRyVFJDAAABoAAAAChnVFJDAAABoAAAAChiVFJDAAABoAAAACh3dHB0AAAByAAAABRjcHJ0AAAB3AAAADxtbHVjAAAAAAAAAAEAAAAMZW5VUwAAAFgAAAAcAHMAUgBHAEIAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAFhZWiAAAAAAAABvogAAOPUAAAOQWFlaIAAAAAAAAGKZAAC3hQAAGNpYWVogAAAAAAAAJKAAAA+EAAC2z3BhcmEAAAAAAAQAAAACZmYAAPKnAAANWQAAE9AAAApbAAAAAAAAAABYWVog
