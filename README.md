# Tienda-de-Lucifer-online-
Vender productos online 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tienda de Servicios</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Tienda de Servicios</h1>
    <nav>
      <a href="#servicios">Servicios</a>
      <a href="#galeria">Galería</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section id="servicios">
    <h2>Servicios</h2>
    <div class="servicio">
      <img src="https://via.placeholder.com/200" alt="Servicio 1">
      <h3>Servicio A</h3>
      <p>Descripción del servicio A.</p>
    </div>
    <div class="servicio">
      <img src="https://via.placeholder.com/200" alt="Servicio 2">
      <h3>Servicio B</h3>
      <p>Descripción del servicio B.</p>
    </div>
  </section>

  <section id="galeria">
    <h2>Galería</h2>
    <div class="galeria">
      <img src="https://via.placeholder.com/150" alt="Imagen 1">
      <img src="https://via.placeholder.com/150" alt="Imagen 2">
      <img src="https://via.placeholder.com/150" alt="Imagen 3">
    </div>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <form>
      <label>Nombre:<br><input type="text" name="nombre"></label><br>
      <label>Email:<br><input type="email" name="email"></label><br>
      <label>Mensaje:<br><textarea name="mensaje"></textarea></label><br>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Tienda de Servicios - Todos los derechos reservados</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #2c3e50;
  color: white;
  padding: 1em;
  text-align: center;
}

nav a {
  margin: 0 1em;
  color: white;
  text-decoration: none;
}

section {
  padding: 2em;
}

.servicio {
  border: 1px solid #ccc;
  padding: 1em;
  margin-bottom: 1em;
  text-align: center;
}

.servicio img {
  width: 200px;
  height: auto;
}

.galeria img {
  margin: 10px;
  width: 150px;
  height: auto;
}

form {
  max-width: 400px;
  margin: auto;
}

input, textarea {
  width: 100%;
  padding: 0.5em;
  margin-bottom: 1em;
}

footer {
  text-align: center;
  background-color: #f1f1f1;
  padding: 1em;
  margin-top: 2em;
}
