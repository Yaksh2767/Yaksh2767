<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CHIRO LIFE THERAPY CENTRE</title>
    <style>
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header, nav, section, footer {
            padding: 20px;
            text-align: center;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 20px;
        }
        header .logo {
            width: 150px;
            height: auto;
            display: block;
            margin: 0 auto;
        }
        nav {
            background: #f2f2f2;
            margin: 0;
            padding: 15px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
        }
        .hero {
            background: #4CAF50;
            color: white;
            padding: 60px 20px;
            margin-bottom: 30px;
        }
        .hero h2 {
            font-size: 2.5em;
            margin: 0;
        }
        .hero p {
            font-size: 1.2em;
        }
        .hero button {
            background: white;
            color: #4CAF50;
            border: none;
            padding: 10px 20px;
            font-size: 1em;
            cursor: pointer;
            margin-top: 20px;
        }
        section {
            margin-bottom: 30px;
        }
        section h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }
        section p, section ul {
            font-size: 1.1em;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
        }
        section ul {
            list-style: none;
            padding: 0;
        }
        section ul li {
            background: #eee;
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
        }
        .products img {
            width: 100%;
            max-width: 300px;
            height: auto;
            display: block;
            margin: 20px auto;
            border-radius: 10px;
        }
        .contact form {
            max-width: 600px;
            margin: 0 auto;
            text-align: left;
        }
        .contact form label, .contact form input, .contact form textarea {
            display: block;
            width: 100%;
            margin-bottom: 10px;
        }
        .contact form input, .contact form textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact form input[type="submit"] {
            background: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        footer {
            background: #4CAF50;
            color: white;
            padding: 20px;
        }
        footer a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ3MDcXRKd_WNHdCdwOU6ZOh409CrP_32SsY30XiV1t5L1wsunGOOFfTQH6&s=10"  class="logo">
        <h1>CHIRO LIFE THERAPY CENTRE</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact Us</a>
    </nav>
    <section id="home" class="hero">
        <h2>Welcome to CHIRO LIFE THERAPY CENTRE</h2>
        <p>Your health and wellness are our priority. We provide top-notch therapy services and products to help you achieve optimal well-being.</p>
        <button onclick="window.location.href='#about'">Learn More</button>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>At CHIRO LIFE THERAPY CENTRE, we are committed to offering holistic and effective therapies for a variety of physical and internal ailments. Our dedicated team of professionals is here to help you on your journey to better health.</p>
        <p>Our mission is to provide exceptional therapy services and products that cater to the unique needs of each individual. We believe in a personalized approach to health and wellness, ensuring that every client receives the care they deserve.</p>
    </section>
    <section id="services" class="services">
        <h2>Our Services</h2>
        <ul>
            <li><strong>Belt Therapy:</strong> It is not just limited to abdomen but also on waist, stomach, shoulder, arms, knees, legs</li>
            <li><strong>Mat Therapy:</strong> Migraine, Sinus, Headache, Insomnia, Control Cholesterol, Blood Pressure, Weight Loss, etc.</li>
            <li><strong>Bed Therapy:</strong> arthritis, hunchback(kyphosis), scoliosis, osteoporosis, back pain, knee pain, leg pain, etc.</li>
            <li><strong>Chiropractic Care:</strong> Spinal adjustments to improve alignment and overall health.</li>
        </ul>
    </section>
    <section id="products" class="products">
        <h2>Our Products</h2>
        <ul>
            <li>
                <strong>Automatic Thermal Massage Bed:</strong> Designed for optimal support and comfort.
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT0fzb0Zh538ewF-oSm_YXGz3v58u_o2Po7iIy1RD2bwdZUK_rZcdTxazFH&s=10" alt="CL-7 therapy bed">
            </li>
            <li>
                <strong>CL-2500 Thermal Single Mat:</strong> Migraine, Sinus, Headache, Insomnia, Control Cholesterol, Blood Pressure, Weight Loss, etc.
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSsg_BqA5uc3nLSf9OoKqy_oxHmYyfU3RKMmg&usqp=CAU" alt="CL-2500 Thermal Single Mat">
            </li>
            <li>
                <strong>CL-1000 Thermal Single Mat:</strong> Migraine, Sinus, Headache, Insomnia, Control Cholesterol, Blood Pressure, Weight Loss, etc.
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQHFbs5s2UT22w9SdIb_Go0av6CgzkTw9b4rA&usqp=CAU" alt="CL-1000 Thermal Single Mat">
            </li>
            <li>
                <strong>Waist Heating Belt:</strong> It is not just limited to abdomen but also on waist, stomach, shoulder, arms, knees, legs
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIE1okHjD19g2HK8TbuaKa2V2JIbB-dGuElA&usqp=CAU" alt="Waist Heating Belt">
            </li>
        </ul>
    </section>
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            <label for="message">Message:</label>
            <textarea id="message" name="message"></textarea>
            <input type="submit" value="Submit">
        </form>
        <p>Address: T-48 saket buisness hub,radhanpur road meshana-2</p>
        <p>Phone: 9974936685,63521 82670</p>
        <p>Email: yakshpatel27627@gmail.com</p>
    </section>
    <footer>
        <p>&copy; 2024 CHIRO LIFE THERAPY CENTRE</p>
        <p><a href="#home">Home</a> | <a href="#about">About Us</a> | <a href="#services">Services</a> | <a href="#products">Products</a> | <a href="#contact">Contact Us</a></p>
    </footer>
</body>
</html>
