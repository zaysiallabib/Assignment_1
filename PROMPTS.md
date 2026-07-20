<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DevConf 2026</title>

    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap"
        rel="stylesheet">

    <link rel="stylesheet" href="style.css">
</head>

<body>
    <!-- Navbar -->
    <header>
        <div class="container">
            <nav class="navbar">
                <a href="#">
                    <img src="assets/logo.png" alt="DevConf 2026 Logo">
                </a>
                
                <ul class="nav-links">
                    <li><a href="#">Speakers</a></li>
                    <li><a href="#">Schedule</a></li>
                    <li><a href="#">Tracks</a></li>
                    <li><a href="#">Venue</a></li>
                    <li><a href="#">Blog</a></li>
                </ul>

                <a href="#" class="nav-btn">
                    Register Now
                </a>
            </nav>

        </div>
    </header>

    <!-- Hero -->

    <section class="hero">
        <div class="overlay">
            <div class="container">
                <div class="hero-content">
                    <h1>
                        Code.
                        <em>Connect.</em>
                        Create
                    </h1>

                    <p>
                        Join over 4,000 engineers, founders and builders at the premier developer conference of 2026. Experience three unforgettable days filled with inspiring talks, practical workshops and meaningful networking opportunities with people shaping the future of technology.
                    </p>

                    <a href="#" class="hero-btn">
                        Register Now
                    </a>

                </div>
            </div>
        </div>
    </section>

    <!-- Speakers -->

    <section class="speakers">
        <div class="container">
            <div class="section-title">
                <h2>Meet the Speakers</h2>
            </div>

            <div class="speaker-grid">

            <!-- Speaker 1 -->

                <div class="speaker-card">
                    <img src="assets/andrej.png" alt="Andrej Karpathy">

                    <span class="specialty">
                        AI / ML
                    </span>

                    <h3>
                        Andrej Karpathy
                    </h3>

                    <p>
                        Pretraining Team, Anthropic
                    </p>

                </div>





            <!-- Speaker 2 -->

                <div class="speaker-card">

                    <!-- Replace with speaker2.jpg -->

                    <img src="assets/demis.png" alt="Demis Hassabis">

                    <span class="specialty">
                        Cloud &amp; DevOps
                    </span>

                    <h3>
                        Demis Hassabis
                    </h3>

                    <p>
                        Co-Founder &amp; CEO, Google DeepMind
                    </p>
                </div>

            <!-- Speaker 3 -->

                <div class="speaker-card">
                    <img src="assets/gary.png" alt="Gary Marcus">
                    <span class="specialty">
                        Frontend
                    </span>

                    <h3>
                        Gary Marcus
                    </h3>

                    <p>
                        Staff Engineer, Vercel
                    </p>
                </div>

            <!-- Speaker 4 -->

                <div class="speaker-card">
                    <img src="assets/mustafa.png" alt="Mustafa Suleyman">

                    <span class="specialty">
                        Security
                    </span>
                    <h3>
                        Mustafa Suleyman
                    </h3>

                    <p>
                        CEO of Microsoft AI
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Price -->

    <section class="pricing">
        <div class="container">
            <div class="section-title">

                <h2>Secure Your Spot</h2>
                <p>
                    Early-bird pricing ends August 15, 2026.
                </p>
            </div>

            <div class="pricing-cards">

                <!-- Standard -->

                <div class="standard">

                    <div class="standard">
                        <span>STANDARD</span>

                        <h1>$399</h1>

                        <span>
                            per person
                        </span>

                        <hr class="divider">

                        <ul>

                            <li>Access to all 3 conference days</li>

                            <li>48 curated technical talks</li>
                            <li>2 workshop sessions</li>

                            <li>Networking lunch &amp; coffee breaks</li>

                            <li>Conference swag bag</li>
                            <li>Digital recordings (30 days)</li>

                        </ul>

                        <a href="#">
                            Get Standard
                        </a>
                    </div>
                </div>

                <!-- Pro -->

                <div class="standard pro">

                    <span>PRO</span>
                    <h1>$749</h1>

                    <span>per person</span>
                    <hr class="divider">

                    <ul>

                        <li>Everything in Standard</li>

                        <li>Unlimited workshop access</li>

                        <li>Speaker meet &amp; greet</li>
                        <li>VIP networking dinner</li>

                        <li>Lifetime recording access</li>
                        <li>1-on-1 mentorship (30 min)</li>

                    </ul>

                    <a href="#">
                        Get Pro
                    </a>
                </div>

            <!-- Team -->

                <div class="standard team">

                    <span>TEAM</span>

                    <h1>$5,999</h1>

                    <span>up to 10 people</span>
                    <hr class="divider">

                    <ul>

                        <li>Everything in Pro (10 seats)</li>
                        <li>Dedicated team lounge access</li>

                        <li>Private workshop booking</li>

                        <li>Company logo on event page</li>

                        <li>Recruitment booth (1 day)</li>

                        <li>Priority customer support</li>
                    </ul>

                    <a href="#">
                        Contact Us
                    </a>
                </div>

            </div>
        </div>

    </section>

    <!-- AI generated -->

    
        <!-- Footer -->

    <footer>
            
        <div class="footer">
            <div class="sec">
                <p>
                    &copy; 2026 DevConf. All rights reserved.
                </p>
            </div>

            <div class="footer-links">

                <a href="#">Privacy Policy</a>

                <a href="#">Terms of Service</a>

            </div>

        </div>
    </footer>

