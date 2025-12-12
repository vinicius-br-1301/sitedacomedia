<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>O Melhor da Comédia</title>

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link
    href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Lobster&family=Merriweather:wght@700&display=swap"
    rel="stylesheet">

  <style>
    body {
      font-family: 'Inter', sans-serif;
    }

    .navbar-brand {
      font-family: 'Lobster', cursive;
      font-size: 2rem;
    }

    h2,
    .card-title {
      font-family: 'Merriweather', serif;
    }

    html {
      scroll-behavior: smooth;
    }

    .hero-section {
      background-image: url('https://www.shutterstock.com/shutterstock/photos/2454926187/display_1500/stock-photo-happy-friends-enjoying-in-movie-projection-in-theater-focus-is-on-african-american-woman-eating-2454926187.jpg');
      background-size: cover;
      background-position: center;
      height: 60vh;
    }

    .carousel-item img {
      height: 400px;
      object-fit: cover;
      object-position: top;
    }


    .curtido {
      transform: scale(1.05);
      transition: all 0.2s ease;
    }
  </style>
</head>

<body class="bg-light">

  <nav class="navbar navbar-expand-lg navbar-dark bg-dark shadow sticky-top">
    <div class="container">
      <a class="navbar-brand text-white" href="#"> O Melhor da Comédia</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active text-white" href="#">Início</a></li>
          <li class="nav-item"><a class="nav-link text-white" href="#descricao">O Gênero</a></li>
          <li class="nav-item"><a class="nav-link text-white" href="#motivos">Por que Assistir?</a></li>
          <li class="nav-item"><a class="nav-link text-white" href="#galeria">Galeria</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <header class="hero-section d-flex align-items-center justify-content-center text-white text-center shadow-lg">
    <div class="bg-black bg-opacity-50 p-5 rounded-3">
      <h1 class="display-3 fw-bold" style="font-family: 'Merriweather', serif;">O Mundo Mágico da Comédia</h1>
      <p class="lead fs-4">Descubra os filmes que definiram gerações e garantiram as melhores risadas.</p>
    </div>
  </header>

  <main class="container my-5">

    <section id="descricao" class="my-5 p-4 bg-white shadow-sm rounded-3">
      <h2 class="display-5 fw-bold mb-3 text-dark text-center">O que é o Cinema de Comédia?</h2>
      <p class="fs-5 text-secondary">
        O cinema de comédia é um gênero que busca provocar o riso e o entretenimento do público. Utilizando o humor de
        formas variadas, desde a sátira social, a paródia e o pastelão, esses filmes têm o poder de aliviar o estresse.
      </p>
    </section>

    <section id="motivos" class="my-5">
      <h2 class="display-5 fw-bold mb-4 text-dark text-center">Por que Amamos Comédia?</h2>
      <div class="row g-4">

        <div class="col-md-4">
          <div class="card h-100 shadow-sm border-0 rounded-3">
            <div class="card-body p-4 text-center">
              <h5 class="card-title fs-4 fw-semibold text-primary">Reduz o Estresse</h5>
              <p class="card-text text-secondary">Uma boa gargalhada faz esquecer os problemas e alivia a mente.</p>
              <button class="btn btn-outline-primary btn-curtir w-100 mt-3">Curtir Motivo</button>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card h-100 shadow-sm border-0 rounded-3">
            <div class="card-body p-4 text-center">
              <h5 class="card-title fs-4 fw-semibold text-primary">Conexão Social</h5>
              <p class="card-text text-secondary">Assistir a uma comédia com amigos ou família cria memórias.</p>
              <button class="btn btn-outline-primary btn-curtir w-100 mt-3">Curtir Motivo</button>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card h-100 shadow-sm border-0 rounded-3">
            <div class="card-body p-4 text-center">
              <h5 class="card-title fs-4 fw-semibold text-primary">Crítica Inteligente</h5>
              <p class="card-text text-secondary">Muitas comédias usam o humor para fazer críticas sociais.</p>
              <button class="btn btn-outline-primary btn-curtir w-100 mt-3">Curtir Motivo</button>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="galeria" class="my-5">
      <h2 class="display-5 fw-bold mb-4 text-dark text-center">Filmes Inesquecíveis</h2>

      <div id="movieCarousel" class="carousel slide shadow-lg rounded-3 overflow-hidden" data-bs-ride="carousel">

        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://placehold.co/1200x400/3498db/ffffff?text=O+Auto+da+Compadecida" class="d-block w-100"
              alt="O Auto da Compadecida">
            <div class="carousel-caption d-none d-md-block bg-black bg-opacity-75 rounded-3 p-3">
              <h5 class="fw-bold">O Auto da Compadecida (2000)</h5>
              <p class="fs-6">As aventuras de João Grilo e Chicó no sertão.</p>
            </div>
          </div>

          <div class="carousel-item">
            <img src="https://placehold.co/1200x400/2980b9/ffffff?text=Tempos+Modernos" class="d-block w-100"
              alt="Tempos Modernos">
            <div class="carousel-caption d-none d-md-block bg-black bg-opacity-75 rounded-3 p-3">
              <h5 class="fw-bold">Tempos Modernos (1936)</h5>
              <p class="fs-6">Chaplin luta para sobreviver ao mundo industrializado.</p>
            </div>
          </div>

          <div class="carousel-item">
            <img src="https://placehold.co/1200x400/5dade2/ffffff?text=Minha+Mãe+é+uma+Peça" class="d-block w-100"
              alt="Minha Mãe é uma Peça">
            <div class="carousel-caption d-none d-md-block bg-black bg-opacity-75 rounded-3 p-3">
              <h5 class="fw-bold">Minha Mãe é uma Peça (2013)</h5>
              <p class="fs-6">Dona Hermínia e suas confusões familiares.</p>
            </div>
          </div>

          <div class="carousel-item">
            <img src="https://placehold.co/1200x400/36D1DC/ffffff?text=Se+Beber,+Não+Case!" class="d-block w-100"
              alt="Se Beber, Não Case!">
            <div class="carousel-caption d-none d-md-block bg-black bg-opacity-75 rounded-3 p-3">
              <h5 class="fw-bold">Se Beber, Não Case! (2009)</h5>
              <p class="fs-6">Uma despedida de solteiro em Las Vegas que dá errado.</p>
            </div>
          </div>

          <div class="carousel-item">
            <img src="https://placehold.co/1200x400/1D4ED8/ffffff?text=As+Branquelas" class="d-block w-100"
              alt="As Branquelas">
            <div class="carousel-caption d-none d-md-block bg-black bg-opacity-75 rounded-3 p-3">
              <h5 class="fw-bold">As Branquelas (2004)</h5>
              <p class="fs-6">Dois agentes do FBI disfarçados de socialites.</p>
            </div>
          </div>

          <div class="carousel-item">
            <img src="https://placehold.co/1200x400/2c3e50/ffffff?text=Monty+Python" class="d-block w-100"
              alt="Monty Python">
            <div class="carousel-caption d-none d-md-block bg-black bg-opacity-75 rounded-3 p-3">
              <h5 class="fw-bold">Monty Python e o Cálice Sagrado (1975)</h5>
              <p class="fs-6">Humor absurdo na era medieval.</p>
            </div>
          </div>

          <div class="carousel-item">
            <img src="https://placehold.co/1200x400/16a085/ffffff?text=Se+Eu+Fosse+Você" class="d-block w-100"
              alt="Se Eu Fosse Você">
            <div class="carousel-caption d-none d-md-block bg-black bg-opacity-75 rounded-3 p-3">
              <h5 class="fw-bold">Se Eu Fosse Você (2006)</h5>
              <p class="fs-6">Um casal troca de corpos magicamente.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="https://placehold.co/1200x400/e67e22/ffffff?text=Os+Caça-Fantasmas" class="d-block w-100"
              alt="Os Caça-Fantasmas">
            <div class="carousel-caption d-none d-md-block bg-black bg-opacity-75 rounded-3 p-3">
              <h5 class="fw-bold">Os Caça-Fantasmas (1984)</h5>
              <p class="fs-6">Quem você vai chamar?</p>
            </div>
          </div>

        </div> <button class="carousel-control-prev" type="button" data-bs-target="#movieCarousel" data-bs-slide="prev">
          <span class="carousel-control-prev-icon"></span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#movieCarousel" data-bs-slide="next">
          <span class="carousel-control-next-icon"></span>
        </button>
      </div>
    </section>

  </main>

  <footer class="bg-dark text-white p-4 text-center mt-5">
    <div class="container">
      <p class="mb-0">&copy; 2025 O Melhor da Comédia.</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

  <script>

    const botoesCurtir = document.querySelectorAll('.btn-curtir');


    botoesCurtir.forEach(botao => {
      botao.addEventListener('click', function () {

        //  Verifica se o botão já foi clicado pelo texto ou classe
        if (this.classList.contains('btn-success')) {
          // Desfaz a ação
          this.classList.remove('btn-success', 'curtido');
          this.classList.add('btn-outline-primary');
          this.textContent = "Curtir Motivo";
        } else {
          // Manipula as classes CSS (remove o azul e adiciona o verde)
          this.classList.remove('btn-outline-primary');
          this.classList.add('btn-success', 'curtido');

          //  Manipula o texto do botão
          this.textContent = "Você curtiu isso! ";
        }

      });
    });
  </script>

</body>

</html>
