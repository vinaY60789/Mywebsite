<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Royal Spice Restaurant</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0f0f0f;
    color: white;
}

header {
    background: url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092') no-repeat center/cover;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

header h1 {
    font-size: 50px;
    color: #ffd700;
}

header p {
    font-size: 20px;
}

.btn {
    margin-top: 20px;
    padding: 12px 25px;
    background: #ffd700;
    color: black;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

section {
    padding: 50px;
    text-align: center;
}

.menu {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.card {
    background: #1c1c1c;
    padding: 20px;
    border-radius: 10px;
}

footer {
    background: black;
    padding: 20px;
    text-align: center;
}

.whatsapp {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #25D366;
    padding: 15px;
    border-radius: 50%;
    text-decoration: none;
    color: white;
    font-size: 20px;
}
</style>
</head>

<body>

<header>
    <h1>Royal Spice Restaurant 🍴</h1>
    <p>Taste the Authentic Flavors of India</p>
    <a href="tel:7895252570" class="btn">Call Now</a>
</header>

<section>
    <h2>About Us</h2>
    <p>Welcome to Royal Spice Restaurant – where taste meets tradition. 
    Enjoy delicious Indian food with family and friends.</p>
</section>

<section>
    <h2>Our Menu</h2>
    <div class="menu">
        <div class="card">🍛 Paneer Butter Masala – ₹220</div>
        <div class="card">🍗 Butter Chicken – ₹280</div>
        <div class="card">🍚 Veg Biryani – ₹180</div>
        <div class="card">🫓 Butter Naan – ₹40</div>
        <div class="card">🥤 Cold Drinks – ₹50</div>
    </div>
</section>

<section>
    <h2>Contact Us</h2>
    <p>📍 Dehradun, Uttarakhand</p>
    <p>📞 7895252570</p>
    <p>🕒 10 AM – 11 PM</p>
</section>

<footer>
    <p>© 2026 Royal Spice Restaurant</p>
</footer>

<a class="whatsapp" href="https://wa.me/917895252570">💬</a>

</body>
</html>
