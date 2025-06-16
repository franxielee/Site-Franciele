<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Franciele Amanda | Dev & Automação</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f7f9fc;
      color: #333;
    }

    header {
      background: linear-gradient(to right, #19348b, #19348b);
      color: white;
      padding: 80px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 0;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    .section-title {
      font-size: 2rem;
      color: #19348b;
      margin-bottom: 20px;
      text-align: center;
    }

    .card {
      background-color: white;
      border-radius: 10px;
      padding: 25px;
      margin-bottom: 30px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
      text-align: center;
    }

    .minha-foto {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 20px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s ease;
    }

    .minha-foto:hover {
      transform: scale(1.05);
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      margin: 10px 0;
    }

    a {
      color: #19348b;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    a.btn {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      background-color: #19348b;
      color: white;
      border-radius: 5px;
      text-decoration: none;
    }

    a.btn:hover {
      background-color: #142b6b;
    }

    footer {
      background-color: #111827;
      color: white;
      text-align: center;
      padding: 30px 20px;
      margin-top: 60px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Franciele Amanda</h1>
    <p>Automação | Apps Script | Dados | Inovação</p>
  </header>

  <section>
    <h2 class="section-title">Sobre mim</h2>
    <div class="card">
      <img
        src="https://media.licdn.com/dms/image/v2/D4D03AQE8WJCTRgAnLg/profile-displayphoto-shrink_800_800/B4DZaDllyxHwAc-/0/1745964392422?e=1755734400&v=beta&t=DrwGCduCFIaLq5kzSzHd5F-mAJDzcyOb2R-IeTYkG_w"
        alt="Foto da Franciele"
        class="minha-foto"
      >
      <p>Sou apaixonada por transformar processos manuais em soluções automatizadas. Desenvolvo scripts em Google Apps Script, organizo dados em Google Sheets e ajudo times a ganharem tempo e eficiência com tecnologia.</p>
    </div>

    <h2 class="section-title">Serviços</h2>
    <div class="card">
      <ul>
        <li>Criação de automações com Google Apps Script</li>
        <li>Envio automático de e-mails com dados filtrados</li>
        <li>Scripts personalizados para sua rotina</li>
      </ul>
    </div>

    <h2 class="section-title">Projetos</h2>
    <div class="card">
      <h3>FilialChargeBot</h3>
      <p>Script que automatiza cobranças por filial com envio de e-mails e CSVs personalizados.</p>
    </div>
    <div class="card">
      <h3>SellerSyncMailer</h3>
      <p>Automação que envia relatórios preventivos com base em dados logísticos de planilhas.</p>
    </div>

    <h2 class="section-title">Contato</h2>
    <div class="card">
      <p>Quer automatizar processos na sua empresa ou criar soluções sob medida?</p>
      <p>Email: franciele@example.com<br>
         LinkedIn: <a href="https://linkedin.com/in/franxielee" target="_blank">linkedin.com/in/franxielee</a></p>
      <a href="https://wa.me/5599999999999" class="btn" target="_blank">Fale comigo</a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Franciele Amanda. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
