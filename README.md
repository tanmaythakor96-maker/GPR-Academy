# GPR-Academy
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GPR Academy | Shaping Bright Futures</title>

<!-- SEO -->
<meta name="description" content="GPR Academy - Shaping Bright Futures with Knowledge & Values. Admissions Open Now.">
<meta name="keywords" content="GPR Academy, School, Education, Admissions, Academics">
<meta name="author" content="GPR Academy">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
:root{
    --primary:#0d47a1;
    --secondary:#fbc02d;
    --light:#f4f6f9;
}
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}
body{
    background:var(--light);
    scroll-behavior:smooth;
}
header{
    background:#fff;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 8%;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
    position:fixed;
    width:100%;
    z-index:1000;
}
header img{
    height:60px;
}
nav a{
    margin-left:20px;
    text-decoration:none;
    color:var(--primary);
    font-weight:600;
}
.hero{
    height:100vh;
    background:linear-gradient(rgba(13,71,161,0.8),rgba(13,71,161,0.8)),url('https://images.unsplash.com/photo-1588072432836-e10032774350');
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:#fff;
    padding:0 20px;
}
.hero h1{
    font-size:40px;
    margin-bottom:20px;
}
.btn{
    padding:12px 25px;
    background:var(--secondary);
    color:#000;
    border:none;
    text-decoration:none;
    margin:10px;
    font-weight:600;
    border-radius:30px;
    transition:0.3s;
}
.btn:hover{
    background:#fff;
}
section{
    padding:80px 8%;
}
h2{
    text-align:center;
    margin-bottom:40px;
    color:var(--primary);
}
.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}
.card{
    background:#fff;
    padding:25px;
    border-radius:10px;
    box-shadow:0 5px 15px rgba(0,0,0,0.08);
    transition:0.3s;
}
.card:hover{
    transform:translateY(-8px);
}
footer{
    background:var(--primary);
    color:#fff;
    padding:40px 8%;
}
footer img{
    height:60px;
    margin-bottom:15px;
}
footer a{
    color:var(--secondary);
    text-decoration:none;
}
form input, form textarea{
    width:100%;
    padding:10px;
    margin:10px 0;
    border:1px solid #ccc;
    border-radius:5px;
}
form button{
    background:var(--primary);
    color:#fff;
    padding:10px 20px;
    border:none;
    border-radius:5px;
}
.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:#fff;
    padding:15px;
    border-radius:50%;
    text-decoration:none;
    font-size:20px;
}
@media(max-width:768px){
    .hero h1{font-size:28px;}
    nav{display:none;}
}
</style>
</head>

<body>

<header>
    <img src="logo.png" alt="GPR Academy Logo">
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#academics">Academics</a>
        <a href="#admissions">Admissions</a>
        <a href="#gallery">Gallery</a>
        <a href="#news">News</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero" id="home">
    <div>
        <h1>Shaping Bright Futures with Knowledge & Values</h1>
        <a href="#admissions" class="btn">Admission Open</a>
        <a href="#contact" class="btn">Contact Us</a>
    </div>
</section>

<section id="about">
<h2>About GPR Academy</h2>
<p style="text-align:center; max-width:800px; margin:auto;">
GPR Academy is a progressive and student-focused educational institution committed to academic excellence, discipline, character development, and holistic growth.
</p>

<div class="grid" style="margin-top:40px;">
<div class="card"><h3>Mission</h3><p>To empower students with knowledge, skills, and strong moral values.</p></div>
<div class="card"><h3>Vision</h3><p>To become a center of excellence in education and leadership development.</p></div>
<div class="card"><h3>Principal’s Message</h3><p>We aim to nurture disciplined, confident and responsible citizens.</p></div>
</div>

<h2 style="margin-top:60px;">Core Values</h2>
<div class="grid">
<div class="card">Discipline</div>
<div class="card">Knowledge</div>
<div class="card">Leadership</div>
<div class="card">Innovation</div>
</div>
</section>

<section id="academics">
<h2>Academics</h2>
<div class="grid">
<div class="card"><h3>Classes Offered</h3><p>Nursery to Higher Secondary</p></div>
<div class="card"><h3>Curriculum</h3><p>Modern, activity-based learning system.</p></div>
<div class="card"><h3>Teaching Method</h3><p>Interactive & digital classroom learning.</p></div>
<div class="card"><h3>Examinations</h3><p>Regular assessments & performance tracking.</p></div>
</div>
</section>

<section id="admissions">
<h2>Admissions</h2>
<div class="grid">
<div class="card">
<h3>Admission Process</h3>
<p>Fill inquiry form → Document verification → Confirmation.</p>
</div>
<div class="card">
<h3>Eligibility</h3>
<p>Age criteria as per academic level.</p>
</div>
<div class="card">
<h3>Required Documents</h3>
<p>Birth Certificate, Aadhaar Card, Previous Marksheet.</p>
</div>
</div>

<h3 style="margin-top:40px;">Inquiry Form</h3>
<form>
<input type="text" placeholder="Student Name" required>
<input type="email" placeholder="Email" required>
<input type="tel" placeholder="Phone" required>
<textarea placeholder="Message"></textarea>
<button type="submit">Submit</button>
</form>
</section>

<section id="gallery">
<h2>Gallery</h2>
<div class="grid">
<img src="https://images.unsplash.com/photo-1509062522246-3755977927d7" width="100%">
<img src="https://images.unsplash.com/photo-1584697964358-67f2c8f97a5f" width="100%">
<img src="https://images.unsplash.com/photo-1596495578065-1f662e5c9b3d" width="100%">
</div>
</section>

<section id="news">
<h2>News & Events</h2>
<div class="grid">
<div class="card">Annual Function 2026 Announced</div>
<div class="card">Admissions Open for 2026-27</div>
<div class="card">Sports Week Celebration</div>
</div>
</section>

<section id="contact">
<h2>Contact Us</h2>
<p>📞 Phone: +91 XXXXX XXXXX</p>
<p>📧 Email: info@gpracademy.com</p>

<iframe src="https://maps.google.com/maps?q=Vadodara&t=&z=13&ie=UTF8&iwloc=&output=embed"
width="100%" height="300" style="border:0;"></iframe>
</section>

<footer>
<img src="logo.png" alt="GPR Academy Logo">
<p><strong>Quick Links:</strong> Home | About | Admissions | Contact</p>
<p>Instagram: <a href="https://www.instagram.com/gpracademy" target="_blank">@gpracademy</a></p>
<p>© 2026 GPR Academy. All Rights Reserved.</p>
</footer>

<a href="https://wa.me/91XXXXXXXXXX" class="whatsapp" target="_blank">💬</a>

</body>
</html>