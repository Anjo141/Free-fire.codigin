<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Site de Resgate</title>
  <!-- Link do FontAwesome para ícones -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      font-family: Arial, sans-serif;
      color: white;
      text-shadow: 1px 1px 2px black;
      position: relative;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    /* Imagem de fundo */
    body::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: url('https://freefireclub.com/wp-content/uploads/2021/11/B90850AC-B7A2-4F8F-A682-51EDA6B6E43B.jpeg') no-repeat center center/cover;
      z-index: -2;
    }

    /* Camada escura */
    body::after {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.5);
      z-index: -1;
    }

    .topo {
      margin-top: 40px;
      text-align: center;
    }

    .topo h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    .topo p {
      font-size: 1.5em;
      margin: 0;
    }

    .conteudo {
      flex-grow: 1;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      margin-top: 20px;
    }

    .botoes {
      display: flex;
      gap: 20px;
      margin-top: 40px;
    }

    .botoes button {
      background-color: #ffffff;
      border: none;
      padding: 15px 20px;
      border-radius: 10px;
      font-size: 1.5em;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    .botoes button:hover {
      background-color: #dddddd;
    }

    .botoes i {
      color: #000;
    }

    .aviso {
      background: rgba(255, 255, 255, 0.85); /* Branco mais forte e visível */
      color: #000; /* Texto preto */
      padding: 30px;
      border-radius: 20px;
      width: 90%;
      max-width: 700px;
      font-size: 1.2em; /* Fonte maior */
      text-align: left;
      margin-top: 80px; /* Aviso mais abaixo */
      margin-bottom: 40px;
    }

    .aviso p {
      margin: 15px 0;
    }
  </style>
</head>
<body>
  <div class="topo">
    <h1>Site de resgate de recompensas</h1>
    <p>Resgate seu código</p>
  </div>
  <div class="conteudo">
    <div class="botoes">
      <!-- Link para a página do Facebook -->
      <a href="facebook.html">
        <button><i class="fab fa-facebook-f"></i></button>
      </a>
      <button><i class="fab fa-vk"></i></button>
      <button><i class="fab fa-google"></i></button>
    </div>
    <!-- Aviso colocado abaixo -->
    <div class="aviso">
      <p><strong>Aviso importante:</strong></p>
      <p>1. O código de resgate tem 12/16 caracteres, em combinação com letras e números.</p>
      <p>2. Os itens de recompensa serão exibidos em [Cofre] no lobby do jogo.</p>
      <p>3. Por favor, anote o prazo de validade do resgate. Qualquer código expirado não pode ser resgatado.</p>
      <p>4. Entre em contato com o serviço ao cliente se você encontrar algum problema.</p>
      <p>5. Lembrete: você não poderá resgatar seus prêmios com contas de convidados. Você pode vincular sua conta ao Facebook ou VK para receber recompensas.</p>
    </div>
  </div>
</body>
</html>
