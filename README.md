<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ravi Vaishno Dhaba | Garhshankar</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', Arial, sans-serif;
    background: #f5f5f5;
    color: #333;
}

/* HEADER */
header {
    background: linear-gradient(135deg, #8b0000, #b22222);
    color: white;
    padding: 25px 15px;
    text-align: center;
}
header h1 {
    margin: 0;
    font-size: 32px;
}
header p {
    margin-top: 8px;
    font-size: 16px;
}

/* CONTAINER */
section {
    max-width: 1000px;
    margin: auto;
    padding: 20px;
    background: white;
}

/* TITLES */
h2 {
    color: #8b0000;
    border-bottom: 2px solid #8b0000;
    padding-bottom: 5px;
    margin-top: 30px;
}

/* MENU */
.menu-category h3 {
    color: #444;
    margin-top: 20px;
}
.menu-item {
    display: flex;
    justify-content: space-between;
    padding: 8px 0;
    border-bottom: 1px dashed #ccc;
}

/* BUTTONS */
.buttons {
    display: flex;
    gap: 10px;
    margin-top: 15px;
    flex-wrap: wrap;
}
.btn {
    padding: 10px 15px;
    background: #8b0000;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-size: 14px;
}
.btn:hover {
    background: #a40000;
}

/* IMAGE */
.menu-image {
    text-align: center;
    margin-top: 25px;
}
.menu-image img {
    max-width: 100%;
    border-radius: 10px;
    border: 2px solid #ddd;
}

/* FOOTER */
footer {
    background: #222;
    color: #ccc;
    text-align: center;
    padding: 15px;
    margin-top: 30px;
    font-size: 14px;
}

/* MOBILE */
@media (max-width: 600px) {
    header h1 {
        font-size: 26px;
    }
    .menu-item {
        font-size: 14px;
    }
}
</style>
</head>

<body>

<header>
    <h1>Ravi Vaishno Dhaba</h1>
    <p>Pure Veg • Fresh Food • Garhshankar</p>
</header>

<section>

    <h2>📍 Location</h2>
    <p>Garhshankar, Punjab</p>

    <div class="buttons">
        <a class="btn" href="https://maps.google.com" target="_blank">📍 Open in Maps</a>
        <a class="btn" href="tel:+919999999999">📞 Call Now</a>
        <a class="btn" href="https://wa.me/919999999999">💬 WhatsApp</a>
    </div>

    <h2>🍽️ Our Menu</h2>

    <div class="menu-category">
        <h3>Paneer</h3>
        <div class="menu-item"><span>Kadhai Paneer</span><span>₹170 / ₹340</span></div>
        <div class="menu-item"><span>Shahi Paneer</span><span>₹150 / ₹300</span></div>
        <div class="menu-item"><span>Paneer Bhurji</span><span>₹150 / ₹300</span></div>
        <div class="menu-item"><span>Matar Paneer</span><span>₹150 / ₹300</span></div>
        <div class="menu-item"><span>Channa Masala (Paneer)</span><span>₹150 / ₹300</span></div>
    </div>

    <div class="menu-category">
        <h3>Rice</h3>
        <div class="menu-item"><span>Jeera Rice</span><span>₹60</span></div>
        <div class="menu-item"><span>Plain Rice</span><span>₹50</span></div>
    </div>

    <div class="menu-category">
        <h3>Dahi / Raita</h3>
        <div class="menu-item"><span>Dahi (Small / Large)</span><span>₹40 / ₹80</span></div>
        <div class="menu-item"><span>Raita (Small / Large)</span><span>₹60 / ₹120</span></div>
        <div class="menu-item"><span>Dahi Katori</span><span>₹20</span></div>
    </div>

    <div class="menu-category">
        <h3>Egg</h3>
        <div class="menu-item"><span>2 Egg Omelette</span><span>₹50</span></div>
        <div class="menu-item"><span>2 Egg Bhurji</span><span>₹50</span></div>
    </div>

    <div class="menu-category">
        <h3>Beverages</h3>
        <div class="menu-item"><span>Tea</span><span>₹15</span></div>
        <div class="menu-item"><span>Coffee</span><span>₹25</span></div>
        <div class="menu-item"><span>Lassi (Sweet / Salted)</span><span>₹20</span></div>
        <div class="menu-item"><span>Cold Drink</span><span>MRP</span></div>
        <div class="menu-item"><span>Mineral Water</span><span>MRP</span></div>
    </div>

    <div class="menu-image">
        <h2>📸 Menu Card</h2>
        <img src="menu.jpg" alt="Ravi Vaishno Dhaba Menu">
        <p><small>Add your real menu photo here</small></p>
    </div>

</section>

<footer>
    <p>© 2026 Ravi Vaishno Dhaba | Garhshankar</p>
</footer>

</body>
</html>
