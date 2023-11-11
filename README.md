# Postulaciones-SpaceMc
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Postulación</title>
</head>
<body>
    <h1>Formulario de Postulación</h1
function enviarPostulacion() {
    // Obtener datos del formulario
    var nombre = document.getElementById("nombre").value;
    var email = document.getElementById("email").value;

    // Validar datos (puedes agregar más validaciones según tus necesidades)

    // Crear un objeto con los datos del formulario
    var datosPostulacion = {
        nombre: nombre,
        email: email
    };

    // Enviar los datos a tu servidor o a un servicio de backend (puedes usar AJAX o Fetch API)
    // Aquí se simula un envío con un log en la consola
    console.log("Datos de postulación:", datosPostulacion);

    // Puedes realizar una solicitud HTTP (por ejemplo, con fetch) para enviar los datos al servidor
    // fetch('URL_DEL_BACKEND', {
    //     method: 'POST',
    //     headers: {
    //         'Content-Type': 'application/json',
    //     },
    //     body: JSON.stringify(datosPostulacion),
    // })
    // .then(response => response.json())
    // .then(data => {
    //     console.log('Respuesta del servidor:', data);
    // })
    // .catch(error => {
    //     console.error('Error al enviar la postulación:', error);
    // });
}
