<?php
// =====================================================
// CONTACT FORM EMAIL HANDLER
// =====================================================

$formMessage = "";
$formSuccess = false;

if ($_SERVER["REQUEST_METHOD"] === "POST") {

    $name    = trim($_POST["name"] ?? "");
    $email   = trim($_POST["email"] ?? "");
    $phone   = trim($_POST["phone"] ?? "");
    $subject = trim($_POST["subject"] ?? "");
    $message = trim($_POST["message"] ?? "");

    // Validation
    if (
        empty($name) ||
        empty($email) ||
        empty($phone) ||
        empty($subject) ||
        empty($message)
    ) {

        $formMessage = "Please fill in all fields.";

    } elseif (!filter_var($email, FILTER_VALIDATE_EMAIL)) {

        $formMessage = "Please enter a valid email address.";

    } else {

        // Email recipient
        $to = "sudeepjha85@gmail.com";

        // Email subject
        $mailSubject = "New Portfolio Enquiry - " . $subject;

        // Email body
        $mailBody = "
========================================
NEW PORTFOLIO CONTACT FORM
========================================

Name:
$name

Email:
$email

Phone:
$phone

Subject:
$subject

Message:
$message

========================================
Website: " . ($_SERVER["HTTP_HOST"] ?? "Portfolio Website") . "

IP Address:
" . ($_SERVER["REMOTE_ADDR"] ?? "Unknown") . "
========================================
";

        // Safe headers
        $host = $_SERVER["HTTP_HOST"] ?? "website.com";
        $host = preg_replace("/[^a-zA-Z0-9.\-]/", "", $host);

        $headers  = "From: Portfolio Website <noreply@" . $host . ">\r\n";
        $headers .= "Reply-To: " . $email . "\r\n";
        $headers .= "MIME-Version: 1.0\r\n";
        $headers .= "Content-Type: text/plain; charset=UTF-8\r\n";

        // Send email
        if (mail($to, $mailSubject, $mailBody, $headers)) {

            $formSuccess = true;
            $formMessage = "Thank you! Your message has been sent successfully.";

            $name = "";
            $email = "";
            $phone = "";
            $subject = "";
            $message = "";

        } else {

            $formMessage = "Unable to send your message. Please try again later.";
        }
    }
}
?>

<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport"
      content="width=device-width, initial-scale=1.0">

<meta name="description"
      content="Senior WordPress Developer Portfolio - Custom WordPress, WooCommerce, Elementor and Plugin Development">

<meta name="keywords"
      content="Senior WordPress Developer, WordPress Developer, Elementor Developer, WooCommerce Developer, WordPress Plugin Developer">

<meta name="author"
      content="Sudeep">

<title>Senior WordPress Developer | Sudeep</title>

<link rel="preconnect"
      href="https://fonts.googleapis.com">

<link rel="preconnect"
      href="https://fonts.gstatic.com"
      crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap"
      rel="stylesheet">

<link rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

<style>

/* =====================================================
   RESET
===================================================== */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: "Inter", sans-serif;
    background: #07070b;
    color: #ffffff;
    line-height: 1.7;
    overflow-x: hidden;
}

a {
    text-decoration: none;
    color: inherit;
}

button,
input,
textarea {
    font-family: inherit;
}

.container {
    width: min(90%, 1200px);
    margin: auto;
}

img {
    max-width: 100%;
}

/* =====================================================
   HEADER
===================================================== */

.header {
    position: fixed;
    left: 0;
    top: 0;
    width: 100%;
    z-index: 999;
    padding: 20px 0;
    transition: .3s;
}

.header.scrolled {
    padding: 13px 0;
    background: rgba(7,7,11,.94);
    backdrop-filter: blur(20px);
    border-bottom: 1px solid rgba(255,255,255,.08);
}

.nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo {
    font-family: "Space Grotesk";
    font-size: 27px;
    font-weight: 800;
    letter-spacing: -2px;
}

.logo span {
    color: #7c5cff;
}

.nav-links {
    display: flex;
    gap: 28px;
}

.nav-links a {
    color: #999;
    font-size: 13px;
    transition: .3s;
}

.nav-links a:hover,
.nav-links a.active {
    color: #fff;
}

.hire-btn {
    background: #7c5cff;
    padding: 10px 20px;
    border-radius: 7px;
    font-size: 13px;
    font-weight: 600;
    transition: .3s;
}

.hire-btn:hover {
    transform: translateY(-2px);
    background: #9278ff;
}

