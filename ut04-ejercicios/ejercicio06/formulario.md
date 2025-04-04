<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Formulario de registro</title>
</head>
<body>
  <h1>Formulario de registro</h1>
  <form action="#" method="post">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre"><br><br>

    <label for="apellidos">Apellidos:</label>
    <input type="text" id="apellidos" name="apellidos"><br><br>

    <label>Sexo:</label>
    <input type="radio" id="hombre" name="sexo" value="hombre">
    <label for="hombre">hombre</label>
    <input type="radio" id="mujer" name="sexo" value="mujer">
    <label for="mujer">mujer</label><br><br>

    <label for="correo">Correo:</label>
    <input type="email" id="correo" name="correo"><br><br>

    <input type="checkbox" id="info" name="info" checked>
    <label for="info">Deseo recibir información sobre novedades y ofertas</label><br><br>

    <input type="checkbox" id="condiciones" name="condiciones">
    <label for="condiciones">Declaro haber leído y aceptar las condiciones generales del programa y la normativa sobre protección de datos</label><br><br>

    <input type="submit" value="Enviar">
  </form>
</body>
</html>