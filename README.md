<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Boutiques Variedades</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
    }
    header {
      background: #9c27b0;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .produtos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .produto {
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      margin: 10px;
      padding: 15px;
      width: 220px;
      text-align: center;
      position: relative;
    }
    .produto img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 8px;
    }
    .botao {
      background: #4caf50;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      display: inline-block;
      margin-top: 10px;
    }
    .preco-antigo {
      color: #888;
      text-decoration: line-through;
      font-size: 0.9em;
    }
    .desconto {
      background: #e91e63;
      color: white;
      font-weight: bold;
      padding: 3px 7px;
      border-radius: 4px;
      position: absolute;
      top: 10px;
      right: 10px;
      font-size: 0.8em;
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #eee;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Boutiques Variedades</h1>
    <p>Cosméticos, roupas, perfumes e muito mais!</p>
  </header>

  <section class="produtos">
    <div class="produto">
      <img src="vestido-floral-infantil.jpg" alt="Vestido Floral Infantil - Tam 2" />
      <div class="desconto">Promoção</div>
      <h3>Vestido Floral Infantil - Tam 2</h3>
      <p><span class="preco-antigo">R$ 80,00</span> R$ 65,00</p>
      <a class="botao" href="https://wa.me/559499162819?text=Olá!%20Tenho%20interesse%20no%20Vestido%20Floral%20Infantil%20-%20Tam%202" target="_blank">Comprar</a>
    </div>

    <div class="produto">
      <img src="macacao-azul-bebe.jpg" alt="Macacão Azul Bebê - Tam P" />
      <h3>Macacão Azul Bebê - Tam P</h3>
      <p>R$ 48,00</p>
      <a class="botao" href="https://wa.me/559499162819?text=Olá!%20Tenho%20interesse%20no%20Macacão%20Azul%20Bebê%20-%20Tam%20P" target="_blank">Comprar</a>
    </div>

    <div class="produto">
      <img src="conjunto-listrado-feminino.jpg" alt="Conjunto Listrado Feminino" />
      <div class="desconto">Oferta</div>
      <h3>Conjunto Listrado Feminino</h3>
      <p><span class="preco-antigo">R$ 90,00</span> R$ 75,00</p>
      <a class="botao" href="https://wa.me/559499162819?text=Olá!%20Tenho%20interesse%20no%20Conjunto%20Listrado%20Feminino" target="_blank">Comprar</a>
    </div>

    <div class="produto">
      <img src="blusa-algodao-branca.jpg" alt="Blusa de Algodão Branca" />
      <h3>Blusa de Algodão Branca</h3>
      <p>R$ 38,00</p>
      <a class="botao" href="https://wa.me/559499162819?text=Olá!%20Tenho%20interesse%20na%20Blusa%20de%20Algodão%20Branca" target="_blank">Comprar</a>
    </div>

    <div class="produto">
      <img src="camiseta-basica-cinza.jpg" alt="Camiseta Básica Cinza" />
      <h3>Camiseta Básica Cinza</h3>
      <p>R$ 35,00</p>
      <a class="botao" href="https://wa.me/559499162819?text=Olá!%20Tenho%20interesse%20na%20Camiseta%20Básica%20Cinza" target="_blank">Comprar</a>
    </div>

    <div class="produto">
      <img src="calca-jeans-infantil.jpg" alt="Calça Jeans Infantil - Tam 3" />
      <h3>Calça Jeans Infantil - Tam 3</h3>
      <p>R$ 52,00</p>
      <a class="botao" href="https://wa.me/559499162819?text=Olá!%20Tenho%20interesse%20na%20Calça%20Jeans%20Infantil%20-%20Tam%203" target="_blank">Comprar</a>
    </div>

    <div class="produto">
      <img src="vestido-rosa-babados.jpg" alt="Vestido Rosa com Babados" />
      <div class="desconto">Promoção</div>
      <h3>Vestido Rosa com Babados</h3>
      <p><span class="preco-antigo">R$ 85,00</span> R$ 70,00</p>
      <a class="botao" href="https://wa.me/559499162819?text=Olá!%20Tenho%20interesse%20no%20Vestido%20Rosa%20com%20Babados" target="_blank">Comprar</a>
    </div>

    <div class="produto">
      <img src="body-branco-bebe.jpg" alt="Body Branco Bebê - Tam M" />
      <h3>Body Branco Bebê - Tam M</h3>
      <p>R$ 40,00</p>
      <a class="botao" href="https://wa.me/559499162819?text=Olá!%20Tenho%20interesse%20no%20Body%20Branco%20Bebê%20-%20Tam%20M" target="_blank">Comprar</a>
    </div>
  </section>

  <footer>
    <p>Entre em contato: <a href="https://wa.me/559499162819" target="_blank">WhatsApp</a></p>
  </footer>
</body>
</html>
