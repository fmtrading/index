# index
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0, maximum-scale=1.0"
    />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Reservas MI NEGOCIO</title>
    <link rel="stylesheet" href="css/estilos.css" />
  </head>
  <body>
    <form action="" class="formulario">
      <img src="logo.jpg" class="imgLogo" />

      <h1 class="formulario__titulo">MI NEGOCIO</h1>
      <h3 class="formulario__subtitulo">Reservas</h3>
      <p class="formulario__parrafo">
        Llena este pequeño formulario para agendar tu cita en MI NEGOCIO.
      </p>

      <label for="cliente" class="formulario__label">¿Cuál es tu nombre?</label>
      <input
        id="cliente"
        type="text"
        class="formulario__input"
        placeholder="Indica cuál es tu nombre completo"
      />

      <label for="fecha" class="formulario__label"
        >Indica la fecha de tu reserva</label
      >
      <input
        id="fecha"
        type="date"
        class="formulario__input"
        pattern="[0-9]{4}-[0-9]{2}-[0-9]{2}"
      />

      <label for="hora" class="formulario__label"
        >Indica la hora de tu reserva</label
      >
      <input id="hora" type="time" class="formulario__input" />

      <label for="empleado" class="formulario__label"
        >EMPLEADO de preferencia</label
      >
      <select id="empleado" name="listaempleados" class="formulario__input">
        <option>EMPLEADO 1</option>
        <option>EMPLEADO 2</option>
      </select>

      <label for="servicio" class="formulario__label"
        >¿Cuál es el servicio que se desea realizar?</label
      >
      <select id="servicio" name="listaservicios" class="formulario__input">
        <option>SERVICIO 1 - $VALOR</option>
        <option>SERVICIO 2 - $VALOR</option>
        <option>SERVICIO 3 - $VALOR</option>
        <option>SERVICIO 4 - $VALOR</option>
        <option>SERVICIO 5 - $VALOR</option>
      </select>

      <div id="respuesta"></div>

      <button id="submit" class="formulario__submit">Enviar a WhatsApp</button>
    </form>
    <script src="js/form.js"></script>
  </body>
</html>
