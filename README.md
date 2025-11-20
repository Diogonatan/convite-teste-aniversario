# convite-teste-aniversario
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Convite de Aniversário</title>

  <style>
    body {
      background-image: url("img/fotodiogo.jpg");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;

      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      color: #556B2F;
    }

    .convite {
      background-color: rgba(0, 0, 0, 0.85);
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0px 4px 10px rgba(0,0,0,0.5);
      max-width: 400px;
      text-align: center;
      color: #6B8E23;
    }

    h1 {
      color: #9ACD32;
    }

    .detalhes {
      font-size: 18px;
      margin-top: 15px;
    }

    .botao {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background-color: #6B8E23;
      color: black;
      border-radius: 10px;
      text-decoration: none;
      font-weight: bold;
    }

    .botao:hover {
      background-color: #9ACD32;
    }
  </style>

</head>
<body>

  <div class="convite">
    <h1>🎉 Convite Especial 🎉</h1>
    <p>Você está convidado para comemorar o meu aniversário!</p>

    <div class="detalhes">
      <p><strong>Data:</strong> 50 de Novembro de 2025</p>
      <p><strong>Hora:</strong> 19h00</p>
      <p><strong>Local:</strong> Minha Casa</p>
    </div>

    <a href="#" class="botao" onclick="confirmarPresenca()">Confirmar Presença</a>
  </div>

  <script>
    function confirmarPresenca() {
      alert("✅ Presença confirmada! Obrigado por confirmar!");
    }
  </script>

</body>
</html>



