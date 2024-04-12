# primeira-pagina-rodando-stylle-css
-----------------------------------------------
no html
<!DOCTYPE html>
<html>
<head>
    <title>Minha Página stylles </title>
    <link rel="stylesheet" href="./stylle.css">
    <style>
        /* Seus estilos CSS aqui */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
        }
        h1 {
            color: blue;
        }
    </style>
</head>
<body>
    <h1>style="color: blue;">Meu Título</h1>
    <p> style="font-family: Arial, sans-serif;">Este é um parágrafo com estilos em linha.</p>
    <div class="container">
       <h2>Plano de Fundo com Duas Cores</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam euismod, dolor at vestibulum ultrices, nisi libero ultrices justo, nec fermentum lorem risus quis odio.</p>
        <p>estou feliz pois é a primeira vez que estou conseguindo fazer funionar meu stylle css, 
            está aparecendo as duas cores na pagina
        </p>

    </div>
    <!--estou feliz pois é a primeira vez que estou conseguindo fazer funionar meu stylle css, 
            está aparecendo as duas cores na pagina-->
</body>
</html>
---------------------------------------
no css

/* styles.css */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}
h1 {
    color: blue;
}
.container {
    width: 100%;
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background: linear-gradient(to bottom, #ff0000 50%, #0000ff 50%); /* Define um gradiente linear com duas cores */
    color: #fff; /* Define a cor do texto para branco para melhor contraste */
  }
  
  h2 {
    text-align: center;
  }
