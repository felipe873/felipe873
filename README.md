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

  <div class="produto">
        <img src="https://via.placeholder.com/200" alt="Produto 1">
        <h3>Produto 1</h3>
        <p>Descrição breve do produto 1. Este é um produto de alta qualidade e com ótimo custo-benefício.</p>
        <button onclick="adicionarAoCarrinho('Produto 1')">Adicionar ao Carrinho</button>
      </div>

      <!-- Produto 2 -->
      <div class="produto">
        <img src="https://via.placeholder.com/200" alt="Produto 2">
        <h3>Produto 2</h3>
        <p>Descrição breve do produto 2. Produto inovador para quem busca performance e qualidade.</p>
        <button onclick="adicionarAoCarrinho('Produto 2')">Adicionar ao Carrinho</button>
      </div>
      
      <!-- Produto 3 -->
      <div class="produto">
        <img src="https://via.placeholder.com/200" alt="Produto 3">
        <h3>Produto 3</h3>
        <p>Descrição breve do produto 3. Ideal para o dia a dia, com excelente durabilidade e design moderno.</p>
        <button onclick="adicionarAoCarrinho('Produto 3')">Adicionar ao Carrinho</button>
      </div>

      <!-- Produto 4 -->
      <div class="produto">
        <img src="https://via.placeholder.com/200" alt="Produto 4">
        <h3>Produto 4</h3>
        <p>Descrição breve do produto 4. Perfeito para quem deseja inovação e sofisticação em seus produtos.</p>
        <button onclick="adicionarAoCarrinho('Produto 4')">Adicionar ao Carrinho</button>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2024 Minha Loja - Todos os direitos reservados.</p>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>
2. style.css (CSS para estilizar a página de produtos):
Aqui, vamos fazer alguns ajustes para garantir que a página de produtos tenha um layout agradável.

css
Copiar código
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
}

header {
  background-color: #333;
  color: #fff;
  padding: 10px 0;
  text-align: center;
}

header .logo {
  font-size: 2em;
}

header nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
}

header nav ul li {
  margin: 0 20px;
}

header nav ul li a {
  color: #fff;
  text-decoration: none;
  font-size: 1.1em;
}

.produtos-section {
  padding: 50px 0;
  background-color: #f9f9f9;
  text-align: center;
}

.produtos-section h2 {
  margin-bottom: 20px;
}

.produtos-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
}

.produto {
  background-color: #fff;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  width: 220px;
  text-align: center;
  transition: transform 0.2s;
}

.produto:hover {
  transform: scale(1.05);
}

.produto img {
  width: 100%;
  height: auto;
  border-radius: 5px;
}

button {
  background-color: #333;
  color: #fff;
  border: none;
  padding: 10px;
  cursor: pointer;
  border-radius: 5px;
  margin-top: 10px;
}

button:hover {
  background-color: #555;
}

footer {
  text-align: center;
  background-color: #333;
  color: #fff;
  padding: 10px 0;
}
