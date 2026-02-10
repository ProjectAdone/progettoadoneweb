<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Progetto Adone - Welcome</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            transition: opacity 0.3s;
        }

        nav a:hover {
            opacity: 0.8;
        }

        main {
            margin-top: 70px;
        }

        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 6rem 2rem;
            text-align: center;
            min-height: 500px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            opacity: 0.9;
        }

        .cta-button {
            display: inline-block;
            background: white;
            color: #667eea;
            padding: 0.8rem 2rem;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 4rem 2rem;
        }

        .feature-card {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s;
        }

        .feature-card:hover {
            transform: translateY(-5px);
        }

        .feature-card h3 {
            color: #667eea;
            margin-bottom: 1rem;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 3rem;
        }

        footer p {
            margin: 0.5rem 0;
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }

            nav ul {
                gap: 1rem;
            }

            nav {
                padding: 0 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">Progetto Adone</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero" id="home">
            <h1>Welcome to Progetto Adone</h1>
            <p>Build something amazing with us</p>
            <a href="#features" class="cta-button">Get Started</a>
        </section>

        <section id="features">
            <div class="container">
                <h2 style="text-align: center; margin-bottom: 2rem; font-size: 2rem;">Features</h2>
                <div class="features">
                    <div class="feature-card">
                        <h3>Fast & Reliable</h3>
                        <p>Experience lightning-fast performance with our optimized infrastructure.</p>
                    </div>
                    <div class="feature-card">
                        <h3>User Friendly</h3>
                        <p>Intuitive interface designed for users of all skill levels.</p>
                    </div>
                    <div class="feature-card">
                        <h3>Secure</h3>
                        <p>Your data is protected with industry-standard security measures.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="about" style="background: #f9f9f9; padding: 4rem 2rem;">
            <div class="container">
                <h2 style="margin-bottom: 1rem;">About Us</h2>
                <p>Progetto Adone is dedicated to delivering exceptional web experiences. We combine cutting-edge technology with thoughtful design to create solutions that matter.</p>
            </div>
        </section>
    </main>

    <footer id="contact">
        <p>&copy; 2026 Progetto Adone. All rights reserved.</p>
        <p>Email: info@progettoadone.com</p>
        <p>Follow us on social media for updates and news.</p>
    </footer>
</body>
</html>
