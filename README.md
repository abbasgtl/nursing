<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nursing Services Kadapa | Professional Home Healthcare</title>
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@400;700&family=Montserrat:wght@600;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    
    <style>
        :root {
            --primary: #0056b3;
            --secondary: #28a745;
            --dark: #343a40;
            --light: #f8f9fa;
            --white: #ffffff;
            --shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Lato', sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background-color: var(--light);
        }

        h1, h2, h3 {
            font-family: 'Montserrat', sans-serif;
            text-transform: uppercase;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header */
        header {
            background: var(--white);
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: var(--shadow);
        }

        .nav-flex {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 800;
            color: var(--primary);
            text-decoration: none;
        }

        .phone-btn {
            background: var(--secondary);
            color: var(--white);
            padding: 10px 20px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
            display: inline-flex;
            align-items: center;
            gap: 10px;
        }

        .phone-btn:hover {
            background: #218838;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                        url('https://images.unsplash.com/photo-1576765608535-5f04d1e3f289?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: var(--white);
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 25px;
        }

        /* Services Grid */
        .section-padding {
            padding: 80px 0;
        }

        .section-title {
            text-align: center;
            margin-bottom: 50px;
        }

        .section-title h2 {
            font-size: 2.5rem;
            color: var(--primary);
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .card {
            background: var(--white);
            padding: 40px;
            border-radius: 10px;
            box-shadow: var(--shadow);
            border-top: 5px solid var(--primary);
            height: 100%;
        }

        .card i {
            font-size: 3rem;
            color: var(--secondary);
            margin-bottom: 20px;
        }

        .card h3 {
            margin-bottom: 20px;
            color: var(--primary);
        }

        .card ul {
            list-style: none;
        }

        .card ul li {
            margin-bottom: 12px;
            padding-left: 25px;
            position: relative;
        }

        .card ul li::before {
            content: "✔";
            position: absolute;
            left: 0;
            color: var(--secondary);
            font-weight: bold;
        }

        /* Image Gallery */
        .gallery {
            background: #fff;
            padding: 80px 0;
        }

        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .gallery-item {
            border-radius: 8px;
            overflow: hidden;
            box-shadow: var(--shadow);
            background: #eee;
        }

        .gallery-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            display: block;
        }

        .caption {
            padding: 15px;
            text-align: center;
            font-weight: bold;
            background: var(--white);
            color: var(--primary);
        }

        /* Footer */
        footer {
            background: var(--dark);
            color: var(--white);
            padding: 40px 0;
            text-align: center;
        }

        .footer-info {
            font-size: 1.2rem;
            margin-bottom: 10px;
        }

        /* Mobile Adjustments */
        @media (max-width: 768px) {
            .hero h1 { font-size: 2rem; }
            .nav-flex { flex-direction: column; gap: 15px; }
            .section-padding { padding: 40px 0; }
        }
    </style>
</head>
<body>

    <header>
        <div class="container nav-flex">
            <a href="#" class="logo">Nursing Services Kadapa</a>
            <a href="tel:09642566400" class="phone-btn">
                <i class="fas fa-phone-alt"></i> 09642566400
            </a>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>Nursing Services at your Door Step</h1>
            <p>Professional healthcare delivered with compassion in the comfort of your home.</p>
            <a href="tel:09642566400" class="phone-btn" style="padding: 15px 40px; font-size: 1.2rem;">Book a Visit Now</a>
        </div>
    </section>

    <section class="container section-padding">
        <div class="section-title">
            <h2>Our Specialized Care</h2>
        </div>
        
        <div class="services-grid">
            <div class="card">
                <i class="fas fa-user-nurse"></i>
                <h3>Nurse Visit</h3>
                <ul>
                    <li>Injection or Intravenous (IV) Medication</li>
                    <li>Assisting With Catheters, Oxygen Equipment, or Feeding Tubes</li>
                    <li>Home Assessment</li>
                    <li>Wound Care</li>
                    <li>Nebulization</li>
                </ul>
            </div>

            <div class="card">
                <i class="fas fa-heartbeat"></i>
                <h3>Critical Care Nursing</h3>
                <ul>
                    <li>Post Operative Care</li>
                    <li>Patient Monitoring and Assessment</li>
                    <li>Managing Life Support Equipment</li>
                    <li>Emergency Response and Intervention</li>
                </ul>
            </div>

            <div class="card">
                <i class="fas fa-house-user"></i>
                <h3>Home Nursing Care</h3>
                <ul>
                    <li>Nursing Caregiving</li>
                    <li>Medicine Administration</li>
                    <li>Mobility Support</li>
                    <li>Vital Monitoring</li>
                    <li>Urinary Catheterisation Care</li>
                    <li>Palliative & Hospice Care At Home</li>
                    <li>Wound Care</li>
                    <li>Stroke Rehabilitation at Home</li>
                    <li>Ensuring Patient Safety</li>
                </ul>
            </div>
        </div>
    </section>

    <section class="gallery">
        <div class="container">
            <div class="section-title">
                <h2>Clinical Procedures</h2>
            </div>
            <div class="gallery-grid">
                <div class="gallery-item">
                    
                    <div class="caption">Wound Care Services</div>
                </div>
                <div class="gallery-item">
                    
                    <div class="caption">Injection & IV Medication</div>
                </div>
                <div class="gallery-item">
                    
                    <div class="caption">Vital Monitoring</div>
                </div>
                <div class="gallery-item">
                    
                    <div class="caption">Nebulization Treatment</div>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <h3>Nursing Services Kadapa</h3>
            <p class="footer-info">Professional care at your door step</p>
            <p class="footer-info"><i class="fas fa-phone-alt"></i> Please reach me @ 09642566400</p>
            <div style="margin-top: 30px; opacity: 0.7; font-size: 0.9rem;">
                &copy; 2026 Nursing Services Kadapa. All Rights Reserved.
            </div>
        </div>
    </footer>

</body>
</html>
