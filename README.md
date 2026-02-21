<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Thrift Store</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f4f4f4;
}

header {
    background: #222;
    color: white;
    padding: 15px;
    text-align: center;
}

nav {
    background: #444;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 15px;
    font-weight: bold;
}

nav a:hover {
    color: yellow;
}

.container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
}

.card {
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    padding: 15px;
    text-align: center;
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
}

.price {
    color: green;
    font-size: 18px;
    font-weight: bold;
}

button {
    background: #222;
    color: white;
    border: none;
    padding: 10px 15px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background: green;
}

footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
}
</style>
</head>

<body>

<header>
    <h1>🛍️ My Thrift Store</h1>
    <p>Best Second-Hand Fashion Deals</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Shop</a>
    <a href="#">Contact</a>
</nav>

<div class="container">

    <div class="card">
        <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab" alt="Jacket">
        <h3>Vintage Jacket</h3>
        <p class="price">₹799</p>
        <button>Add to Cart</button>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f" alt="Shoes">
        <h3>Used Sneakers</h3>
        <p class="price">₹599</p>
        <button>Add to Cart</button>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1541099649105-f69ad21f3246" alt="Jeans">
        <h3>Denim Jeans</h3>
        <p class="price">₹499</p>
        <button>Add to Cart</button>
    </div>

</div>

<footer>
    © 2026 My Thrift Store | All Rights Reserved
</footer>

</body>
</html>