</body>
</html>





*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Inter',sans-serif;
    background:#f7f7f7;
    color:#222;
    line-height:1.6;
}

a{
    text-decoration:none;
    color:inherit;
}

img{
    width:100%;
    display:block;
}

ul{
    list-style:none;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}

/* Navbar */

header{
    background:#fff;
    padding:22px 0;
}

.navbar{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:24px;
    font-weight:800;
}

.logo span{
    font-weight:500;
}

.nav-links{
    display:flex;
    gap:35px;
}

.nav-links a{
    font-size:15px;
    transition:.3s;
}

.nav-links a:hover{
    color:#2563eb;
}

.nav-btn{
    background:#2563eb;
    color:#fff;
    padding:12px 35px;
    border-radius:8px;
    font-weight:600;
    transition:.3s;
}

.nav-btn:hover{
    background:#1d4ed8;
}

/* Hero */

.hero{
    background:url("assets/banner.jpg") center/cover no-repeat;
    height:650px;
    position:relative;
}

.overlay{
    background:rgba(0,0,0,.45);
    width:100%;
    height:100%;
    display:flex;
    align-items:center;
    justify-content:center;
}

.hero-content{
    max-width:800px;
    margin:auto;
    text-align:center;
    color:#fff;
    transform: translateY(-50px);
}

.hero-content h1{
    font-size:64px;
    font-weight:800;
    margin-bottom:25px;
    line-height:1.2;
}

.hero-content em{
    font-style:italic;
}

.hero-content p{
    font-size:15px;
    color:#ddd;
    margin-bottom:40px;
    line-height:1.8;
}

.hero-btn{
    transform: translateY(180px);
    display:inline-block;
    background:#2563eb;
    color:#fff;
    padding:12px 50px;
    border-radius:8px;
    font-weight:600;
    transition:.3s;
}

.hero-btn:hover{
    background:#1d4ed8;
}

.section-title{
    text-align:center;
    margin-bottom:55px;
}

.section-title h2{
    font-size:40px;
    margin-bottom:12px;
}

.section-title p{
    color:#666;
    font-size:17px;
}
/* Speakers */

.speakers{
    padding:100px 0;
    background:#fff;
}

.speaker-grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:35px;
}

.speaker-card{
    background:#fff;
    border-radius:12px;
    overflow:hidden;
    box-shadow:0 5px 18px rgba(0,0,0,.08);
    transition:.3s;
}

.speaker-card:hover{
    transform:translateY(-5px);
}

.speaker-card img{
    height:320px;
    object-fit:cover;
}

.specialty{
    display:inline-block;
    margin:20px 10px 12px;
    padding:6px 12px;
    color:#2563eb;
    font-size:13px;
    font-weight:600;
}

.speaker-card h3{
    margin:0 20px 8px;
    font-size:24px;
}

.speaker-card p{
    margin:0 20px 25px;
    color:#666;
    font-size:15px;
    line-height:1.7;
}

/* Pricing */

.pricing{
    padding:100px 0;
    background:#f7f7f7;
}

.pricing-cards{
    display:flex;
    gap:30px;
    justify-content:center;
    align-items:stretch;
}

.standard{
    flex:1;
    background:#fff;
    border-radius:14px;
    padding:35px;
    box-shadow:0 5px 18px rgba(0,0,0,.08);
}


.standard h1{
    font-size:46px;
    margin-bottom:5px;
}

.standard span{
    color:#666;
    font-size:15px;
}
.standard .divider{
    color:#eeecec;
    Transform: translateY(18px);
}

.standard ul{
    margin:30px 0;
    list-style-type: disc;
    padding-left: 20px;
}

.standard li{
    margin-bottom:14px;
    color:#252525;
    font-size:15px;
}
.standard li::marker {
    color: #1d4ed8;}

.standard a{
    display:block;
    text-align:center;
    color:#1d4ed8;
    padding:14px;
    border:1px solid #1d4ed8;
    border-radius:8px;
    font-weight:600;
    transition:.3s;
}

.standard a:hover{
    background:#1d4ed8;
    color:#f6f6f8;
    transition:.3s;
}

.pro{
    background:#131e36;
    color:#fff;
    transform:scale(1.04);
}

.pro span,
.pro li{
    color:#d6d7da;
}

.pro a{
    background:#2563eb;
    color:#fff;
}

.pro a:hover{
    background:#f2f2f2;
    color:#0e1930;
}
.team a{
    color:#152141;
    border:1px solid #152141;
}
/* AI generated */


/* Footer */

.footer, .sec{
    background:#111827;
    color:#838181;
    padding:30px 50px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    font-size:14px;
}


.footer-links{
    display:flex;
    justify-content:flex-end;
    gap:20px;
}

.footer-links a:hover{
    color:#fff;
}




you are an expert frontend designer with years of experience. write me two separate html and css codes for the area marked as "AI generated". be simple and minimalistic.