<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="google-site-verification" content="google37da617c41221159" />
<title>MD Soyeb Designs | 3D Interior & Building Designer in India</title>
<meta name="description" content="Luxury 3D Interior & Building Designer. Affordable & Modern Design Services. Contact Now.">
<meta name="keywords" content="interior designer India, 3D home design, building designer, luxury interior">
<meta name="author" content="MD Soyeb">
<link rel="icon" href="https://cdn-icons-png.flaticon.com/512/847/847969.png">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
<link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
body{background:#0b0b0b;color:#fff;scroll-behavior:smooth;padding-top:70px}

/* HEADER */
header{
position:fixed;width:100%;background:rgba(0,0,0,0.6);backdrop-filter:blur(12px);padding:15px;text-align:center;z-index:1000
}
nav a{color:#fff;margin:0 15px;text-decoration:none;transition:0.3s}
nav a:hover{color:gold}

/* HERO */
.hero{
height:100vh;display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center;
background:linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.7)),url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c') center/cover;
}
.hero h1{font-size:50px;color:gold}
.hero p{color:#ddd;margin-top:10px}
.btn{margin-top:15px;padding:12px 25px;border-radius:30px;background:gold;color:#000;text-decoration:none;transition:0.3s}
.btn:hover{background:#fff}

/* SECTION */
section{padding:80px 20px;text-align:center}

/* SERVICES */
.services{display:flex;flex-wrap:wrap;justify-content:center}
.card{background:rgba(255,255,255,0.05);backdrop-filter:blur(10px);margin:15px;padding:25px;border-radius:15px;width:250px;transition:0.4s}
.card:hover{transform:translateY(-10px) scale(1.05)}

/* GALLERY */
.gallery{display:flex;flex-wrap:wrap;justify-content:center}
.gallery img{width:300px;height:200px;margin:10px;border-radius:10px;transition:0.4s}
.gallery img:hover{transform:scale(1.1)}

/* TRUST */
.trust{display:flex;justify-content:center;gap:40px;flex-wrap:wrap;margin-top:30px}
.trust div{color:gold;font-size:20px}

/* FORM */
form{max-width:400px;margin:auto}
input, textarea{width:100%;padding:12px;margin:10px 0;border:none;border-radius:5px}
button{padding:12px 20px;border:none;background:gold;border-radius:5px;cursor:pointer}

/* WHATSAPP */
.whatsapp{position:fixed;bottom:20px;right:20px;background:#25D366;color:#fff;padding:18px;border-radius:50%;font-size:22px;text-decoration:none}

/* FOOTER */
footer{background:#000;padding:20px;text-align:center;color:#aaa}
</style>
</head>
<body>

<header>
<h2>MD SOYEB</h2>
<nav>
<a href="#home">Home</a>
<a href="#services">Services</a>
<a href="#portfolio">Portfolio</a>
<a href="#contact">Contact</a>
</nav>
</header>

<!-- HERO -->
<section class="hero" id="home">
<h1 data-aos="fade-up">Design Your Dream Space</h1>
<p data-aos="fade-up">Luxury • Modern • Smart Design</p>
<a href="https://wa.me/916394643385?text=Hello%20I%20saw%20your%20website%20and%20need%20design" class="btn" data-aos="zoom-in">Hire Me</a>
</section>

<!-- SERVICES -->
<section id="services">
<h2 data-aos="fade-up">Services</h2>
<div class="services">
<div class="card" data-aos="fade-up">3D Interior Design</div>
<div class="card" data-aos="fade-up">Building Design</div>
<div class="card" data-aos="fade-up">2D Floor Plan</div>
<div class="card" data-aos="fade-up">Lighting Layout</div>
</div>

<div class="trust">
<div data-aos="zoom-in">✔ 10+ Projects</div>
<div data-aos="zoom-in">✔ 2+ Years Experience</div>
<div data-aos="zoom-in">✔ 100% Satisfaction</div>
</div>
</section>

<!-- PORTFOLIO -->
<section id="portfolio">
<h2 data-aos="fade-up">My Work</h2>
<div class="gallery">
<img src="https://images.unsplash.com/photo-1600210492486-724fe5c67fb0" loading="lazy">
<img src="https://images.unsplash.com/photo-1600607687920-4e2a09cf159d" loading="lazy">
<img src="https://images.unsplash.com/photo-1600573472591-ee6b68d14c68" loading="lazy">
</div>
</section>

<!-- CONTACT -->
<section id="contact">
<h2 data-aos="fade-up">Contact Me</h2>

<form id="clientForm" onsubmit="sendAutoClient(); return false;" data-aos="fade-up">
<input type="text" id="name" placeholder="Your Name" required>
<input type="tel" id="phone" placeholder="Your Phone" pattern="[0-9]{10}" required>
<textarea id="message" placeholder="Your Requirement"></textarea>
<button type="submit">Send Message</button>
</form>

<br>
<a href="https://instagram.com/shoyebmd07" target="_blank" class="btn">Instagram</a>
<a href="https://youtube.com/@MdSoyeb008" target="_blank" class="btn">YouTube</a>
</section>



<footer>
<p>© 2026 MD Soyeb Designs | All Rights Reserved</p>
</footer>

<script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
<script>
AOS.init({duration:1000,once:true});

function sendAutoClient(){
  let name=document.getElementById('name').value;
  let phone=document.getElementById('phone').value;
  let message=document.getElementById('message').value;

  // WhatsApp auto message
  let whatsappURL="https://wa.me/916394643385?text="
  +"Hello, I am "+name+"%0a"
  +"Phone: "+phone+"%0a"
  +"Requirement: "+message;
  window.open(whatsappURL,'_blank');

  // Gmail auto message
  let gmail="mailto:rsoyeb574@gmail.com?subject=New Client&body="
  +"Name: "+name+"%0a"
  +"Phone: "+phone+"%0a"
  +"Requirement: "+message;
  window.open(gmail,'_blank');

  // Optional: Google Form prefill URL
  // let googleForm="GOOGLE_FORM_PREFILL_LINK";
  // window.open(googleForm,'_blank');
}
</script>
</body>
</html>
