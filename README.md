# Site - Código página principal: 
<!DOCTYPE html>
<html lang="pt-br">
<head>
  
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Style Site Danielly.css.html">
    <title> Site Danielly Goncalves Santos </title>
    <link rel="stylesheet" href="style site Danielly.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous">"
    <link href="CarrinhoComprasSite.html" rel="stylesheet">
    <script src="CarrinhoComprasSite.html"></script>
    <link href="Codigo site - Danielly Goncalves Santos - Produtos.html" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" integrity="sha512-vX6ufAA9stus6G2nCtHaXKdOvR6oAQOjgUJl4Ri7Lk2NArRfDAxIJQg4kKwG9mI+oGogdHrKvLsZjK8DQIk6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/js/all.min.js"></script>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha2/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/2.11.6/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha2/js/bootstrap.min.js"></script>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

  </head>
    
<body> 
  <section>
    <header>
           
        <figure>
        <img src="logo.png.PNG" weight = "30%" width="10%" style="margin-top: 10px; margin-bottom: 20px;">
        </figure>
<!-- Icone de cabeçalho -->
        <div class="icons-container">
          <i style="color: #78452b;" class="fas fa-shopping-cart icon"></i>
          <i class="fas fa-user icon"></i>
        </div>
          <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/js/all.min.js"></script>
  <script>
    // Script para redirecionar ao clicar no ícone do carrinho
    $(".cart-icon").click(function() {
      window.location.href = "CarrinhoComprasSite.html";
    });

    // Script para redirecionar ao clicar no ícone de usuário
    $(".user-icon").click(function() {
      window.location.href = "pagina_do_usuario.html";
    });
  </script>
        
    </header>
  </section>
  
  <!-- Barra de navegação -->
        <nav class="navbar navbar-expand-lg bg-body-tertiary" style="width: 54%;" style="height: 40%" style="border-radius: 10%;">
      <div style="margin-top: 0px;" class="container-fluid">
      <button class="navbar-toggler" style="position: relative;" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
      </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0" style="border: 5px;">
        <li class="nav-item">
        <a class="nav-link active" aria-current="page" href="#">&nbsp&nbsp&nbsp&nbsp Quem Somos :) &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</a>
        </li>
          <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
          Nossos Ambientes
          </a>
          <li class="nav-item">
          <a class="nav-link" href="#">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp Projetistas de plantão</a>
          </li>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Sala Estar</a></li>
            <li><a class="dropdown-item" href="#">Cozinha</a></li>
            <li><a class="dropdown-item" href="#">Sala de Jantar</a></li>
            <li><a class="dropdown-item" href="#">Quarto</a></li>
            <li><hr class="dropdown-divider"></li>
            </ul>
        </li>
        </ul>

          <!-- campode de pesquisa -->
      <form class="d-flex" role="Pesquisa">
        <input class="form-control me-2" style="margin-top: 7px;" type="Pesquisa" placeholder="Pesquisa" aria-label="Pesquisa">
        <button class="btn btn-outline-success"  style="text-align: center;" style="height: 25px;" type="submit">Pesquisa</button>
      </form>
    </div>
  </div>
</nav>

<!-- Script para controlar o carrossel -->
<script>
  $(document).ready(function() {
    // Função para trocar o slide para a esquerda
    $('.carousel-control-prev').click(function() {
      $('#carouselExampleDark').carousel('prev');
    });

    // Função para trocar o slide para a direita
    $('.carousel-control-next').click(function() {
      $('#carouselExampleDark').carousel('next');
    });
  });
</script>

  <!-- Foto principal -->
<div id="carouselExampleDark" style="left: 0px;" style="width: 0px;" style="margin-top: 20px;" class="carousel carousel-dark slide">
  <div class="carousel-inner" style="width: 1296px;">
    <div class="carousel-item active" data-bs-interval="10000">
      <img src="home-carrosel.png.png" class="d-block w-100" height="600px" alt="home-carrosel">
      <div class="carousel-caption d-none d-md-block">
        <h2>Design Exclusivo</h2>
        </div>
        </div>
        </div>
        </div>
        </body>
        </html>
        </div>

  <!-- Detalhe tracejado -->
