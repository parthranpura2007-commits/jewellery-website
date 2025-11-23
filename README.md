 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Jewellery Store Demo</title>
    <style>
        * {margin:0; padding:0; box-sizing:border-box; font-family:Arial, sans-serif;}
        body {background:#fff; color:#333;}
        header {background:linear-gradient(45deg,#d4af37,#f5e6a1); padding:20px; text-align:center; color:#000; font-size:28px; font-weight:bold;}
        nav {display:flex; justify-content:center; gap:20px; padding:15px; background:#fff; border-bottom:1px solid #ddd;}
        nav a {text-decoration:none; color:#444; font-weight:bold;}
        .hero {padding:60px 20px; text-align:center; background:#faf7f0;}
        .hero h1 {font-size:40px; color:#b38b00;}
        .hero p {font-size:18px; margin-top:10px;}
        .products {padding:40px; display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:20px;}
        .card {border:1px solid #ddd; border-radius:10px; padding:15px; text-align:center; background:#fff;}
        .card img {width:100%; height:240px; object-fit:cover; border-radius:10px;}
        .card h3 {margin-top:10px; font-size:20px;}
        .card p {color:#666; margin:8px 0;}
        .btn {background:#d4af37; padding:10px 18px; border:none; color:#fff; border-radius:5px; cursor:pointer;}
        footer {text-align:center; padding:20px; background:#f4f4f4; margin-top:40px;}
    </style>
</head>
<body>

<header>Royal Jewellery</header>

<nav>
    <a href="#home">Home</a>
    <a href="#collections">Collections</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero" id="home">
    <h1>Premium Gold & Diamond Jewellery</h1>
    <p>Elegant • Authentic • Affordable</p>
</section>

<section class="products" id="collections">
    <div class="card">
        <img src="https://i.imgur.com/9QO5YkN.jpg" alt="Necklace" />
        <h3>Gold Necklace</h3>
        <p>₹45,000</p>
        <button class="btn">Order Now</button>
    </div>

    <div class="card">
        <img src="https://i.imgur.com/Ic8ZQ0h.jpg" alt="Ring" />
        <h3>Diamond Ring</h3>
        <p>₹27,999</p>
        <button class="btn">Order Now</button>
    </div>

    <div class="card">
        <img src="https://i.imgur.com/XEJqO3z.jpg" alt="Earrings" />
        <h3>Elegant Earrings</h3>
        <p>₹12,599</p>
        <button class="btn">Order Now</button>
    </div>
</section>

<footer id="contact">
    <p>Contact Us: +91 98765 43210 | royaljewellery@mail.com</p>
    <p>© 2025 Royal Jewellery. All Rights Reserved.</p>
</footer>

<script>
    document.querySelectorAll('.btn').forEach(btn => {
        btn.addEventListener('click', () => {
            alert('Thank you for your interest! WhatsApp order option will be added.');
        });
    });
</script>

</body>
</html>
