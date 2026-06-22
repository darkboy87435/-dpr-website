<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Professional Website</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0f172a;
    color: white;
}

/* Navbar */
nav {
    display: flex;
    justify-content: space-between;
    padding: 15px 30px;
    background: #111827;
    position: sticky;
    top: 0;
}

nav h2 {
    color: #38bdf8;
}

nav a {
    color: white;
    margin-left: 15px;
    text-decoration: none;
}

/* Hero */
.hero {
    text-align: center;
    padding: 80px 20px;
    background: linear-gradient(to right, #2563eb, #7c3aed);
}

.hero h1 {
    font-size: 40px;
}

.hero p {
    font-size: 18px;
    margin-top: 10px;
}

/* Section */
section {
    padding: 50px 20px;
    text-align: center;
}

.card-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.card {
    background: #1f2937;
    padding: 20px;
    width: 250px;
    border-radius: 10px;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background: #111827;
    margin-top: 20px;
}
</style>
</head>

<body>

<nav>
    <h2>MySite</h2>
    <div>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<div class="hero" id="home">
    <h1>Hi, I'm a Web Developer</h1>
    <p>I build modern and responsive websites using HTML, CSS & GitHub Pages</p>
</div>

<section id="about">
    <h2>About Me</h2>
    <p>I am a beginner developer learning to build professional websites step by step.</p>
</section>

<section id="services">
    <h2>My Services</h2>
    <div class="card-container">
        <div class="card">🌐 Website Design</div>
        <div class="card">📱 Mobile Friendly UI</div>
        <div class="card">⚡ Fast Landing Pages</div>
    </div>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>Email: yourname@gmail.com</p>
</section>

<footer>
    © 2026 My Professional Website | All Rights Reserved
</footer>

</body>
</html>