<div>
<h1 style="color: #d9d9d9; margin-top: -25px" >---------------------------------------------------------------------------------</h1>
</div>

  
<!-- Primeira sessão de cards (fotos ambientes) -->
<div style="margin-top: 1px;" class="row row-cols-1 row-cols-md-3 g-4">
  <div class="col">
    <div style="width: 50%; height: 95%; background-color: #d9d9d9; left: 4%;" class="card h-300">
      <img src="cozinha-planejada.png.png" style="font-size: 0%;" class="card-img-top" alt="Cozinha-cards" width="200" height="250">
      <div class="card-body bg-gray">
        <h5 style="text-align: center; font-family:cursive; height: 30px; color: white; background-color:#674c38;  float: inline-start; opacity: 1; border-radius: 5px;"  class="card-title">Cozinhas</h5>
         </div>
      <div class="card-footer">
      </div>
    </div>
  </div>
  <div class="col">
    <div style="width: 50%; height: 95%; background-color: #d9d9d9; left: -45.5%;" class="card h-300">
      <img src="home 2.png" style="font-size: 0%; " class="card-img-top" alt="Home-cards"  width="200" height="250">
      <div class="card-body bg-gray">
        <h5 style="text-align: center; font-family:cursive; height: 30px; color: white; background-color:#674c38; float: inline-start; opacity: 1; border-radius: 5px;"  class="card-title">Home</h5>
         </div>
      <div class="card-footer">
      </div>
    </div>
  </div>
  <div class="col">
    <div style="width: 50%; height: 95%; background-color: #d9d9d9; left: -95%;" class="card h-300">
      <img src="jantar.png.png" style="font-size: 0%;" class="card-img-top" alt="Jantar-cards" width="200" height="250">
      <div class="card-body bg-gray">
        <h5 style="text-align: center; font-family:cursive; height: 30px; color: white; background-color:#674c38; float: inline-start; opacity: 1; border-radius: 5px;"  class="card-title">Jantar</h5>
         </div>
      <div style="mar" class="card-footer">
      </div>
    </div>
  </div>
</div>

<br>
<br>
<br>
<br>
<br>
<br>

<!-- Segunda sessão de cards (fotos ambientes) -->
<div style="margin-top: -160px;"  class="row row-cols-1 row-cols-md-3 g-4">
  <div class="col">
    <div  style="width: 50%; height: 95%; background-color: #d9d9d9; color: #674c38; left: 4%;" class="card h-300">
      <img src="quarto.png.png" style="font-size: 0%;" class="card-img-top" alt="Quarto-cards" width="200" height="250">
      <div class="card-body bg-gray">
        <h5 style="text-align: center; font-family:cursive; height: 30px; color: white; background-color:#674c38; float: inline-start; opacity: 1; border-radius: 5px;"  class="card-title">Quarto</h5>
         </div>
      <div  class="card-footer">
      </div>
    </div>
  </div>
  <div class="col">
    <div style="width: 50%; height: 95%; background-color: #d9d9d9; left: -45.5%;" class="card h-300">
      <img src="promocao.png.png" style="font-size: 0%; " class="card-img-top" alt="promocao"  width="200" height="250">
      <div class="card-body bg-gray">
        <h5 style="text-align: center; font-family:cursive; height: 30px; color: white; background-color:#674c38; float: inline-start; opacity: 1; border-radius: 5px;"  class="card-title">Descontos %</h5>
         </div>
      <div class="card-footer">
      </div>
    </div>
  </div>
  <div class="col">
    <div style="width: 50%; height: 95%; background-color: #d9d9d9; left: -95%;" class="card h-400">
      <img src="premio.png" style="font-size: 0%;" class="card-img-top" alt="Premio-cards" width="200" height="250">
      <div class="card-body bg-gray">
        <h5 style="text-align: center; font-family:cursive; height: 30px; color: white; background-color:#674c38; float: inline-start; opacity: 1; border-radius: 5px;"  class="card-title">Premiações</h5>
      </div> 
      <div style="mar"class="card-footer">
      </div>
    </div>
    </div>
