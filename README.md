<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Postulación</title>
</head>
<body>
    <h1>Formulario de Postulación</h1>
    <form id="postulacionForm">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>
        <br>
        <label for="email">Correo Electrónico:</label>
        <input type="email" id="email" name="email" required>
        <br>
        <button type="button" onclick="enviarPostulacion()">Enviar Postulación</button>
    </form>

    <script src="postulacion.js"></script>
</body>
</html>
