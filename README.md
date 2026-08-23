<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gurukul Kidz Academy</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:Arial,Helvetica,sans-serif;color:#24324a;line-height:1.6;background:#fff}
header{position:sticky;top:0;z-index:10;background:#fff;box-shadow:0 2px 12px #00000018}
.nav{max-width:1150px;margin:auto;padding:14px 22px;display:flex;align-items:center;justify-content:space-between}
.logo{font-size:1.45rem;font-weight:800;color:#1456a0}.logo span{color:#f39b20}
nav a{margin-left:20px;text-decoration:none;color:#24324a;font-weight:700}
nav a:hover{color:#f39b20}
.hero{background:linear-gradient(135deg,#e9f6ff,#fff3d8);padding:90px 22px}
.hero-inner{max-width:1150px;margin:auto;display:grid;grid-template-columns:1.25fr .75fr;gap:40px;align-items:center}
.hero h1{font-size:clamp(2.5rem,6vw,4.7rem);line-height:1.05;color:#1456a0}
.hero h1 span{color:#f39b20}
.hero p{font-size:1.15rem;margin:22px 0;max-width:650px}
.btn{display:inline-block;padding:13px 22px;border-radius:30px;background:#f39b20;color:#fff;text-decoration:none;font-weight:800;margin-right:10px}
.btn.blue{background:#1456a0}
.hero-card{background:#fff;border-radius:28px;padding:38px;text-align:center;box-shadow:0 15px 40px #1456a025}
.hero-card .emoji{font-size:6rem}
section{padding:75px 22px}
.container{max-width:1150px;margin:auto}
.title{text-align:center;margin-bottom:42px}
.title h2{font-size:2.3rem;color:#1456a0}
.title p{color:#68758a}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
.card{background:#fff;border-radius:20px;padding:28px;box-shadow:0 8px 28px #0000000d;border:1px solid #eef2f7}
.card h3{margin:12px 0;color:#1456a0}.icon{font-size:2.5rem}
.about{background:#f7fbff}
.stats{display:grid;grid-template-columns:repeat(4,1fr);gap:18px;margin-top:30px}
.stat{padding:25px;text-align:center;border-radius:18px;background:#fff;box-shadow:0 5px 20px #0000000b}
.stat strong{display:block;font-size:2rem;color:#f39b20}
.admission{background:linear-gradient(135deg,#1456a0,#247bc8);color:#fff}
.admission .title h2,.admission .title p{color:#fff}
.contact{background:#fff8e9}
.contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:30px}
.contact-card{background:#fff;padding:30px;border-radius:20px}
.contact-card p{margin:12px 0}
footer{background:#17243a;color:#fff;text-align:center;padding:28px}
@media(max-width:800px){
nav{display:none}.hero-inner,.contact-grid{grid-template-columns:1fr}.grid{grid-template-columns:1fr 1fr}.stats{grid-template-columns:1fr 1fr}
}
@media(max-width:520px){.grid,.stats{grid-template-columns:1fr}.hero{padding:60px 18px}section{padding:55px 18px}}
</style>
</head>
<body>
<header>
<div class="nav">
<div class="logo">Gurukul <span>Kidz</span> Academy</div>
<nav>
<a href="#home">Home</a><a href="#about">About</a><a href="#academics">Academics</a><a href="#activities">Activities</a><a href="#admissions">Admissions</a><a href="#contact">Contact</a>
</nav>
</div>
</header>

<main>
<section class="hero" id="home">
<div class="hero-inner">
<div>
<h1>Learn. Grow. <span>Shine!</span></h1>
<p>Welcome to Gurukul Kidz Academy — a joyful place where children learn with confidence, creativity and curiosity.</p>
<a class="btn" href="#admissions">Admissions Open</a>
<a class="btn blue" href="#contact">Contact Us</a>
</div>
<div class="hero-card"><div class="emoji">🎒📚🌈</div><h2>Happy Learning Starts Here</h2><p>Building bright minds and confident learners.</p></div>
</div>
</section>

<section id="about" class="about">
<div class="container">
<div class="title"><h2>About Our School</h2><p>A caring environment designed for every child's growth.</p></div>
<div class="grid">
<div class="card"><div class="icon">🏫</div><h3>Safe Environment</h3><p>A welcoming and supportive atmosphere where children feel comfortable learning and exploring.</p></div>
<div class="card"><div class="icon">👩‍🏫</div><h3>Dedicated Teachers</h3><p>Teachers who encourage questions, creativity, good habits and a love for learning.</p></div>
<div class="card"><div class="icon">🌟</div><h3>Holistic Growth</h3><p>We focus on academics, confidence, communication, creativity and practical skills.</p></div>
</div>
<div class="stats">
<div class="stat"><strong>📚</strong>Quality Learning</div>
<div class="stat"><strong>🎨</strong>Creative Activities</div>
<div class="stat"><strong>🧠</strong>Abacus Classes</div>
<div class="stat"><strong>❤️</strong>Caring Community</div>
</div>
</div>
</section>

<section id="academics">
<div class="container">
<div class="title"><h2>Academics</h2><p>Learning that is engaging, practical and enjoyable.</p></div>
<div class="grid">
<div class="card"><div class="icon">🔤</div><h3>Language Skills</h3><p>Developing reading, writing, vocabulary and confident communication.</p></div>
<div class="card"><div class="icon">🔢</div><h3>Mathematics</h3><p>Building strong number sense through activities, practice and logical thinking.</p></div>
<div class="card"><div class="icon">🔬</div><h3>EVS & Science</h3><p>Discovering the world through observation, experiments and curiosity.</p></div>
</div>
</div>
</section>

<section id="activities" class="about">
<div class="container">
<div class="title"><h2>Activities & Abacus</h2><p>Because children learn best when they enjoy learning.</p></div>
<div class="grid">
<div class="card"><div class="icon">🧮</div><h3>Abacus Classes</h3><p>Fun number activities that encourage concentration, calculation skills and confidence.</p></div>
<div class="card"><div class="icon">⚽</div><h3>Sports & Games</h3><p>Opportunities for active play, teamwork and healthy habits.</p></div>
<div class="card"><div class="icon">🎭</div><h3>Creative Activities</h3><p>Art, craft, performances and activities that let children express themselves.</p></div>
</div>
</div>
</section>

<section id="admissions" class="admission">
<div class="container">
<div class="title"><h2>Admissions Open</h2><p>Give your child a joyful beginning and a strong foundation.</p></div>
<div style="text-align:center"><a class="btn" href="tel:8937053837">📞 Call 8937053837</a><a class="btn" href="tel:9760131406">📞 Call 9760131406</a></div>
</div>
</section>

<section id="contact" class="contact">
<div class="container">
<div class="title"><h2>Contact Us</h2><p>We would love to hear from you.</p></div>
<div class="contact-grid">
<div class="contact-card"><h3>Gurukul Kidz Academy</h3><p>📞 <a href="tel:8937053837">8937053837</a></p><p>📞 <a href="tel:9760131406">9760131406</a></p><p>📧 Contact the school for admissions and further information.</p></div>
<div class="contact-card"><h3>Quick Enquiry</h3><p>For admission enquiries, call us on either of the numbers above.</p><a class="btn blue" href="tel:8937053837">Call Now</a></div>
</div>
</div>
</section>
</main>

<footer>© 2026 Gurukul Kidz Academy. All Rights Reserved.</footer>
</body>
</html>
