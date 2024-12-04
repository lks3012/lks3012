<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Outlet de Tênis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        section {
            text-align: center;
            padding: 20px;
        }
        .products {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 10px;
            width: 200px;
            text-align: center;
        }
        .product img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Outlet de Tênis</h1>
    </header>
    <nav>
        <a href="#produtos">Produtos</a>
        <a href="#sobre">Sobre Nós</a>
        <a href="#contato">Contato</a>
    </nav>
    <section id="produtos">
        <h2>Nossos Produtos</h2>
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Tênis 1">
                <h3>Tênis Esportivo</h3>
                <p>R$199,99</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Tênis 2">
                <h3>Tênis Casual</h3>
                <p>R$149,99</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Tênis 3">
                <h3>Tênis de Corrida</h3>
                <p>R$249,99</p>
            </div>
        </div>
    </section>
    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Bem-vindo à nossa outlet! Oferecemos tênis de alta qualidade com preços acessíveis.</p>
    </section>
    <section id="contato">
        <h2>Contato</h2>
        <p>Email: contato@outletdetenis.com</p>
        <p>Telefone: (11) 99999-9999</p>
    </section>
    <footer>
        <p>&copy; 2024 Outlet de Tênis. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
