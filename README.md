<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dulces Merengones y Más</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #d8bfd8; /* Color violeta pastel */
    }
    header {
      background-color: #f9e4b7; /* Color pastel suave */
      padding: 20px;
      text-align: center;
    }
    .important {
      background-color: #ffffe0;
      padding: 10px;
      border-left: 5px solid #ffeb3b;
    }
    .highlight p {
      color: #ff5722;
      font-size: 18px;
      font-weight: bold;
    }
    .violet {
      background-color: #d8bffd; /* Violeta pastel */
    }
    .pink {
      background-color: #ffb6c1; /* Rosado pastel */
    }
    .blue {
      background-color: #add8e6; /* Azul pastel */
    }
    .box-text {
      margin-bottom: 10px;
    }
    img {
      max-width: 200px;
      height: auto;
      border-radius: 100px;
      margin-top: 0;
    }
  </style>
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <a class="navbar-brand" href="#">Merengones</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item"><a class="nav-link" href="#inicio">Inicio</a></li>
      <li class="nav-item"><a class="nav-link" href="#variedades">Variedades</a></li>
      <li class="nav-item"><a class="nav-link" href="#ingredientes">Ingredientes</a></li>
      <li class="nav-item"><a class="nav-link" href="#beneficios">Beneficios</a></li>
      <li class="nav-item"><a class="nav-link" href="#eventos">Eventos</a></li>
      <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
      <li class="nav-item"><a class="nav-link" href="#toppings">Toppings</a></li>
    </ul>
  </div>
</nav>

<header class="container mt-4">
  <h1>Dulces Merengones: Deliciosos y Esponjosos</h1>
</header>

<div class="container mt-4">
  <h2>Descripción del Producto</h2>
  <p class="important">Los merengones son dulces ligeros y esponjosos, elaborados principalmente con claras de huevo y azúcar. Su textura crujiente por fuera y suave por dentro los convierte en una delicia irresistible para cualquier ocasión.</p>
  <p>Otro contenido del inicio.</p>

  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTXlAGMty9wQurOViTGgImAbDyjavR1zavf1QfYaSkRxg&s" alt="Merengones">

  <h2>Subtemas o Temas</h2>
  <ul class="list-unstyled">
    <li><a href="#variedades">Variedades de Merengones</a></li>
    <li><a href="#ingredientes">Ingredientes y Recetas</a></li>
    <li><a href="#beneficios">Beneficios para la Salud</a></li>
    <li><a href="#eventos">Eventos y Celebraciones</a></li>
    <li><a href="#contacto">Contacto y Pedidos</a></li>
    <li><a href="#toppings">Toppings</a></li>
  </ul>

  <h2 id="variedades">Variedades de Merengones</h2>
  <p class="highlight">En esta sección encontrarás información sobre las diferentes variedades de merengones disponibles, desde los clásicos hasta los más innovadores.</p>

  <h2 id="ingredientes">Ingredientes y Recetas</h2>
  <p class="highlight">Aprende sobre los ingredientes básicos para preparar merengones y descubre recetas deliciosas para sorprender a tus amigos y familiares.</p>

  <h2 id="toppings">Toppings</h2>

  <table class="table table-bordered">
    <thead>
      <tr>
        <th>Tipo</th>
        <th>Ingredientes</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Dulce</td>
        <td>Mini Galletas, Gomitas, Chispa de chocolate, Malvaviscos, Chicles, Chocolatinas, Caramelos, Bombones.</td>
      </tr>
      <tr>
        <td>Salada</td>
        <td>Almendra, Avellana, Cacahuete, Castaña, Dátil, Nuez, Pasas, Piñón, Granola.</td>
      </tr>
      <tr>
        <td>Fruta</td>
        <td>Manzana, Plátano, Naranja, Uva, Fresa, Piña, Durazno, Cereza.</td>
      </tr>
    </tbody>
  </table>

  <h2 id="beneficios">Beneficios para la Salud</h2>
  <p>Descubre los beneficios nutricionales de los merengones y cómo pueden formar parte de una dieta equilibrada.</p>

  <h2 id="eventos">Eventos y Celebraciones</h2>
  <p>Encuentra ideas para incluir merengones en tus eventos y celebraciones especiales, desde cumpleaños hasta bodas.</p>

  <h2 id="contacto">Contacto y Pedidos</h2>
  <p>¿Quieres realizar un pedido de deliciosos merengones? Contáctanos al 3115654604.</p>
</div>

<div class="container box-container mt-4">
  <div class="row">
    <div class="col-12 mb-3">
      <div class="box large-box violet p-3">
        <p class="box-text">Información única y secretos de</p>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR6GLqRINKpMvw9wSN2AlD1HGAOUxGp-8-xXA&s" alt="Imagen de ejemplo" class="img-fluid">
      </div>
    </div>
    <div class="col-md-6">
      <div class="box small-box pink p-3">
        <h2>Premium</h2>
        <p>Se un cliente premium, por compras 5 veces en nuestros locales obtendrás promociones.</p>
      </div>
    </div>
    <div class="col-md-6">
      <div class="box small-box blue p-3">
        <h2>Promociones</h2>
        <p>Los martes agrega dos toppings más, por compras mayores de 3 te damos el otro completamente gratis.</p>
      </div>
    </div>
  </div>
</div>

<div class="container mt-4">
  <h3>Autor</h3>
  <p>Este manual fue creado por <a href="https://devcode.la/cursos/html-css/#clases/html5/enlaces" target="_blank">Cabral</a>. Puedes escribirle un correo a <a href="mailto:CabralC@gmail.com">CabralC@gmail.com</a>.</p>
</div>

<!-- Bootstrap JS and dependencies -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
