<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Acesso Premium - Sistema de Palpites IA</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 30px;
    }

    h1 {
      font-size: 28px;
      margin-bottom: 10px;
      text-align: center;
    }

    p {
      font-size: 16px;
      margin-bottom: 20px;
      text-align: center;
      max-width: 500px;
    }

    .benefits {
      background: rgba(255, 255, 255, 0.05);
      padding: 15px 20px;
      border-radius: 10px;
      margin-bottom: 20px;
      width: 100%;
      max-width: 500px;
    }

    .benefits ul {
      list-style: none;
      padding: 0;
    }

    .benefits li {
      margin-bottom: 10px;
      position: relative;
      padding-left: 20px;
    }

    .benefits li::before {
      content: "✔";
      position: absolute;
      left: 0;
      color: #4caf50;
    }

    .pix-box {
      background-color: #ffffff0f;
      padding: 15px;
      border-radius: 8px;
      margin-bottom: 20px;
      text-align: center;
      word-break: break-word;
    }

    button.copy {
      background-color: #4caf50;
      border: none;
      padding: 10px 20px;
      color: white;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 10px;
    }

    button.copy:hover {
      background-color: #45a049;
    }

    .confirm {
      background-color: #2196f3;
      border: none;
      padding: 12px 25px;
      color: white;
      font-size: 17px;
      border-radius: 6px;
      cursor: pointer;
      margin-top: 20px;
      text-decoration: none;
      display: inline-block;
    }

    .confirm:hover {
      background-color: #1e88e5;
    }

    footer {
      margin-top: 40px;
      font-size: 14px;
      color: #aaa;
      text-align: center;
    }
  </style>
</head>
<body>
  <h1>Desbloqueie Seu Acesso Premium</h1>
  <p>Realize o pagamento via Pix e tenha acesso aos melhores palpites automáticos baseados em Inteligência Artificial.</p>

  <div class="benefits">
    <ul>
      <li>Palpites gerados automaticamente</li>
      <li>Análise precisa com IA</li>
      <li>Entregue direto no seu WhatsApp</li>
      <li>Suporte rápido e direto</li>
    </ul>
  </div>

  <div class="pix-box">
    <strong>Chave Pix (Copia e Cola):</strong><br><br>
    <code id="pix">00020126360014br.gov.bcb.pix0114+556599688674152040000530398654046.905802BR5918Lukas Silva Soares6008Brasilia62240520daqr231463059835516963045480</code>
    <br>
    <button class="copy" onclick="copyPix()">Copiar Código</button>
  </div>

  <a class="confirm" href="https://wa.me/5565996886741?text=Olá!+Efetuei+o+pagamento+e+gostaria+de+receber+meu+acesso.">Confirmar Pagamento</a>

  <footer>
    © 2025 IA Esportiva - Todos os direitos reservados.
  </footer>

  <script>
    function copyPix() {
      const pixCode = document.getElementById("pix").innerText;
      navigator.clipboard.writeText(pixCode).then(() => {
        alert("Código Pix copiado com sucesso!");
      });
    }
  </script>
</body>
</html>
