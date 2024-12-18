<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Loja Online Moderna</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <div class="logo">Minha Loja</div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#produtos">Produtos</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="home-section">
    <h1>Bem-vindo à nossa loja online!</h1>
    <p>Encontre os melhores produtos ao seu alcance.</p>
  </section>

  <section id="produtos" class="produtos-section">
    <h2>Nossos Produtos</h2>
    <div class="produtos-container">
      <!-- Produto 1 -->
      <div class="produto">
        <img src="https://via.placeholder.com/200" alt="Produto 1">
        <h3>Produto 1</h3>
        <p>Descrição breve do produto 1.</p>
        <button onclick="adicionarAoCarrinho('Produto 1')">Adicionar ao Carrinho</button>
      </div>

      <!-- Produto 2 -->
      <div class="produto">
        <img src="https://via.placeholder.com/200" alt="Produto 2">
        <h3>Produto 2</h3>
        <p>Descrição breve do produto 2.</p>
        <button onclick="adicionarAoCarrinho('Produto 2')">Adicionar ao Carrinho</button>
      </div>
      
      <!-- Produto 3 -->
      <div class="produto">
        <img src="https://via.placeholder.com/200" alt="Produto 3">
        <h3>Produto 3</h3>
        <p>Descrição breve do produto 3.</p>
        <button onclick="adicionarAoCarrinho('Produto 3')">Adicionar ao Carrinho</button>
      </div>
    </div>
  </section>

  <section id="contato" class="contato-section">
    <h2>Contato</h2>
    <p>Entre em contato conosco por e-mail ou telefone.</p>
    <form>
      <input type="email" placeholder="Seu e-mail" required>
      <textarea placeholder="Sua mensagem" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2024 Minha Loja - Todos os direitos reservados.</p>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>

let carrinho = [];

function adicionarAoCarrinho(produto) {
  carrinho.push(produto);
  alert(produto + ' foi adicionado ao seu carrinho!');
  console.log(carrinho);
}

<!---
felipe873/felipe873 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