</div>

<br>
<br>
<br>
<br>
<br>
<br>


<div>
  <h1 style="color: #d9d9d9; margin-top: -175px" >________________________&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp_________________________</h1>
</div>

<div>
<figure style="margin-top: 10px; margin-left: 500px;">
<img src="logo2.png" weight = "35%" width="15%">
</figure>
</div>

<br>
<br>

<!-- Footer -->
<footer style="background-color: #674c38; color: #fff; padding: 20px; width: 1296px; margin-top: -40px;">
  <div style="display: flex; justify-content: space-between; align-items: center;">
    <!-- Informações de endereço -->
    <div>
      <h3 style="color: #fff;">Onde nos encontrar:</h3>
      <p style="color: #fff;">Endereço: Rua das flores, 100 - Centro - São Paulo</p>
      <p style="margin-top: -15px; color: #fff;">Telefone: (11) 98765-0000</p>
    </div>


      <!-- Ícones de redes sociais -->
    <div>
      <h3 style="color: #fff; margin-top: -40px; margin-right: 20px;">Redes Sociais&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</h3>
      <a href="https://www.linkedin.com/in/daniellygoncalvess/" style="color: #fff; text-decoration: none; margin-right: 20px;"><i class="fab fa-linkedin"></i></a>
      <a href="https://github.com/gsdanielly" style="color: #fff; text-decoration: none; margin-right: 20px;"><i class="fab fa-github"></i></a>
      <a href="https://twitter.com/gsdanielly?t=Py27ULtdjZfDSbJmwv1gVQ&s=09" style="color: #fff; text-decoration: none; margin-right: 10px;"><i class="fab fa-twitter"></i></a>
      <a href="https://www.instagram.com/gsdanielly/" style="color: #fff; text-decoration: none; margin-right: 50px;"><i class="fab fa-instagram"></i></a>
    </div>
  </div>

   <!-- Campo de cadastro de usuário -->
   <div id="cadastro" style="background-color: #f5f0e1; padding: 20px; border-radius: 10px; margin-top: 20px;">
    <h4 style="color: #2b2927;">Cadastre-se para receber nossas novidades:</h4>
    <form>
      <div>
        <label for="nome"style="color: #000; margin-top: 10px;">&nbsp&nbsp&nbspNome:&nbsp</label>
        <input type="text" id="nome" name="nome" placeholder="Seu nome completo" style="width: 300px; " required>
      </div>
      <div>
        <label for="email" style="color: #2b2927;">&nbsp&nbsp&nbspE-mail:&nbsp</label>
        <input type="email" id="email" name="email" placeholder="seuemail@example.com" style="width: 300px; margin-top: 5px;" required>
      </div>
      <div>
        <label for="telefone" style="color: #2b2927;">Telefone:&nbsp</label>
        <input type="tel" id="telefone" name="telefone" placeholder="(11) 98765-4321" style="width: 300px; margin-top: 5px;" required>
      </div>
      <div>
        <label for="cpf" style="color: #2b2927;">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspCPF:&nbsp</label>
        <input type="text" id="cpf" name="cpf" placeholder="000.000.000-00" style="width: 300px; margin-top: 5px;" required>
      </div>
      <button type="submit" style="background-color: #674c38; color: #fff; padding: 10px 20px; margin-top: 20px; border: none; border-radius: 5px; cursor: pointer;">Cadastrar</button>
    </form> 
  </div>
</footer>

<!-- Balão Whattsapp -->
<div class="container">
  <!-- Conteúdo da página -->
</div>

<!-- Balão de WhatsApp -->
<div class="balao-whatsapp">
  <p class="mb-0">Fale com um projetista! :)</p>
  <a href="https://api.whatsapp.com/send?phone=27998139695" target="_blank">
    <i class="fab fa-whatsapp"></i> Nosso WhatsApp
  </a>
</div>

<p style="margin-left: 400px; color: #fff; margin-top: 10px;"> Desenvolvido por: Danielly Gonçalves Santos / Todos os direitos reservados</p>

</body>
</html>
