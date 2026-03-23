<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>YengeniTech Solutions</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&family=Pacifico&display=swap" rel="stylesheet">

<style>

body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  scroll-behavior: smooth;
  color: white;
}

/* NAVBAR */
nav {
  position: fixed;
  width: 100%;
  display: flex;
  justify-content: space-between;
  padding: 15px 30px;
  background: rgba(0,0,0,0.7);
  z-index: 1000;
}

.logo {
  font-family: 'Pacifico', cursive;
  color: #ffb6f9;
}

nav a {
  color: white;
  margin-left: 15px;
  text-decoration: none;
}

/* SECTIONS */
section {
  padding: 100px 20px;
  text-align: center;
}

/* HERO VIDEO */
#home {
  position: relative;
  height: 100vh;
  overflow: hidden;
}

#home video {
  position: absolute;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.overlay {
  position: relative;
  z-index: 1;
  padding-top: 200px;
  background: linear-gradient(rgba(255,105,180,0.4), rgba(0,0,0,0.7));
  height: 100%;
}

/* BUTTON */
.btn {
  background: linear-gradient(45deg, #ff6ec4, #ffb6c1);
  padding: 14px 30px;
  border-radius: 30px;
  text-decoration: none;
  color: white;
  display: inline-block;
  margin-top: 20px;
}

/* SERVICES */
.services {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.card {
  background: rgba(255,255,255,0.15);
  margin: 15px;
  padding: 25px;
  width: 250px;
  border-radius: 15px;
}

/* CONTACT */
#contact {
  background: linear-gradient(135deg, #ff6ec4, #7873f5);
}

</style>
</head>

<body>

<!-- NAVIGATION -->
<nav>
<div class="logo">💻 YengeniTech</div>
<div>
<a href="#home">Home</a>
<a href="#services">Services</a>
<a href="#contact">Contact</a>
</div>
</nav>

<!-- HOME -->
<section id="home">

<video autoplay muted loop>
<source src="https://cdn.coverr.co/videos/coverr-working-on-laptop-5176/1080p.mp4" type="video/mp4">
</video>

<div class="overlay">
<h1 style="font-family:'Pacifico', cursive;">Luxury Websites ✨</h1>
<p>Modern websites that attract customers 💖</p>

<a class="btn" href="#contact">Get Started 💬</a>
</div>

</section>

<!-- SERVICES -->
<section id="services">
<h2>💼 My Services</h2>

<div class="services">

<div class="card">
<p>✔ Business Websites</p>
</div>

<div class="card">
<p>✔ Beauty & Food Websites</p>
</div>

<div class="card">
<p>✔ WhatsApp Integration</p>
</div>

</div>

</section>

<!-- CONTACT -->
<section id="contact">
<h2>📲 Contact Me</h2>
<p>Let’s build your website 💖</p>

<a class="btn" href="https://wa.me/27812624641">Chat on WhatsApp 💬</a>

</section>

</body>
</html>
