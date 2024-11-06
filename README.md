<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anaflix - Assista aos Melhores Filmes</title>
  <style>
    /* Estilos gerais */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #2b0a3d;
      color: #ffffff;
      text-align: center;
    }

    /* Cabeçalho */
    header {
      padding: 20px;
      background-color: #4b0082;
      color: #e6e6fa;
    }

    h1 {
      font-size: 2.5em;
      margin: 0;
    }

    /* Grid de Filmes */
    .catalogo {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      padding: 20px;
    }

    /* Estilo dos cartões de filmes */
    .filme-card {
      background-color: #5d3c6e;
      border-radius: 8px;
      width: 320px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
    }

    .filme-card iframe {
      width: 100%;
      height: 180px;
    }

    .filme-info {
      padding: 15px;
    }

    .filme-titulo {
      font-size: 18px;
      font-weight: bold;
      color: #dda0dd;
      margin: 0 0 10px;
    }

    .filme-descricao {
      font-size: 14px;
      color: #e0bee0;
    }
  </style>
</head>
<body>

  <!-- Cabeçalho do Site -->
  <header>
    <h1>Anaflix</h1>
    <p>Assista aos melhores filmes e trailers na sua plataforma favorita!</p>
  </header>

  <!-- Catálogo de Filmes -->
  <div class="catalogo">

    <!-- Card do Filme 1 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/watch?v=esOMdVTJISE" title="After" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">After</h2>
        <p class="filme-descricao">Uma jovem se apaixona por um rapaz misterioso, o que muda sua vida para sempre.</p>
      </div>
    </div>

    <!-- Card do Filme 2 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/watch?v=gyd3X62IcEM" title="Através da Minha Janela" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">Através da Minha Janela</h2>
        <p class="filme-descricao">Raquel está determinada a conquistar seu atraente vizinho, Ares.</p>
      </div>
    </div>

    <!-- Card do Filme 3 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/watch?v=QIalE8-E990" title="A Barraca do Beijo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">A Barraca do Beijo</h2>
        <p class="filme-descricao">Elle se apaixona pelo irmão mais velho do seu melhor amigo, o que complica tudo.</p>
      </div>
    </div>

    <!-- Card do Filme 4 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/watch?v=9zhzD0kWSi0" title="Por Lugares Incríveis" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">Por Lugares Incríveis</h2>
        <p class="filme-descricao">Dois adolescentes enfrentam traumas pessoais enquanto formam uma ligação especial.</p>
      </div>
    </div>

    <!-- Card do Filme 5 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/watch?v=_K_qbjm97tY" title="O Melhor de Mim" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">O Melhor de Mim</h2>
        <p class="filme-descricao">Um casal reencontra o amor após anos separados por acontecimentos trágicos.</p>
      </div>
    </div>

    <!-- Card do Filme 6 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/watch?v=ZUqU9SQOt10" title="Simplesmente Acontece" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">Simplesmente Acontece</h2>
        <p class="filme-descricao">Dois amigos de infância enfrentam desafios amorosos e descobrem seus sentimentos.</p>
      </div>
    </div>

    <!-- Card do Filme 7 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/embed/J5t1tyMlZyI" title="Era Uma Vez..." frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">Era Uma Vez...</h2>
        <p class="filme-descricao">Um romance improvável floresce entre pessoas de mundos diferentes.</p>
      </div>
    </div>

    <!-- Card do Filme 8 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/watch?v=DA3K6Xrx4HE" title="Venom" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">Venom</h2>
        <p class="filme-descricao">Um jornalista se torna hospedeiro de uma entidade alienígena com superpoderes.</p>
      </div>
    </div>

    <!-- Card do Filme 9 -->
    <div class="filme-card">
      <iframe src="https://www.youtube.com/embed/EXeTwQWrcwY" title="Batman Begins" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <div class="filme-info">
        <h2 class="filme-titulo">Batman Begins</h2>
        <p class="filme-descricao">A origem do Cavaleiro das Trevas e sua luta para proteger Gotham.</p>
      </div>
    </div>

  </div>
