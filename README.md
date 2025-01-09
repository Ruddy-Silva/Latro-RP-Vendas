# Latro-RP-Vendas
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latro-RP - Sua Loja de Vendas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 0.5rem;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            padding: 0.5rem;
        }
        nav a:hover {
            background-color: #555;
            border-radius: 5px;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 1rem;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1rem;
            text-align: center;
            margin-bottom: 2rem;
            background-color: #fff;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .product h3 {
            margin: 1rem 0;
        }
        .product p {
            color: #666;
        }
        .product button {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 0.5rem 1rem;
            cursor: pointer;
            border-radius: 5px;
        }
        .product button:hover {
            background-color: #555;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo à Latro-RP</h1>
        <p>Os melhores produtos para você!</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#produtos">Produtos</a>
        <a href="#contato">Contato</a>
    </nav>
    <div class="container" id="produtos">
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Produto 1">
            <h3>Produto 1</h3>
            <p>Descrição do produto 1.</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Produto 2">
            <h3>Produto 2</h3>
            <p>Descrição do produto 2.</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Produto 3">
            <h3>Produto 3</h3>
            <p>Descrição do produto 3.</p>
            <button>Comprar</button>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 Latro-RP. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
