<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Voucher Especial</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 2em;
    }
    .voucher {
      background-color: white;
      padding: 2em;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
      max-width: 600px;
    }
    .codigo {
      font-size: 1.5em;
      font-weight: bold;
      background-color: #eee;
      padding: 0.5em 1em;
      border-radius: 5px;
      margin: 1em 0;
    }
    button {
      background-color: #28a745;
      color: white;
      border: none;
      padding: 0.75em 1.5em;
      font-size: 1em;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      opacity: 0.9;
    }
    form {
      margin-top: 2em;
    }
    input, textarea {
      display: block;
      margin: 0.5em auto;
      width: 90%;
      max-width: 400px;
      padding: 0.75em;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
  </style>
</head>
<body>
  <div class="voucher">
    <h1>Parabéns pelo SEU DIA Edna Benicio da Silva, tão especial como VOCÊ! 🎉</h1>
    <p>Utilize o código abaixo para acessar o SEU PRESENTE ESPECIAL DE ANIVERSÁRIO enviado pela sua Agencia de Viagens - Partiu Turismo, a ser apresentado durante sua viagem, em caso de necessidade.</p>
    <div class="codigo" id="codigoVoucher">Voucher de Serviço - Partiu Turismo</div>
    <button onclick="copiarVoucher()">Copiar Código</button>
    <p id="confirmacao" style="color: green; display: none; margin-top: 1em;">Código copiado!</p>

    <hr style="margin: 2em 0;">
    <p><strong>Clique no botão a seguir para baixar o SEU PRESENTE ESPECIAL de aniversário, que está em arquivo PDF:</strong></p>
    <a href="https://drive.google.com/uc?export=download&id=1g7Rm-lZZEqsOZwrVkFboziMgGThRH534">
      <button style="background-color: #007bff;">Baixar Voucher PDF</button>
    </a>

    <form action="https://formsubmit.co/teu-email@exemplo.com" method="POST">
      <h2 style="margin-top: 2em;">Envie este PRESENTE ESPECIAL como voucher para o seu e-mail</h2>
      <input type="text" name="nome" placeholder="Nome completo" required>
      <input type="email" name="email" placeholder="Email" required>
      <input type="hidden" name="_subject" value="Voucher Partiu Turismo">
      <textarea name="mensagem" rows="4">Olá! Aqui está o seu voucher de presente: https://drive.google.com/uc?export=download&id=1g7Rm-lZZEqsOZwrVkFboziMgGThRH534</textarea>
      <button type="submit" style="background-color: #17a2b8;">Enviar por E-mail</button>
    </form>
  </div>

  <script>
    function copiarVoucher() {
      const codigo = document.getElementById("codigoVoucher").innerText;
      navigator.clipboard.writeText(codigo).then(() => {
        document.getElementById("confirmacao").style.display = 'block';
      });
    }
  </script>
</body>
</html>
