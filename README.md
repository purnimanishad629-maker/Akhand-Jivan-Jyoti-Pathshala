
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Akhand Jivan Jyoti Pathshala</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        *{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}
        body{background:#fef9e8;color:#1e2a3e;}
        .container{max-width:1200px;margin:auto;padding:0 20px;}
        .navbar{background:white;box-shadow:0 4px 12px rgba(0,0,0,0.05);position:sticky;top:0;}
        .nav-flex{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;padding:15px 0;}
        .logo h1{font-size:1.6rem;color:#c0392b;}
        .logo p{font-size:0.8rem;color:#f39c12;}
        .nav-links{display:flex;gap:25px;list-style:none;}
        .nav-links a{text-decoration:none;color:#2c3e50;font-weight:500;}
        .hero{background:linear-gradient(135deg,#fff5e6,#ffe6d5);padding:70px 0;text-align:center;}
        .hero h2{font-size:2.8rem;color:#b03a2e;}
        .btn{padding:12px 28px;border-radius:40px;text-decoration:none;font-weight:600;display:inline-block;}
        .btn-primary{background:#e67e22;color:white;}
        .btn-outline{border:2px solid #e67e22;color:#e67e22;}
        section{padding:70px 0;}
        .section-title{font-size:2.2rem;text-align:center;margin-bottom:50px;position:relative;}
        .section-title:after{content:'';width:80px;height:4px;background:#e67e22;display:block;margin:12px auto 0;}
        .facilities-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:30px;}
        .facility-card{background:white;padding:25px;text-align:center;border-radius:20px;box-shadow:0 5px 15px rgba(0,0,0,0.05);}
        .stats-row{display:flex;flex-wrap:wrap;justify-content:space-around;background:#2c3e50;padding:50px;border-radius:30px;color:white;text-align:center;}
        .why-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:25px;}
        .principal-message{background:#fff1e6;border-radius:30px;padding:40px;text-align:center;}
        .contact-info{background:#2c3e50;color:white;border-radius:30px;padding:40px;text-align:center;}
        footer{background:#1e2a3e;color:#aaa;text-align:center;padding:25px;}
        @media (max-width:768px){.hero h2{font-size:2rem;}}
    </style>
</head>
<body>
<div class="navbar">
    <div class="container nav-flex">
        <div class="logo">
            <h1>AKHAND JIVAN<br>JYOTI PATHSHALA</h1>
            <p>Nurturing Minds, Shaping Futures</p>
        </div>
        <ul class="nav-links">
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Facilities</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </div>
</div>

<div class="hero">
    <div class="container">
        <h2>Welcome to <br><span style="color:#f39c12;">Akhand Jivan Jyoti Pathshala</span></h2>
        <p>A place where learning is joyful, values are strong, and every child shines bright.</p>
        <div class="btn-group">
            <a href="#" class="btn btn-primary">Discover More</a>
            <a href="#" class="btn btn-outline">Virtual Tour</a>
        </div>
    </div>
</div>
<section>
    <div class="container">
        <div class="section-title">About Us</div>
        <div class="about-text" style="text-align:center;max-width:800px;margin:auto;">
            <p>We provide quality education, discipline, and a supportive environment to help every student grow and succeed.</p>
            <a href="#" style="color:#e67e22;">Read More →</a>
        </div>
    </div>
</section>

<section style="background:#fffaf5;">
    <div class="container">
        <div class="section-title">Our Facilities</div>
        <div class="facilities-grid">
            <div class="facility-card"><i class="fas fa-chalkboard-user"></i><h3>Spacious Classrooms</h3></div>
            <div class="facility-card"><i class="fas fa-flask"></i><h3>Science & Computer Labs</h3></div>
            <div class="facility-card"><i class="fas fa-book"></i><h3>Library & Reading Room</h3></div>
            <div class="facility-card"><i class="fas fa-futbol"></i><h3>Sports & Playground</h3></div>
            <div class="facility-card"><i class="fas fa-video"></i><h3>CCTV & Safe Campus</h3></div>
        </div>
        <div style="text-align:center;margin-top:30px;"><a href="#" class="btn btn-outline">Explore More</a></div>
    </div>
</section>
<section>
    <div class="container">
        <div class="section-title">Memories</div>
        <div class="stats-row">
            <div class="stat-item"><h3>25+</h3><p>Awards Won</p></div>
            <div class="stat-item"><h3>1100+</h3><p>Students Enrolled</p></div>
            <div class="stat-item"><h3>25+</h3><p>Experienced Teachers</p></div>
            <div class="stat-item"><h3>98%</h3><p>Result Success</p></div>
        </div>
        <div style="text-align:center;margin-top:30px;"><a href="#" class="btn btn-outline">View All Memories</a></div>
    </div>
</section>

<section style="background:#fffaf5;">
    <div class="container">
        <div class="section-title">Why Choose Us?</div>
        <div class="why-grid">
            <div class="why-item"><i class="fas fa-chalkboard-user"></i><h3>Experienced Teachers</h3></div>
            <div class="why-item"><i class="fas fa-brain"></i><h3>Holistic Development</h3></div>
            <div class="why-item"><i class="fas fa-building"></i><h3>Modern Infrastructure</h3></div>
            <div class="why-item"><i class="fas fa-palette"></i><h3>Co-curricular Activities</h3></div>
            <div class="why-item"><i class="fas fa-shield-alt"></i><h3>Safe & Secure</h3></div>
            <div class="why-item"><i class="fas fa-user-graduate"></i><h3>Personalized Attention</h3></div>
        </div>
    </div>
</section>
<div class="container principal-message">
    <i class="fas fa-quote-left" style="font-size:2rem;color:#e67e22;"></i>
    <p>Our mission is to inspire students to achieve excellence in academics and character. Together, let’s build a brighter tomorrow.</p>
    <h3>Jahnavi Goyal</h3>
    <p>Principal</p>
</div>

<section style="background:#fffaf5;">
    <div class="container">
        <div class="section-title">At A Glance</div>
        <div class="why-grid">
            <div><i class="fas fa-smile"></i><h3>2000+</h3><p>Happy Alumni</p></div>
            <div><i class="fas fa-award"></i><h3>15+</h3><p>Years of Excellence</p></div>
            <div><i class="fas fa-music"></i><h3>10+</h3><p>Extracurricular Clubs</p></div>
            <div><i class="fas fa-desktop"></i><h3>5+</h3><p>Smart Classrooms</p></div>
        </div>
    </div>
</section>
<div class="container contact-info">
    <h3><i class="fas fa-map-marker-alt"></i> Address:</h3>
    <p>AJJP Raigani, GKP</p>
    <p><i class="fas fa-phone-alt"></i> 7054001284</p>
    <p><i class="fas fa-envelope"></i> ajjprrajgani@gmail.com</p>
    <div class="social-icons" style="margin-top:20px;">
        <a href="#" style="color:white;margin:0 12px;"><i class="fab fa-facebook-f"></i></a>
        <a href="#" style="color:white;margin:0 12px;"><i class="fab fa-instagram"></i></a>
        <a href="#" style="color:white;margin:0 12px;"><i class="fab fa-youtube"></i></a>
    </div>
</div>

<footer>
    <p>© 2024 Akhand Jivan Jyoti Pathshala. All Rights Reserved.</p>
</footer>

</body>
</html>