.menu-btn {
    display: none;
    border: 0;
    background: none;
    color: #fff;
    font-size: 23px;
    cursor: pointer;
}

/* =====================================================
   HERO
===================================================== */

.hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    padding: 130px 0 80px;
    position: relative;
    overflow: hidden;
}

.hero:before {
    content: "";
    position: absolute;
    width: 500px;
    height: 500px;
    background: #7c5cff;
    opacity: .12;
    filter: blur(130px);
    border-radius: 50%;
    left: -200px;
    top: 100px;
}

.hero:after {
    content: "";
    position: absolute;
    width: 400px;
    height: 400px;
    background: #00d4ff;
    opacity: .07;
    filter: blur(120px);
    border-radius: 50%;
    right: -150px;
    bottom: 50px;
}

.hero-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 70px;
    align-items: center;
    position: relative;
    z-index: 2;
}

.available {
    display: inline-flex;
    gap: 9px;
    align-items: center;
    border: 1px solid rgba(255,255,255,.1);
    background: rgba(255,255,255,.03);
    padding: 7px 13px;
    border-radius: 30px;
    color: #aaa;
    font-size: 11px;
}

.dot {
    width: 8px;
    height: 8px;
    background: #48e08b;
    border-radius: 50%;
    box-shadow: 0 0 12px #48e08b;
}

.hero small {
    display: block;
    color: #9d85ff;
    letter-spacing: 3px;
    font-size: 11px;
    font-weight: 700;
    margin-top: 25px;
}

.hero h1 {
    font-family: "Space Grotesk";
    font-size: clamp(48px,6vw,75px);
    line-height: 1.03;
    letter-spacing: -4px;
    margin: 15px 0 25px;
}

.hero h1 span {
    color: #7c5cff;
}

.hero-text {
    color: #999;
    max-width: 620px;
    font-size: 16px;
    margin-bottom: 30px;
}

.buttons {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
}

.btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 9px;
    min-height: 48px;
    padding: 0 22px;
    border-radius: 7px;
    font-size: 13px;
    font-weight: 600;
    border: 0;
    cursor: pointer;
    transition: .3s;
}

.btn-primary {
    background: #7c5cff;
    color: #fff;
}

.btn-primary:hover {
    transform: translateY(-3px);
    box-shadow: 0 15px 35px rgba(124,92,255,.3);
}

.btn-outline {
    border: 1px solid rgba(255,255,255,.1);
    color: #fff;
}

.btn-outline:hover {
    border-color: #7c5cff;
}

.stats {
    display: flex;
    gap: 40px;
    margin-top: 50px;
}

.stat strong {
    font-family: "Space Grotesk";
    font-size: 29px;
}

.stat span {
    color: #7c5cff;
    font-weight: 700;
}

.stat small {
    color: #777;
    letter-spacing: 0;
    margin: 0;
    font-size: 10px;
}

/* =====================================================
   CODE CARD
===================================================== */

.code-card {
    background: #0d0d13;
    border: 1px solid rgba(255,255,255,.08);
    border-radius: 14px;
    overflow: hidden;
    box-shadow: 0 30px 70px rgba(0,0,0,.5);
    transform: perspective(1000px) rotateY(-4deg);
}

.code-header {
    height: 45px;
    display: flex;
    align-items: center;
    padding: 0 17px;
    border-bottom: 1px solid rgba(255,255,255,.08);
}

.code-dots {
    display: flex;
    gap: 6px;
}

.code-dots span {
    width: 9px;
    height: 9px;
    border-radius: 50%;
    background: #444;
}

.code-title {
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    color: #666;
    font-size: 10px;
}

.code {
    padding: 30px 20px;
    font-family: Consolas, monospace;
    font-size: 12px;
    line-height: 2.1;
    color: #ddd;
}

.line {
    color: #41414b;
    display: inline-block;
    width: 28px;
}

.purple {
    color: #c792ea;
}

.blue {
    color: #82aaff;
}

.yellow {
    color: #ffcb6b;
}

.green {
    color: #c3e88d;
}

.floating {
    position: absolute;
    background: #11111a;
    border: 1px solid rgba(255,255,255,.1);
    border-radius: 9px;
    padding: 12px 15px;
    display: flex;
    gap: 10px;
    align-items: center;
    box-shadow: 0 20px 40px rgba(0,0,0,.4);
}

.floating i {
    color: #7c5cff;
    font-size: 21px;
}

.floating strong {
    display: block;
    font-size: 11px;
}

.floating small {
    display: block;
    color: #777;
    font-size: 9px;
}

