<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AURORA - Roupas Minimalistas</title>
  <style>
    * {
      margin: 0; padding: 0; box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background-color: #fffaf5;
      color: #111;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    header {
      background-color: #fff;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #eee;
    }

    .logo {
      font-size: 1.8rem;
      font-weight: 700;
      color: #000;
      letter-spacing: 2px;
    }

    nav a {
      color: #000;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
    }

    nav a:hover {
      color: #be9b7b;
    }

    .hero {
      height: 60vh;
      background: url('https://images.unsplash.com/photo-1521334884684-d80222895322?auto=format&fit=crop&w=1350&q=80') no-repeat center/cover;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
      text-align: center;
      padding: 0 20px;
    }

    .hero h1 {
      font-size: 3rem;
      text-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    }

    .hero p {
      margin-top: 10px;
      font-size: 1.2rem;
    }

    .btn-whatsapp {
      margin-top: 20px;
      background-color: #25D366;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 25px;
      text-decoration: none;
      font-weight: 600;
      display: inline-flex;
      align-items: center;
      gap: 10px;
    }

    main {
      flex-grow: 1;
      padding: 40px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }

    h2 {
      text-align: center;
      font-size: 2rem;
      color: #7a5c38;
      margin-bottom: 30px;
    }

    .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }

    .product-card {
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 12px;
      overflow: hidden;
      transition: box-shadow 0.3s;
    }

    .product-card:hover {
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    }

    .product-card img {
      width: 100%;
      height: 320px;
      object-fit: cover;
    }

    .product-info {
      padding: 15px;
      text-align: center;
    }

    .product-info h3 {
      margin-bottom: 10px;
      font-weight: 500;
    }

    .product-info p {
      color: #444;
      font-weight: 300;
      margin-bottom: 10px;
    }

    .product-info a {
      background: #000;
      color: #fff;
      padding: 10px 20px;
      border-radius: 20px;
      text-decoration: none;
      font-weight: 500;
      display: inline-block;
    }

    footer {
      background: #fff;
      text-align: center;
      padding: 20px;
      color: #777;
      font-size: 0.9rem;
      border-top: 1px solid #eee;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">AURORA</div>
    <nav>
      <a href="#produtos">Produtos</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section class="hero">
    <div>
      <h1>Minimalismo com atitude</h1>
      <p>Camisas estilosas e exclusivas</p>
      <a href="https://wa.me/5535998840725" target="_blank" class="btn-whatsapp">WhatsApp</a>
    </div>
  </section>

  <main>
    <section id="produtos">
      <h2>Produtos</h2>
      <div class="products-grid">

        <div class="product-card">
          <img src="/mnt/data/60b9ca90-7899-4a58-98d3-606d61cc1071.jpg" alt="Camisa Miami Heat Preta">
          <div class="product-info">
            <h3>Miami Heat Preta</h3>
            <p>R$ 129,90</p>
            <a href="https://wa.me/5535998840725?text=Olá!%20Tenho%20interesse%20na%20Miami%20Heat%20Preta">Comprar</a>
          </div>
        </div>

        <div class="product-card">
          <img src="/mnt/data/92f6b945-154c-4782-ae26-69d299ac0454.jpg" alt="Camisa Miami Heat Branca">
          <div class="product-info">
            <h3>Miami Heat Branca</h3>
            <p>R$ 129,90</p>
            <a href="https://wa.me/5535998840725?text=Olá!%20Tenho%20interesse%20na%20Miami%20Heat%20Branca">Comprar</a>
          </div>
        </div>

        <div class="product-card">
          <img src="/mnt/data/495e9016-a61d-42ab-8a08-8aabbbbf8520.jpg" alt="Camisa Stussy Branca">
          <div class="product-info">
            <h3>Stussy Branca</h3>
            <p>R$ 119,90</p>
            <a href="https://wa.me/5535998840725?text=Olá!%20Tenho%20interesse%20na%20Stussy%20Branca">Comprar</a>
          </div>
        </div>

        <div class="product-card">
          <img src="/mnt/data/674a1a46-21cc-41df-914f-40b6fdac7727.jpg" alt="Camisa Stussy Azul Bebê">
          <div class="product-info">
            <h3>Stussy Azul Bebê</h3>
            <p>R$ 119,90</p>
            <a href="https://wa.me/5535998840725?text=Olá!%20Tenho%20interesse%20na%20Stussy%20Azul%20Bebê">Comprar</a>
          </div>
        </div>

        <div class="product-card">
          <img src="/mnt/data/a9479974-6170-408e-870b-c21cb1bd0249.jpg" alt="Miami Heat Azul Claro">
          <div class="product-info">
            <h3>Miami Heat Azul Claro</h3>
            <p>R$ 129,90</p>
            <a href="https://wa.me/5535998840725?text=Olá!%20Tenho%20interesse%20na%20Miami%20Heat%20Azul%20Claro">Comprar</a>
          </div>
        </div>

        <div class="product-card">
          <img src="/mnt/data/ae2463cf-474d-48ea-bef2-01d62fe8c465.jpg" alt="NY Steak House">
          <div class="product-info">
            <h3>NY Steak House</h3>
            <p>R$ 109,90</p>
            <a href="https://wa.me/5535998840725?text=Olá!%20Tenho%20interesse%20na%20camisa%20NY%20Steak%20House">Comprar</a>
          </div>
        </div>

      </div>
    </section>
  </main>

  <footer>
    © 2025 AURORA. Todos os direitos reservados.
  </footer>
</body>
</html>
