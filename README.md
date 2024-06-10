<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fragment Online Store</title>
<link rel="stylesheet" href="styles.css">
</head>
<body>
<header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Products</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
</header>

<main>
    <section class="product-list">
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p>$100</p>
            <button>Add to Cart</button>
        </div>
        <!-- More products here -->
    </section>

    <aside class="cart">
        <h2>Shopping Cart</h2>
        <ul>
            <!-- Cart items will be dynamically added here -->
        </ul>
        <button>Checkout</button>
    </aside>
</main>

<footer>
    <p>&copy; 2024 Fragment Online Store. All rights reserved.</p>
</footer>

<script src="script.js"></script>
</body>
</html>