.float-one {
    left: -35px;
    bottom: 30px;
}

.float-two {
    right: -25px;
    top: 30px;
}

/* =====================================================
   SECTIONS
===================================================== */

section {
    padding: 110px 0;
}

.dark-section {
    background: #0d0d13;
}

.section-label {
    color: #9d85ff;
    font-size: 11px;
    letter-spacing: 3px;
    font-weight: 700;
}

.section-title {
    font-family: "Space Grotesk";
    font-size: clamp(38px,5vw,55px);
    line-height: 1.1;
    letter-spacing: -2px;
    margin-top: 13px;
}

.section-title span {
    color: #7c5cff;
}

.section-description {
    color: #888;
    margin-top: 15px;
}

/* =====================================================
   ABOUT
===================================================== */

.about-grid {
    display: grid;
    grid-template-columns: .8fr 1.2fr;
    gap: 80px;
    align-items: center;
}

.profile-box {
    aspect-ratio: 1;
    border-radius: 20px;
    background:
        radial-gradient(
            circle at center,
            rgba(124,92,255,.35),
            transparent 35%
        ),
        #101019;
    border: 1px solid rgba(255,255,255,.08);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 100px;
    color: rgba(255,255,255,.08);
}

.about-content .lead {
    color: #fff;
    font-size: 20px;
    line-height: 1.5;
    margin-bottom: 20px;
}

.about-content p {
    color: #888;
    margin-bottom: 18px;
}

.check-list {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
    margin: 28px 0;
}

.check-list div {
    font-size: 12px;
    color: #bbb;
}

.check-list i {
    color: #7c5cff;
    margin-right: 7px;
}

/* =====================================================
   SKILLS
===================================================== */

.center {
    text-align: center;
    max-width: 700px;
    margin: 0 auto 55px;
}

.skills {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    max-width: 900px;
    margin: auto;
}

.skill {
    padding: 22px;
    background: #11111a;
    border: 1px solid rgba(255,255,255,.08);
    border-radius: 10px;
}

.skill-top {
    display: flex;
    justify-content: space-between;
    margin-bottom: 12px;
    font-size: 13px;
}

.skill-top span {
    color: #9d85ff;
}

.progress {
    height: 5px;
    background: #272731;
    border-radius: 10px;
    overflow: hidden;
}

.progress span {
    display: block;
    height: 100%;
    background: linear-gradient(90deg,#7c5cff,#00d4ff);
}

.tech-list {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 9px;
    margin-top: 40px;
}

.tech-list span {
    padding: 8px 13px;
    border: 1px solid rgba(255,255,255,.08);
    border-radius: 5px;
    color: #999;
    font-size: 11px;
}

/* =====================================================
   SERVICES
===================================================== */

.services {
    display: grid;
    grid-template-columns: repeat(4,1fr);
    gap: 18px;
    margin-top: 55px;
}

.service {
    padding: 27px;
    min-height: 300px;
    background: #11111a;
    border: 1px solid rgba(255,255,255,.08);
    border-radius: 11px;
    transition: .3s;
}

.service:hover {
    transform: translateY(-6px);
    border-color: #7c5cff;
}

.service-icon {
    width: 50px;
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: center;
    background: rgba(124,92,255,.1);
    color: #9d85ff;
    border-radius: 9px;
    font-size: 21px;
    margin-bottom: 25px;
}

.service h3 {
    font-family: "Space Grotesk";
    font-size: 18px;
    margin-bottom: 12px;
}

.service p {
    color: #888;
    font-size: 12px;
}

/* =====================================================
   PROJECTS
===================================================== */

.project-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 22px;
    margin-top: 50px;
}

.project {
    overflow: hidden;
    background: #11111a;
    border: 1px solid rgba(255,255,255,.08);
    border-radius: 11px;
}

.project-image {
    height: 250px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: "Space Grotesk";
    font-size: 38px;
    font-weight: 800;
    color: rgba(255,255,255,.15);
}

