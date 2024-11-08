��#   P I _ M a r c i o 
 
 index:
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conheçao surso de DSM</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
    <link rel="shortcut icon" href="img/Imagem DSMsem fundo Real.png">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-light" style="background: linear-gradient(#310E4E, #000000);">
        <img src="img/Imagem DSMsem fundo Real.png" alt="Logo" width="25" height="25" class="d-inline-block align-text-top">
        <a class="navbar-brand" href="#">DSM</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Apresentando o curso</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Disciplinas</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Profissões</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Depoimentos</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Duvidas</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Quizz</a>
              <li class="nav-item">
                <a class="nav-link" href="#">Endereço e contato</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Quem fez a página</a>
              </li>
          </ul>
        </div>
      </nav>

      <div class="card" style="width: 100%; height: 13rem; color: #000000; text-align: center;">
        <div class="card-body">
            O novo curso de Tecnologia da Fatec Indaiatuba!
        </div>
      </div>
      <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img class="d-block w-10" src="img/Imagem DSMsem fundo Real.png" alt="First slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-10" src="img/Imagem DSMsem fundo Real.png" alt="Second slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-10" src="img/Imagem DSMsem fundo Real.png" alt="Third slide">
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Anterior</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Próximo</span>
        </a>
      </div>
    
      <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
      <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js"></script>
      <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js"></script>
</body>
</html>

JavaScript:
$('.carousel').carousel({
    interval: 7
  })
