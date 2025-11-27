
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MyBay - Online Marketplace</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <div class="logo">MyBay</div>
    <input id="searchInput" type="text" placeholder="Search products...">
</header>

<nav class="categories">
    <button onclick="filterCategory('all')">All</button>
    <button onclick="filterCategory('electronics')">Electronics</button>
    <button onclick="filterCategory('fashion')">Fashion</button>
    <button onclick="filterCategory('home')">Home</button>
</nav>

<section class="product-grid" id="productGrid">
    <!-- Example Product -->
    <div class="product-card" data-category="electronics">
        <img src="https://via.placeholder.com/200">
        <h3>Wireless Headphones</h3>
        <p>$59.99</p>
        <a class="btn" href="product.html">View</a>
    </div>

    <div class="product-card" data-category="fashion">
        <img src="https://via.placeholder.com/200">
        <h3>Leather Wallet</h3>
        <p>$29.99</p>
        <a class="btn" href="product.html">View</a>
    </div>

    <div class="product-card" data-category="home">
        <img src="https://via.placeholder.com/200">
        <h3>Table Lamp</h3>
        <p>$39.99</p>
        <a class="btn" href="product.html">View</a>
    </div>
</section>

<script src="script.js"></script>
</body>
</html>
