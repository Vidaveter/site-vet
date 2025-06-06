<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vida Veter - Atendimento Veterinário em Domicílio</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Montserrat', sans-serif;
      margin: 0;
      background: linear-gradient(to bottom, #cce4ff, #ffffff);
      color: #002b5c;
    }
    header {
      background: linear-gradient(90deg, #005fa3, #66b2ff);
      color: white;
      padding: 20px;
      text-align: center;
      animation: fadeIn 1s ease-in;
      position: sticky;
      top: 0;
      z-index: 1000;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 15px;
    }
    header img.logo {
      height: 50px;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-10px); }
      to { opacity: 1; transform: translateY(0); }
    }
    section {
      padding: 20px;
      animation: fadeIn 1s ease-in;
    }
    .banner {
      background: url('https://cdn.pixabay.com/photo/2021/08/27/17/21/dog-and-cat-6579957_1280.jpg') no-repeat center center/cover;
      height: 300px;
      border-bottom: 5px solid #005c99;
    }
    h2 {
      color: #004080;
      margin-top: 0;
    }
    .servicos {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .servico {
      flex: 1 1 250px;
      background-color: #d6eaff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s;
      text-align: center;
    }
    .servico img {
      max-width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 10px;
    }
    .servico:hover {
      transform: scale(1.05);
    }
    .contatos, .formulario {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin: 20px 0;
      gap: 20px;
    }
    .contato-link a {
      background-color: #25D366;
      color: white;
      padding: 15px 25px;
      border-radius: 30px;
      text-decoration: none;
      font-size: 18px;
      transition: background-color 0.3s;
      display: inline-block;
    }
    .contato-link a:hover {
      background-color: #1ebe5d;
    }
    .contato-link.instagram a {
      background-color: #405DE6;
    }
    .contato-link.instagram a:hover {
      background-color: #3048c3;
    }
    form {
      background-color: #d6eaff;
      padding: 20px;
      border-radius: 10px;
      max-width: 500px;
      width: 100%;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    form label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }
    form input, form select, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #aaa;
      border-radius: 5px;
      font-family: 'Montserrat', sans-serif;
    }
    form button {
      background-color: #005fa3;
      color: white;
      border: none;
      padding: 12px 20px;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    form button:hover {
      background-color: #004080;
    }
    .whatsapp-fixed {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      padding: 10px 15px;
      border-radius: 50px;
      text-decoration: none;
      font-size: 18px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
      z-index: 1000;
    }
    footer {
      background: linear-gradient(to right, #005fa3, #3399ff);
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }
    @media (max-width: 600px) {
      header {
        flex-direction: column;
      }
      .servicos {
        flex-direction: column;
        align-items: center;
      }
      .servico {
        width: 100%;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="sua-logo.png" alt="Logo Vida Veter" class="logo">
    <div>
      <h1>Vida Veter</h1>
      <p>Atendimento veterinário em casa com conforto e exclusividade!</p>
    </div>
  </header>

  <div class="banner"></div>

  <section>
    <h2>Bem-vindo à Vida Veter</h2>
    <p>
      Bem-vindo à Vida Veter, sua clínica veterinária em domicílio em Belo Horizonte e região! Nos dedicamos a proporcionar o melhor atendimento para o seu pet, no conforto do lar. Nosso diferencial está em oferecer um serviço personalizado e exclusivo, garantindo que seu animal de estimação receba toda a atenção e cuidado necessários, sem o estresse de ambientes desconhecidos. Na Vida Veter, entendemos a importância de estar presente nos momentos mais delicados e especiais da vida do seu pet. Com serviços que vão desde consultas veterinárias e vacinação até atendimento de emergência e eutanásia, estamos aqui para cuidar do seu companheiro de quatro patas com amor e dedicação. Conte conosco para proporcionar uma experiência tranquila e segura para o seu animal, sempre com a comodidade e flexibilidade que vocês merecem. Agende agora mesmo e traga mais conforto para a vida do seu melhor amigo!
    </p>
  </section>

  <section>
    <h2>Serviços</h2>
    <div class="servicos">
      <div class="servico">
        <img src="https://cdn.pixabay.com/photo/2016/03/27/22/22/dog-1284238_960_720.jpg" alt="Consulta Veterinária">
        <h3>Consulta Veterinária</h3>
        <p>Consulta Veterinária personalizada e exclusiva no conforto do seu lar, proporcionando o melhor cuidado para o seu pet.</p>
      </div>
      <div class="servico">
        <img src="https://cdn.pixabay.com/photo/2016/11/29/12/54/veterinarian-1863712_1280.jpg" alt="Vacinação">
        <h3>Vacinação</h3>
        <p>Vacinação em Casa: Cuide da saúde do seu pet com comodidade e segurança, sem sair de casa.</p>
      </div>
      <div class="servico">
        <img src="https://cdn.pixabay.com/photo/2019/11/28/22/55/dog-4661609_1280.jpg" alt="Exames Laboratoriais">
        <h3>Exames Laboratoriais</h3>
        <p>Exames laboratoriais realizados no conforto do lar do seu pet, garantindo comodidade e tranquilidade para você e seu animal de estimação.</p>
      </div>
      <div class="servico">
        <img src="https://cdn.pixabay.com/photo/2017/02/27/13/54/veterinary-2104079_1280.jpg" alt="Tratamento e Curativo">
        <h3>Tratamentos e Curativos</h3>
        <p>Cuide do seu pet com todo o carinho e atenção necessários, no conforto do seu lar.</p>
      </div>
      <div class="servico">
        <img src="https://cdn.pixabay.com/photo/2015/06/08/15/11/veterinary-801890_1280.jpg" alt="Eutanásia">
        <h3>Eutanásia</h3>
        <p>Dê ao seu pet o adeus que ele merece com nosso serviço de Eutanásia, realizado com respeito e compaixão no conforto do seu lar.</p>
      </div>
      <div class="servico">
        <img src="https://cdn.pixabay.com/photo/2021/06/15/13/56/veterinarian-6337273_1280.jpg" alt="Emergência">
        <h3>Atendimento de Emergência</h3>
        <p>Com o Atendimento de Emergência da Vida Veter, seu pet recebe cuidados especializados no conforto do lar, a qualquer hora do dia ou da noite.</p>
      </div>
      <div class="servico">
        <img src="https://cdn.pixabay.com/photo/2016/03/27/19/40/veterinarian-1284207_1280.jpg" alt="Radiografia e Ultrassom">
        <h3>Radiografia e Ultrassom</h3>
        <p>Oferecemos exames de imagem como radiografia e ultrassom realizados em casa, com toda a praticidade e segurança que seu pet merece.</p>
      </div>
    </div>
  </section>

  <section class="formulario">
    <h2>Agende um Atendimento</h2>
    <form action="#" method="post">
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome" required>

      <label for="telefone">Telefone (WhatsApp):</label>
      <input type="tel" id="telefone" name="telefone" required>

      <label for="endereco">Endereço:</label>
      <input type="text" id="endereco" name="endereco" required>

      <label for="tipo">Tipo de Atendimento:</label>
      <select id="tipo" name="tipo" required>
        <option value="Consulta">Consulta</option>
        <option value="Vacinação">Vacinação</option>
        <option value="Exames">Exames Laboratoriais</option>
        <option value="Tratamento">Tratamentos e Curativos</option>
        <option value="Eutanasia">Eutanásia</option>
        <option value="Emergencia">Emergência</option>
        <option value="Imagem">Radiografia e Ultrassom</option>
      </select>

      <label for="mensagem">Mensagem (opcional):</label>
      <textarea id="mensagem" name="mensagem" rows="4"></textarea>

      <button type="submit">Enviar</button>
    </form>
  </section>

  <section class="contatos">
    <div class="contato-link">
      <a href="https://wa.me/5531983222242" target="_blank">Fale conosco no WhatsApp</a>
    </div>
    <div class="contato-link instagram">
      <a href="https://www.instagram.com/vidaveter?igsh=MTFydXlpODJueHA2bQ==" target="_blank">Siga no Instagram</a>
    </div>
  </section>

  <a class="whatsapp-fixed" href="https://wa.me/5531983222242" target="_blank">WhatsApp</a>

  <footer>
    <p>&copy; 2025 Vida Veter - Atendimento Veterinário em Domicílio</p>
  </footer>
</body>
</html>
