<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda Online</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        .container {
            padding: 2rem;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1rem;
            margin-bottom: 1rem;
            background-color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .product img {
            max-width: 100%;
            border-radius: 8px;
        }
        .product h3 {
            margin: 0.5rem 0;
        }
        .product button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            cursor: pointer;
            border-radius: 4px;
        }
        .social-links {
            text-align: center;
            margin-top: 2rem;
        }
        .social-links a {
            margin: 0 10px;
            color: #4CAF50;
            font-size: 1.5rem;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tienda Online</h1>
        <p>Encuentra los mejores productos y compártelos en tus redes sociales</p>
    </header>
    <div class="container">
        <div class="product">
            <img src="producto1.jpg" alt="Producto 1">
            <h3>Producto 1</h3>
            <p>$10.00</p>
            <button>Comprar Ahora</button>
        </div>
        <div class="product">
            <img src="producto2.jpg" alt="Producto 2">
            <h3>Producto 2</h3>
            <p>$15.00</p>
            <button>Comprar Ahora</button>
        </div>
    </div>
    <div class="social-links">
        <p>Síguenos en nuestras redes sociales:</p>
        <a href="https://www.facebook.com" target="_blank">&#x1F465; Facebook</a>
        <a href="https://www.instagram.com" target="_blank">&#x1F467; Instagram</a>
        <a href="https://www.twitter.com" target="_blank">&#x1F426; Twitter</a>
        <a href="https://www.tiktok.com" target="_blank">&#x1F44D; TikTok</a>
    </div>
</body>
</html>
