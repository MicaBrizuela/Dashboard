<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard</title>
    <link href="styleI.css" rel="stylesheet" type="text/css" />
</head>
<body>
  <main class"contenedor">
    <class="login">
      <div class="log1">
            <div class="unq">
              <img src="./img/unquii.jpg" alt="logo">
            </div>
            <div class="titulo">
                <h1>Dashboard</h1>
            </div>
            <div class="welcome">
              <span>Bienvenido</span>
            </div>
            <form class="entrada" name="formulario" method="post" action="bd/conection.php">
                <label>Nombre de usuario</label>
                <input type="text" name="nom" >
            </form>
            <form class="entrada">
                <label>Contraseña</label> <br>
                <input type="text" name="psw" >
            </form>
            <div class="recuperar">
              <a href="/media/profesor/TIARA/dashboard/recuperar.html">¿Has olvidado tu contraseña?</a>
            </div>
            <a href="/pagina.html">
                <button onclick="pagina.html">INGRESAR</button>
            </a>
    </class>
    <script src="./js/index.js"></script>
  </main>
</body>

<footer></footer>
</html>

