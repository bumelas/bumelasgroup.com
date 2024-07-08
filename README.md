# HTML content
html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bumelas Group Ltd</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bumelas Group Ltd</h1>
        <p>P.O. Box 2411, Pongwe Street, Tanga, Tanzania | Phone: +255 674 000 553</p>
    </header>

    <nav>
        <a href="#about">About Us</a>
        <a href="#agrovet">Agrovet</a>
        <a href="#beverage">Beverage</a>
        <a href="#finance">Finance</a>
        <a href="#logistic">Logistic</a>
        <a href="#realestate">Real Estate</a>
        <a href="#industries">Industries</a>
        <a href="#mining">Mining</a>
        <a href="#contact">Contact Us</a>
    </nav>

    <div class="container">
        <section id="about" class="section">
            <h2>About Us</h2>
            <p>Welcome to Bumelas Group Ltd, a diversified conglomerate based in Tanga, Tanzania. We operate in various sectors including agriculture, beverages, finance, logistics, real estate, industries, and mining.</p>
        </section>

        <section id="agrovet" class="section">
            <h2>Bumelas Group Agrovet</h2>
            <p>Our Agrovet section focuses on sustainable agricultural practices and products.</p>
        </section>

        <section id="beverage" class="section">
            <h2>Bumelas Group Beverage</h2>
            <p>We produce high-quality beverages including soft drinks and mineral water.</p>
        </section>

        <section id="finance" class="section">
            <h2>Bumelas Group Finance</h2>
            <p>Providing financial services and investment opportunities to help grow your wealth.</p>
        </section>

        <section id="logistic" class="section">
            <h2>Bumelas Group Logistic</h2>
            <p>Efficient logistics solutions for transportation and warehousing needs.</p>
        </section>

        <section id="realestate" class="section">
            <h2>Bumelas Group Real Estate</h2>
            <p>Developing and selling prime real estate properties.</p>
        </section>

        <section id="industries" class="section">
            <h2>Bumelas Group Industries</h2>
            <p>Advanced manufacturing capabilities for various industrial products.</p>
        </section>

        <section id="mining" class="section">
            <h2>Bumelas Group Mining</h2>
            <p>Responsible mining practices to extract and process minerals.</p>
        </section>

        <section id="contact" class="section">
            <h2>Contact Us</h2>
            <p>For inquiries, please contact us at info@bumelasgroup.com or call +255 674 000 553.</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Bumelas Group Ltd. All rights reserved.</p>
        <p>Follow us on <a href="#" style="color: white;">LinkedIn</a>, <a href="#" style="color: white;">Facebook</a>, <a href="#" style="color: white;">Twitter</a></p>
    </footer>
</body>
</html>
"""

# CSS content
css_content = """
/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

header, footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em 0;
}

nav {
    display: flex;
    justify-content: center;
    background-color: #444;
}

nav a {
    color: white;
    padding: 14px 20px;
    text-decoration: none;
    display: inline-block;
}

nav a:hover {
    background-color: #555;
}

.container {
    padding: 20px;
    max-width: 1200px;
    margin: 0 auto;
}

.section {
    margin: 20px 0;
}

.section h2 {
    background-color: #f4f4f4;
    padding: 10px;
    border-left: 5px solid #333;
}

.section p {
    padding: 10px;
    background-color: #f9f9f9;
    border: 1px solid #ddd;
}

footer p {
    margin: 5px 0;
}

footer a {
    color: white;
    text-decoration: underline;
}

footer a:hover {
    text-decoration: none;
}

/* Media Queries for Responsive Design */
@media (max-width: 768px) {
    nav {
        flex-direction: column;
    }

    nav a {
        padding: 10px;
        border-top: 1px solid #555;
        border-bottom: 1px solid #555;
    }

    .section h2, .section p {
        padding: 15px;
    }
}

@media (max-width: 480px) {
    nav a {
        padding: 8px;
    }

    .section h2, .section p {
        padding: 10px;
    }
}
"""


