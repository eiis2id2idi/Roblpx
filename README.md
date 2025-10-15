<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Resgatar Códigos Roblox</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background-color: #f2f2f2;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      min-height: 100vh;
    }

    /* Barra superior */
    header {
      width: 100%;
      background-color: #ffffff;
      display: flex;
      justify-content: flex-end;
      align-items: center;
      padding: 15px 25px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    header button {
      background-color: #00b06f;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 8px;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }

    header button:hover {
      background-color: #00935d;
    }

    .container {
      background-color: white;
      width: 90%;
      max-width: 850px;
      margin-top: 40px;
      border-radius: 10px;
      box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
      padding: 30px;
      display: flex;
      flex-direction: row;
      gap: 30px;
    }

    .left, .right {
      flex: 1;
    }

    h1 {
      font-size: 28px;
      color: #333;
      margin-bottom: 15px;
    }

    p {
      font-size: 15px;
      color: #444;
      margin-bottom: 15px;
    }

    input[type="text"] {
      width: 100%;
      padding: 12px;
      font-size: 16px;
      border-radius: 6px;
      border: 1px solid #ccc;
      margin-bottom: 15px;
    }

    label {
      font-size: 13px;
      color: #555;
      display: flex;
      align-items: flex-start;
      gap: 8px;
    }

    .resgatar-btn {
      background-color: #00b06f;
      color: white;
      font-size: 16px;
      font-weight: bold;
      padding: 12px 20px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      width: 100%;
      transition: 0.3s;
    }

    .resgatar-btn:hover {
      background-color: #00935d;
    }

    .right img {
      width: 100%;
      border-radius: 8px;
      margin-top: 10px;
    }

    .links {
      margin-top: 10px;
    }

    .links a {
      display: block;
      color: #0074cc;
      text-decoration: none;
      margin-bottom: 6px;
    }

    .links a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <button>Entra</button>
  </header>

  <div class="container">
    <div class="left">
      <h1>Resgatar códigos Roblox</h1>
      <p>Digite o código de seu cartão presente, item virtual ou código promocional abaixo.</p>

      <input type="text" placeholder="Código" />

      <label>
        <input type="checkbox" />
        Ao marcar a caixa, você concorda que tem pelo menos 18 anos de idade, ou que é um dos pais ou responsável legal do proprietário da conta e concorda com nossos Termos de Uso, incluindo a cláusula de arbitragem, com os Termos e Condições do cartão presente e com nossa Política de Privacidade.
      </label>

      <button class="resgatar-btn" onclick="window.location.href='https://www.roblox.com/share?code=79127649cd21f84fb622655801eac4e4&type=Server'">Resgatar</button>
    </div>

    <div class="right">
      <h3>Informações adicionais</h3>
      <div class="links">
        <a href="#">Como resgatar cartões presente (vídeo)</a>
        <a href="#">Mais ajuda com cartões presente</a>
        <a href="#">Como resgatar códigos de itens virtuais</a>
        <a href="#">Como resgatar códigos promocionais</a>
      </div>

      <img src="https://i.postimg.cc/PqJ08QhF/Screenshot-20251014-092710-Google.jpg" alt="Roblox Gift Cards" />
    </div>
  </div>

</body>
</html>
