# maom-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stunning Website</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            color: #333;
            background-color: #f4f4f4;
        }
        header {
            background: linear-gradient(135deg, #6e45e2, #88d3ce);
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            font-size: 3em;
            margin: 0;
        }
        nav {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            position: sticky;
            top: 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2em;
        }
        section {
            padding: 50px 20px;
            text-align: center;
        }
        section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        section p {
            font-size: 1.2em;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
        }
        .highlight {
            background-color: #88d3ce;
            padding: 10px;
            border-radius: 8px;
            display: inline-block;
            color: #333;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        footer p {
            margin: 0;
        }
        /* Responsive design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }
            section h2 {
                font-size: 2em;
            }
            section p {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Stunning Website</h1>
        <p>Where creativity meets code</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Us</h2>
        <p>
            We are a team of passionate developers and designers committed to delivering high-quality websites that captivate and engage users. 
            <span class="highlight">Our focus</span> is on crafting experiences that make an impact!
        </p>
    </section>

    <section id="services" style="background-color: #eee;">
        <h2>Our Services</h2>
        <p>
            We offer a range of services from web design, front-end development, to full-stack solutions. 
            Whether you're building a portfolio or a large-scale application, we’ve got you covered!
        </p>
    </section>

    <section id="contact">
        <h2>Get In Touch</h2>
        <p>
            Interested in working with us? Drop us a message and let's build something amazing together!
        </p>
    </section>

    <footer>
        <p>&copy; 2024 Stunning Website. All Rights Reserved.</p>
    </footer>

</body>
</html>
