<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Copy That Converts – Free Masterclass</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">

<style>
body{
margin:0;
font-family:'Inter',sans-serif;
background:#0f0f0f;
color:#ffffff;
}

.container{
width:90%;
max-width:1100px;
margin:auto;
}

.hero{
text-align:center;
padding:80px 0;
background:linear-gradient(180deg,#111,#000);
}

.hero h1{
font-family:'Playfair Display',serif;
font-size:48px;
line-height:1.2;
margin-bottom:20px;
}

.hero p{
font-size:20px;
color:#c9c9c9;
margin-bottom:40px;
}

.btn{
display:inline-block;
padding:18px 40px;
background:#ffcc00;
color:#000;
font-weight:600;
text-decoration:none;
border-radius:6px;
font-size:16px;
}

.section{
padding:80px 0;
}

.section h2{
text-align:center;
font-size:36px;
margin-bottom:40px;
font-family:'Playfair Display',serif;
}

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

.card{
background:#1a1a1a;
padding:30px;
border-radius:8px;
}

.card h3{
margin-top:0;
color:#ffcc00;
}

.host{
display:grid;
grid-template-columns:1fr 1fr;
gap:40px;
align-items:center;
}

.host img{
width:100%;
border-radius:12px;
}

.countdown{
font-size:32px;
text-align:center;
margin:40px 0;
}

.footer{
text-align:center;
padding:40px 0;
background:#000;
color:#777;
font-size:14px;
}

@media(max-width:768px){
.hero h1{font-size:34px;}
.host{grid-template-columns:1fr;}
}
</style>
</head>

<body>

<section class="hero">
<div class="container">
<h1>Copy That Converts – Free Masterclass</h1>
<p>Discover how to write copy that grabs attention, builds desire, and drives real sales — even if you're just getting started.</p>

<div class="countdown" id="countdown">Loading countdown...</div>

<a href="#register" class="btn">Reserve My Free Spot</a>
</div>
</section>

<section class="section">
<div class="container">
<h2>What You'll Learn</h2>

<div class="features">
<div class="card">
<h3>Headlines That Sell</h3>
<p>Craft irresistible headlines that stop scrolling and force people to read.</p>
</div>

<div class="card">
<h3>Email Copy That Converts</h3>
<p>Write emails that build trust and turn subscribers into paying clients.</p>
</div>

<div class="card">
<h3>Persuasion Psychology</h3>
<p>Understand buyer behavior and use proven psychological triggers.</p>
</div>

<div class="card">
<h3>Bonus Templates</h3>
<p>Swipe high-converting templates you can use immediately.</p>
</div>
</div>

</div>
</section>

<section class="section">
<div class="container host">
<img src="IMG_20260301_001429_142.jpg" alt="Olayinka Ashaye">

<div>
<h2>Meet Your Host</h2>
<h3>Olayinka Ashaye</h3>
<p>Copywriting Strategist & Conversion Specialist</p>
<p>Olayinka helps brands turn words into revenue using strategic messaging, persuasion frameworks, and high-impact storytelling. In this masterclass, you'll learn the exact system used to write copy that converts consistently.</p>
</div>

</div>
</section>

<section class="section" id="register">
<div class="container" style="text-align:center;">
<h2>Reserve Your Spot Now</h2>
<p>Limited seats available. Secure your access today.</p>

<a href="#" class="btn">Register Now</a>
</div>
</section>

<div class="footer">
© 2026 Copy That Converts — All Rights Reserved
</div>

<script>
const countdownDate = new Date();
countdownDate.setDate(countdownDate.getDate()+5);

const timer = setInterval(function(){
const now = new Date().getTime();
const distance = countdownDate - now;

const days = Math.floor(distance / (1000 * 60 * 60 * 24));
const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
const seconds = Math.floor((distance % (1000 * 60)) / 1000);

document.getElementById("countdown").innerHTML =
days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

if(distance < 0){
clearInterval(timer);
document.getElementById("countdown").innerHTML = "Registration Closed";
}
},1000);
</script>

</body>
</html>
