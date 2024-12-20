<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GameFuel - Your Gaming Recharge Hub</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #121212;
            color: #fff;
        }

        header {
            background: #1f1f1f;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            font-size: 1.8rem;
            color: #00bcd4;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        nav ul li {
            margin: 0 1rem;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
        }

        .hero {
            text-align: center;
            padding: 3rem 2rem;
            background: #00bcd4;
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 2rem;
        }

        .product-card {
            background: #1f1f1f;
            border: 1px solid #333;
            border-radius: 8px;
            padding: 1.5rem;
            text-align: center;
        }

        .product-card img {
            max-width: 100%;
            border-radius: 8px;
            margin-bottom: 1rem;
        }

        .product-card h3 {
            font-size: 1.5rem;
            margin-bottom: 0.5rem;
        }

        .product-card p {
            font-size: 1rem;
            margin-bottom: 1rem;
        }

        .product-card button {
            background: #00bcd4;
            color: #fff;
            border: none;
            padding: 0.8rem 1.5rem;
            border-radius: 4px;
            cursor: pointer;
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background: #1f1f1f;
            margin-top: 2rem;
        }

        footer p {
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>GameFuel</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h2>Fuel Your Gaming Journey</h2>
        <p>Recharge your favorite games instantly with our trusted service.</p>
    </section>

    <section class="products" id="products">
        <div class="product-card">
            <img src="https://via.placeholder.com/300" alt="Game Card">
            <h3>PlayStation Gift Card</h3>
            <p>Top up your PS wallet and enjoy exclusive games and add-ons.</p>
            <button>Buy Now</button>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/300" alt="Game Card">
            <h3>Xbox Live Gold</h3>
            <p>Unlock multiplayer, free games, and more with Xbox Live Gold.</p>
            <button>Buy Now</button>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/300" alt="Game Card">
            <h3>Steam Wallet Code</h3>
            <p>Load your Steam wallet and explore an endless library of games.</p>
            <button>Buy Now</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 GameFuel. All rights reserved.</p>
    </footer>
</body>
</html>
