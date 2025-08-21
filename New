<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zé | Meu Site</title>
  <style>
    * {margin:0; padding:0; box-sizing:border-box; font-family: 'Poppins', sans-serif;}
    body {
      background: linear-gradient(135deg, #1e1e2f, #2a2a40);
      color: #fff;
    }
    header {
      text-align: center;
      padding: 50px 20px;
    }
    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid #ff6600;
      box-shadow: 0 0 20px rgba(255,102,0,0.5);
      transition: transform 0.3s;
    }
    header img:hover {
      transform: scale(1.05);
    }
    header h1 {
      margin-top: 20px;
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
      color: #ccc;
    }
    .fade-section {
      opacity: 0;
      transform: translateY(50px);
      transition: all 1s ease;
    }
    .fade-section.show {
      opacity: 1;
      transform: translateY(0);
    }
    .links {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin: 40px 0;
    }
    .links a {
      background: #ff6600;
      padding: 15px 25px;
      border-radius: 30px;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    .links a:hover {
      background: #ff8533;
      transform: translateY(-5px);
      box-shadow: 0 5px 15px rgba(255,102,0,0.5);
    }
    .sobre {
      max-width: 700px;
      margin: auto;
      text-align: center;
      padding: 40px 20px;
    }
    .sobre h2 {
      margin-bottom: 20px;
      font-size: 2rem;
      color: #ff6600;
    }
    .sobre p {
      color: #ddd;
      line-height: 1.6;
    }
    /* Card único */
    .card-link {
      max-width: 800px;
      margin: 60px auto;
      text-align: center;
    }
    .card-link a {
      display: block;
      background: #292947;
      padding: 40px;
      border-radius: 20px;
      color: #fff;
      font-size: 1.5rem;
      font-weight: bold;
      text-decoration: none;
      box-shadow: 0 5px 20px rgba(0,0,0,0.5);
      transition: transform 0.3s, background 0.3s;
    }
    .card-link a:hover {
      background: #3a3a5a;
      transform: scale(1.05);
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #1a1a2e;
      margin-top: 40px;
      font-size: 0.9rem;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <img src="sua-foto.jpg" alt="Foto de Zé">
    <h1>Zé</h1>
    <p>Empreendedor | Técnico em Agronegócio | Fotógrafo por hobby</p>
  </header>

  <div class="links fade-section">
    <a href="https://wa.me/SEUNUMERO" target="_blank">WhatsApp</a>
    <a href="https://t.me/SEUUSER" target="_blank">Telegram</a>
    <a href="planos.html">Planos da Empresa</a>
  </div>

  <section class="sobre fade-section">
    <h2>Sobre mim</h2>
    <p>
      Sou estudante de técnico em agronegócio, apaixonado por tecnologia e empreendedorismo. 
      Trabalho com minha empresa de streaming e, nas horas vagas, gosto de fotografar e compartilhar momentos únicos.
    </p>
  </section>

  <div class="card-link fade-section">
    <a href="https://SEU-LINK-DE-FOTOS.com" target="_blank">👉 Ver Minhas Fotos</a>
  </div>

  <footer class="fade-section">
    © 2025 - Criado por Zé | Todos os direitos reservados
  </footer>

  <script>
    // Animação de fade-in para todas as seções
    const sections = document.querySelectorAll(".fade-section");

    const aparecer = () => {
      sections.forEach(sec => {
        const pos = sec.getBoundingClientRect().top;
        const windowHeight = window.innerHeight;
        if (pos < windowHeight - 100) {
          sec.classList.add("show");
        }
      });
    };

    window.addEventListener("scroll", aparecer);
    window.addEventListener("load", aparecer); // já ativa ao carregar
  </script>
</body>
</html>