.project-one {
    background: linear-gradient(135deg,#251b50,#664ce1);
}

.project-two {
    background: linear-gradient(135deg,#11383d,#07818c);
}

.project-three {
    background: linear-gradient(135deg,#401b35,#a83b7d);
}

.project-four {
    background: linear-gradient(135deg,#1c2939,#3e729e);
}

.project-content {
    padding: 23px;
}

.project-content span {
    font-size: 9px;
    color: #9d85ff;
    margin-right: 8px;
}

.project-content h3 {
    font-family: "Space Grotesk";
    margin: 10px 0 7px;
}

.project-content p {
    color: #888;
    font-size: 12px;
}

/* =====================================================
   EXPERIENCE
===================================================== */

.timeline {
    max-width: 850px;
    margin: 55px auto 0;
    position: relative;
}

.timeline:before {
    content: "";
    position: absolute;
    left: 105px;
    top: 0;
    bottom: 0;
    width: 1px;
    background: rgba(255,255,255,.1);
}

.timeline-item {
    display: grid;
    grid-template-columns: 150px 1fr;
    gap: 40px;
    position: relative;
    padding-bottom: 55px;
}

.timeline-date {
    color: #9d85ff;
    font-size: 11px;
}

.timeline-dot {
    position: absolute;
    left: 100px;
    top: 2px;
    width: 11px;
    height: 11px;
    background: #7c5cff;
    border-radius: 50%;
    border: 3px solid #0d0d13;
}

.timeline-content {
    padding-left: 20px;
}

.timeline-content h3 {
    font-family: "Space Grotesk";
    font-size: 21px;
}

.timeline-content h4 {
    color: #666;
    font-size: 11px;
    margin: 4px 0 12px;
}

.timeline-content p {
    color: #888;
    font-size: 12px;
}

/* =====================================================
   CONTACT
===================================================== */

.contact-grid {
    display: grid;
    grid-template-columns: .85fr 1.15fr;
    gap: 70px;
    align-items: start;
}

.contact-info h2 {
    font-family: "Space Grotesk";
    font-size: clamp(40px,5vw,58px);
    line-height: 1.05;
    letter-spacing: -2px;
    margin: 15px 0;
}

.contact-info h2 span {
    color: #7c5cff;
}

.contact-info > p {
    color: #888;
    font-size: 14px;
    margin-bottom: 30px;
}

.contact-item {
    display: flex;
    align-items: center;
    gap: 13px;
    margin-bottom: 18px;
}

.contact-icon {
    width: 42px;
    height: 42px;
    background: rgba(124,92,255,.1);
    color: #9d85ff;
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.contact-item small {
    display: block;
    color: #666;
    font-size: 9px;
}

.contact-item span {
    font-size: 12px;
    color: #bbb;
}

.social {
    display: flex;
    gap: 8px;
    margin-top: 30px;
}

.social a {
    width: 37px;
    height: 37px;
    border: 1px solid rgba(255,255,255,.08);
    border-radius: 6px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #999;
    transition: .3s;
}

.social a:hover {
    background: #7c5cff;
    color: #fff;
}

/* =====================================================
   FORM
===================================================== */

.contact-form {
    background: #11111a;
    border: 1px solid rgba(255,255,255,.08);
    border-radius: 13px;
    padding: 32px;
}

.form-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 15px;
}

.form-group {
    margin-bottom: 17px;
}

.form-group label {
    display: block;
    color: #aaa;
    font-size: 11px;
    margin-bottom: 7px;
}

.form-group input,
.form-group textarea {
    width: 100%;
    border: 1px solid rgba(255,255,255,.08);
    background: #09090e;
    color: #fff;
    border-radius: 6px;
    padding: 13px;
    outline: none;
    font-size: 12px;
    transition: .3s;
}

.form-group input:focus,
.form-group textarea:focus {
    border-color: #7c5cff;
}

.form-group textarea {
    min-height: 130px;
    resize: vertical;
}

.form-message {
    padding: 13px;
    margin-bottom: 18px;
    border-radius: 6px;
    font-size: 12px;
}

.success {
    background: rgba(72,224,139,.1);
    color: #48e08b;
    border: 1px solid rgba(72,224,139,.2);
}

.error {
    background: rgba(255,80,80,.1);
    color: #ff7777;
    border: 1px solid rgba(255,80,80,.2);
}

/* =====================================================
   FOOTER
===================================================== */

footer {
    border-top: 1px solid rgba(255,255,255,.08);
    padding: 28px 0;
    background: #050507;
}

.footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.footer p {
    color: #555;
    font-size: 10px;
}

/* =====================================================
   RESPONSIVE
===================================================== */

@media(max-width:1000px) {

    .nav-links {
        gap: 16px;
    }

    .hero-grid {
        gap: 40px;
    }

    .services {
        grid-template-columns: 1fr 1fr;
    }

}

@media(max-width:850px) {

    .nav-links {
        position: fixed;
        left: 0;
        right: 0;
        top: 70px;
        background: #09090e;
        padding: 25px;
        flex-direction: column;
        border-bottom: 1px solid rgba(255,255,255,.08);
        transform: translateY(-150%);
        transition: .3s;
    }

    .nav-links.open {
        transform: translateY(0);
    }

    .hire-btn {
        display: none;
    }

    .menu-btn {
        display: block;
    }

    .hero-grid,
    .about-grid,
    .contact-grid {
        grid-template-columns: 1fr;
    }

    .hero {
        padding-top: 130px;
    }

    .code-card {
        max-width: 700px;
        margin: 30px auto 0;
    }

    .services {
        grid-template-columns: 1fr 1fr;
    }

}

@media(max-width:650px) {

    section {
        padding: 80px 0;
    }

    .hero h1 {
        font-size: 43px;
        letter-spacing: -3px;
    }

    .stats {
        gap: 20px;
    }

    .stat strong {
        font-size: 23px;
    }

    .skills,
    .project-grid {
        grid-template-columns: 1fr;
    }

    .services {
        grid-template-columns: 1fr;
    }

    .check-list {
        grid-template-columns: 1fr;
    }

    .timeline:before {
        left: 5px;
    }

    .timeline-item {
        grid-template-columns: 1fr;
        padding-left: 28px;
        gap: 8px;
    }

    .timeline-dot {
        left: 0;
    }

    .timeline-content {
        padding-left: 0;
    }

    .form-row {
        grid-template-columns: 1fr;
    }

    .contact-form {
        padding: 22px;
    }

    .footer {
        flex-direction: column;
        gap: 10px;
        text-align: center;
    }

    .float-one {
        left: -5px;
    }

    .float-two {
        right: -5px;
    }

}

</style>

</head>

<body>


<!-- =====================================================
     HEADER
===================================================== -->

<header class="header" id="header">

<div class="container nav">

<a href="#home" class="logo">
<span>&lt;</span>WP<span>/&gt;</span>
</a>

<nav class="nav-links" id="navLinks">

<a href="#home" class="active">Home</a>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#services">Services</a>
<a href="#projects">Projects</a>
<a href="#experience">Experience</a>
<a href="#contact">Contact</a>

</nav>

<a href="#contact" class="hire-btn">
Hire Me
</a>

<button class="menu-btn" id="menuBtn">
<i class="fas fa-bars"></i>
</button>

</div>

</header>


<!-- =====================================================
     HERO
===================================================== -->

<section class="hero" id="home">

<div class="container hero-grid">

<div>

<div class="available">
<span class="dot"></span>
Available for new projects
</div>

<small>
SENIOR WORDPRESS DEVELOPER
</small>

<h1>
Building
<span>Powerful</span>
WordPress Experiences.
</h1>

<p class="hero-text">
I build high-performance WordPress websites, custom themes,
plugins, WooCommerce stores and scalable digital experiences
that help businesses grow.
</p>

<div class="buttons">

<a href="#projects" class="btn btn-primary">
View My Work
<i class="fas fa-arrow-right"></i>
</a>

<a href="#contact" class="btn btn-outline">
Let's Work Together
</a>

</div>

<div class="stats">

<div class="stat">
<strong>8</strong><span>+</span>
<small>Years Experience</small>
</div>

<div class="stat">
<strong>150</strong><span>+</span>
<small>Projects</small>
</div>

<div class="stat">
<strong>50</strong><span>+</span>
<small>Clients</small>
</div>

</div>

</div>


<div style="position:relative">

<div class="code-card">

<div class="code-header">

<div class="code-dots">
<span></span>
<span></span>
<span></span>
</div>

<div class="code-title">
wordpress-developer.php
</div>

</div>

<div class="code">

<div>
<span class="line">01</span>
<span class="purple">&lt;?php</span>
</div>

<div>
<span class="line">02</span>
<span class="blue">class</span>
<span class="yellow">WordPressDeveloper</span>
</div>

<div>
<span class="line">03</span>
{
</div>

<div>
<span class="line">04</span>
&nbsp;&nbsp;
<span class="blue">public</span>
$experience =
<span class="green">"8+ years"</span>;
</div>

<div>
<span class="line">05</span>
&nbsp;&nbsp;
<span class="blue">public</span>
$speciality =
<span class="green">"WordPress"</span>;
</div>

<div>
<span class="line">06</span>
&nbsp;&nbsp;
<span class="blue">public</span>
$focus =
<span class="green">"Performance"</span>;
</div>

<div>
<span class="line">07</span>
}
</div>

<div>
<span class="line">08</span>
</div>

<div>
<span class="line">09</span>
<span class="purple">echo</span>
<span class="green">
"Let's build something amazing!";
</span>
</div>

</div>

</div>


<div class="floating float-one">

<i class="fab fa-wordpress"></i>

<div>
<strong>WordPress</strong>
<small>Expert Developer</small>
</div>

</div>


<div class="floating float-two">

<i class="fas fa-gauge-high"></i>

<div>
<strong>98/100</strong>
<small>Performance</small>
</div>

</div>

</div>

</div>

</section>


<!-- =====================================================
     ABOUT
===================================================== -->

<section id="about">

<div class="container">

<div>
<span class="section-label">
ABOUT ME
</span>

<h2 class="section-title">
Turning ideas into
<span>high-performing websites.</span>
</h2>
</div>


<div class="about-grid" style="margin-top:55px">

<div class="profile-box">
<i class="fas fa-code"></i>
</div>

<div class="about-content">

<p class="lead">
I'm a Senior WordPress Developer passionate about creating
fast, scalable and conversion-focused websites.
</p>

<p>
I specialize in custom WordPress development, custom themes,
plugins, Elementor, WooCommerce, API integrations and
website performance optimization.
</p>

<p>
My focus is clean code, responsive design, security,
performance and creating solutions that are easy to manage.
</p>

<div class="check-list">

<div>
<i class="fas fa-check"></i>
Custom WordPress Development
</div>

<div>
<i class="fas fa-check"></i>
Elementor & Elementor Pro
</div>

<div>
<i class="fas fa-check"></i>
WooCommerce Development
</div>

<div>
<i class="fas fa-check"></i>
Custom Plugin Development
</div>

</div>

</div>

</div>

</div>

</section>


<!-- =====================================================
     SKILLS
===================================================== -->

<section id="skills" class="dark-section">

<div class="container">

<div class="center">

<span class="section-label">
TECHNICAL EXPERTISE
</span>

<h2 class="section-title">
Skills &
<span>Technologies</span>
</h2>

<p class="section-description">
Technologies I use to build modern, scalable and
high-performance WordPress websites.
</p>

</div>


<div class="skills">

<div class="skill">

<div class="skill-top">
<strong>WordPress</strong>
<span>98%</span>
</div>

<div class="progress">
<span style="width:98%"></span>
</div>

</div>


<div class="skill">

<div class="skill-top">
<strong>PHP</strong>
<span>92%</span>
</div>

<div class="progress">
<span style="width:92%"></span>
</div>

</div>


<div class="skill">

<div class="skill-top">
<strong>JavaScript</strong>
<span>88%</span>
</div>

<div class="progress">
<span style="width:88%"></span>
</div>

</div>


<div class="skill">

<div class="skill-top">
<strong>HTML / CSS</strong>
<span>96%</span>
</div>

<div class="progress">
<span style="width:96%"></span>
</div>

</div>


<div class="skill">

<div class="skill-top">
<strong>WooCommerce</strong>
<span>94%</span>
</div>

<div class="progress">
<span style="width:94%"></span>
</div>

</div>


<div class="skill">

<div class="skill-top">
<strong>MySQL</strong>
<span>88%</span>
</div>

<div class="progress">
<span style="width:88%"></span>
</div>

</div>

</div>


<div class="tech-list">

<span>WordPress</span>
<span>PHP</span>
<span>JavaScript</span>
<span>HTML5</span>
<span>CSS3</span>
<span>Elementor</span>
<span>WooCommerce</span>
<span>MySQL</span>
<span>Git</span>
<span>REST API</span>

</div>

</div>

</section>


<!-- =====================================================
     SERVICES
===================================================== -->

<section id="services">

<div class="container">

<span class="section-label">
WHAT I DO
</span>

<h2 class="section-title">
WordPress
<span>Development Services</span>
</h2>


<div class="services">

<div class="service">

<div class="service-icon">
<i class="fab fa-wordpress"></i>
</div>

<h3>
Custom WordPress Development
</h3>

<p>
Custom WordPress websites developed around your
business requirements and goals.
</p>

</div>


<div class="service">

<div class="service-icon">
<i class="fas fa-puzzle-piece"></i>
</div>

<h3>
Plugin Development
</h3>

<p>
Secure and scalable custom WordPress plugins with
admin interfaces, AJAX and API integrations.
</p>

</div>


<div class="service">

<div class="service-icon">
<i class="fas fa-cart-shopping"></i>
</div>

<h3>
WooCommerce Development
</h3>

<p>
Custom eCommerce solutions with product,
checkout and payment functionality.
</p>

</div>


<div class="service">

<div class="service-icon">
<i class="fas fa-gauge-high"></i>
</div>

<h3>
Performance Optimization
</h3>

<p>
Improve Core Web Vitals, loading speed, database
performance and overall website experience.
</p>

</div>

</div>

</div>

</section>


<!-- =====================================================
     PROJECTS
===================================================== -->

<section id="projects" class="dark-section">

<div class="container">

<span class="section-label">
SELECTED WORK
</span>

<h2 class="section-title">
Featured
<span>Projects</span>
</h2>


<div class="project-grid">

<div class="project">

<div class="project-image project-one">
WORDPRESS
</div>

<div class="project-content">

<span>WORDPRESS</span>
<span>ELEMENTOR</span>

<h3>
Corporate Business Website
</h3>

<p>
Modern corporate website with custom WordPress
architecture and Elementor.
</p>

</div>

</div>


<div class="project">

<div class="project-image project-two">
ECOMMERCE
</div>

<div class="project-content">

<span>WOOCOMMERCE</span>
<span>PHP</span>

<h3>
Premium eCommerce Store
</h3>

<p>
Custom WooCommerce store with advanced product
and checkout functionality.
</p>

</div>

</div>


<div class="project">

<div class="project-image project-three">
PLUGIN
</div>

<div class="project-content">

<span>PLUGIN</span>
<span>AJAX</span>

<h3>
Custom Business Plugin
</h3>

<p>
Advanced WordPress plugin with custom admin
panels and API integration.
</p>

</div>

</div>


<div class="project">

<div class="project-image project-four">
CUSTOM THEME
</div>

<div class="project-content">

<span>WORDPRESS</span>
<span>PHP</span>

<h3>
Technology Company Website
</h3>

<p>
Fully custom responsive WordPress theme developed
from Figma designs.
</p>

</div>

</div>

</div>

</div>

</section>


<!-- =====================================================
     EXPERIENCE
===================================================== -->

<section id="experience">

<div class="container">

<div class="center">

<span class="section-label">
CAREER
</span>

<h2 class="section-title">
Professional
<span>Experience</span>
</h2>

</div>


<div class="timeline">

<div class="timeline-item">

<div class="timeline-date">
2023 — Present
</div>

<div class="timeline-dot"></div>

<div class="timeline-content">

<h3>
Senior WordPress Developer
</h3>

<h4>
Digital Agency / Technology Company
</h4>

<p>
Leading WordPress development projects, custom plugin
development, architecture decisions and performance
optimization.
</p>

</div>

</div>


<div class="timeline-item">

<div class="timeline-date">
2020 — 2023
</div>

<div class="timeline-dot"></div>

<div class="timeline-content">

<h3>
WordPress Developer
</h3>

<h4>
Web Development Agency
</h4>

<p>
Developed custom WordPress websites, WooCommerce
stores, Elementor websites and custom integrations.
</p>

</div>

</div>


<div class="timeline-item">

<div class="timeline-date">
2018 — 2020
</div>

<div class="timeline-dot"></div>

<div class="timeline-content">

<h3>
Web Developer
</h3>

<h4>
Web Solutions Company
</h4>

<p>
Built responsive websites using HTML, CSS,
JavaScript, PHP and WordPress.
</p>

</div>

</div>

</div>

</div>

</section>


<!-- =====================================================
     CONTACT
===================================================== -->

<section id="contact" class="dark-section">

<div class="container contact-grid">


<div class="contact-info">

<span class="section-label">
GET IN TOUCH
</span>

<h2>
Have a WordPress
<span>project in mind?</span>
</h2>

<p>
Let's discuss your project, requirements and business
goals. I'll help you build a fast and scalable solution.
</p>


<div class="contact-item">

<div class="contact-icon">
<i class="fas fa-envelope"></i>
</div>

<div>
<small>EMAIL</small>
<span>sudeepjha85@gmail.com</span>
</div>

</div>


<div class="contact-item">

<div class="contact-icon">
<i class="fas fa-phone"></i>
</div>

<div>
<small>PHONE</small>
<span>+91 99999 99999</span>
</div>

</div>


<div class="contact-item">

<div class="contact-icon">
<i class="fas fa-location-dot"></i>
</div>

<div>
<small>LOCATION</small>
<span>India</span>
</div>

</div>


<div class="social">

<a href="#" aria-label="LinkedIn">
<i class="fab fa-linkedin-in"></i>
</a>

<a href="#" aria-label="GitHub">
<i class="fab fa-github"></i>
</a>

<a href="#" aria-label="WordPress">
<i class="fab fa-wordpress"></i>
</a>

<a href="#" aria-label="Twitter">
<i class="fab fa-x-twitter"></i>
</a>

</div>

</div>


<!-- =====================================================
     CONTACT FORM
===================================================== -->

<form
    class="contact-form"
    method="POST"
    action="#contact"
>


<?php if ($formMessage): ?>

<div class="form-message <?php echo $formSuccess ? 'success' : 'error'; ?>">

<?php echo htmlspecialchars($formMessage); ?>

</div>

<?php endif; ?>


<div class="form-row">

<div class="form-group">

<label for="name">
Your Name
</label>

<input
    type="text"
    id="name"
    name="name"
    placeholder="John Doe"
    value="<?php echo htmlspecialchars($name ?? ''); ?>"
    required
>

</div>


<div class="form-group">

<label for="email">
Email Address
</label>

<input
    type="email"
    id="email"
    name="email"
    placeholder="john@example.com"
    value="<?php echo htmlspecialchars($email ?? ''); ?>"
    required
>

</div>

</div>


<div class="form-row">

<div class="form-group">

<label for="phone">
Phone Number
</label>

<input
    type="tel"
    id="phone"
    name="phone"
    placeholder="+91 98765 43210"
    value="<?php echo htmlspecialchars($phone ?? ''); ?>"
    required
>

</div>


<div class="form-group">

<label for="subject">
Subject
</label>

<input
    type="text"
    id="subject"
    name="subject"
    placeholder="WordPress Project"
    value="<?php echo htmlspecialchars($subject ?? ''); ?>"
    required
>

</div>

</div>


<div class="form-group">

<label for="message">
Message
</label>

<textarea
    id="message"
    name="message"
    placeholder="Tell me about your project..."
    required
><?php echo htmlspecialchars($message ?? ''); ?></textarea>

</div>


<button
    type="submit"
    class="btn btn-primary"
>

Send Message

<i class="fas fa-paper-plane"></i>

</button>

</form>

</div>

</section>


<!-- =====================================================
     FOOTER
===================================================== -->

<footer>

<div class="container footer">

<p>
© <span id="year"></span>
Sudeep. All Rights Reserved.
</p>

<p>
Senior WordPress Developer
</p>

</div>

</footer>


<script>

/* =====================================================
   HEADER
===================================================== */

const header = document.getElementById("header");

window.addEventListener("scroll", function() {

    if (window.scrollY > 50) {

        header.classList.add("scrolled");

    } else {

        header.classList.remove("scrolled");

    }

});


/* =====================================================
   MOBILE MENU
===================================================== */

const menuBtn = document.getElementById("menuBtn");
const navLinks = document.getElementById("navLinks");

menuBtn.addEventListener("click", function() {

    navLinks.classList.toggle("open");

    const icon = menuBtn.querySelector("i");

    if (navLinks.classList.contains("open")) {

        icon.classList.remove("fa-bars");
        icon.classList.add("fa-xmark");

    } else {

        icon.classList.remove("fa-xmark");
        icon.classList.add("fa-bars");

    }

});


/* Close mobile menu */

document.querySelectorAll(".nav-links a").forEach(function(link) {

    link.addEventListener("click", function() {

        navLinks.classList.remove("open");

        const icon = menuBtn.querySelector("i");

        icon.classList.remove("fa-xmark");
        icon.classList.add("fa-bars");

    });

});


/* =====================================================
   ACTIVE MENU
===================================================== */

const sections = document.querySelectorAll("section[id]");
const links = document.querySelectorAll(".nav-links a");

window.addEventListener("scroll", function() {

    let current = "";

    sections.forEach(function(section) {

        const top = section.offsetTop - 150;

        if (window.scrollY >= top) {

            current = section.getAttribute("id");

        }

    });

    links.forEach(function(link) {

        link.classList.remove("active");

        if (
            link.getAttribute("href") === "#" + current
        ) {

            link.classList.add("active");

        }

    });

});


/* =====================================================
   YEAR
===================================================== */

document.getElementById("year").textContent =
    new Date().getFullYear();


/* =====================================================
   AUTO HIDE FORM MESSAGE
===================================================== */

setTimeout(function() {

    const message =
        document.querySelector(".form-message");

    if (message) {

        message.style.opacity = "0";

        message.style.transition = ".5s";

    }

}, 6000);

</script>

</body>
</html>
