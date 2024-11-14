��#   P I _ M a r c i o 
 
HTML:

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conheçao curso de DSM</title>
    <link rel="stylesheet" href="css/estilos.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
    <link rel="shortcut icon" href="img/Imagem DSMsem fundo Real.png">
</head>
<body style="background-color: #000000; font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-size: larger;">
    <nav class="navbar navbar-expand-lg navbar-dark bg-light" style="background: linear-gradient(#310E4E, #000000);">
        <img src="img/Imagem DSMsem fundo Real.png" alt="Logo" width="30" height="30" class="d-inline-block align-text-top">
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
      <h3>
      <div class="card" style="width: 100%; height: 13rem; color: #ffffff; text-align: center; background-color: #000000;">
        <div class="card-body">
            O novo curso de Tecnologia da Fatec Indaiatuba!
           <br>
            <img src="img/Imagem_DSMsem_fundo-removebg-preview.png" alt="">
          </h3>
        </div>
        </div>
        <div class="container">
            <div class="row" style="background-color: #000000;">
               <div id="demo" class="carousel slide" data-ride="carousel">
               <!-- Carrossel -->
               <div class="carousel-inner center-block">
                 <div class="carousel-item active">
                   <img class="d-block w-100" src="img/Linux.jpg" alt="Linux">
                 </div>
                 <div class="carousel-item">
                   <img class="d-block w-100" src="img/Python.png" alt="Python">
                 </div>
                 <div class="carousel-item">
                  <img class="d-block w-100" src="img/VS Code.webp" alt="VS Code">
                </div>
               </div>
         
               <!-- Controle do carrossel -->
               <a class="carousel-control-prev" href="#demo" data-slide="prev">
                 <span class="carousel-control-prev-icon"></span>
               </a>
               <a class="carousel-control-next" href="#demo" data-slide="next">
                 <span class="carousel-control-next-icon"></span>
               </a>
         
             </div>
             </div>
          </div>
          <h3>
          <div class="card" style="width: 100%; height: 13rem; color: #ffffff; text-align: center; background-color: #000000; text-align: center; text-justify: auto;">
            <div class="card-body"> <br>
              <br>Aprenda a criar interfaces  atraentes e funcionais para aplicativos e sites,<br>
              <br>otimizar o desenvolvimento de software,  conceitos e práticas de aplicação em nuvem, <br>
              <br>criação de sistemas inteligentes com IA e muito mais!
              </h3>
            </div>
            </div>
    
      <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
      <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js"></script>
      <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js"></script>
</body>
</html>

JavaScript:

('carousel').carousel()

$('.carousel').carousel({
    interval: 7
  })
