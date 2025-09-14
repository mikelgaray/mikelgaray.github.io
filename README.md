<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portafolio - Mikel Aritz Garay Pantoja</title>
    <!-- <link rel="stylesheet" href="css/style.css" />-->
    <link rel="icon" type="image/png" href="img/logo.png" />
    <style>
      /*General*/
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      body {
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
        background-color: #f2f2f2;
        color: #333;
        line-height: 1.6;
      }
      h2 {
        color: #2c3e50;
        margin-bottom: 1rem;
        border-bottom: 2px solid #3498db;
        display: inline-block;
        padding-bottom: 0.3rem;
      }
      ul {
        list-style: none;
        padding-left: 0;
      }

      ul li {
        background: #ecf0f1;
        margin: 0.5rem 0;
        padding: 0.5rem;
        border-left: 4px solid #3498db;
        border-radius: 4px;
      }
      section {
        padding: 2rem;
        max-width: 900px;
        margin: 0 auto;
        background-color: white;
        margin-bottom: 2rem;
        border-radius: 8px;
        box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
      }
      /*Header*/
      header {
        background-color: #2c3e50;
        color: white;
        text-align: center;
        padding: 2rem 1rem;
      }

      header img {
        width: 150px;
        height: 150px;
        border-radius: 50%;
        object-fit: cover;
        margin-bottom: 1rem;
        border: 4px solid #3498db;
      }

      header h1 {
        font-size: 2.5rem;
        margin-bottom: 0.5rem;
      }

      header p {
        font-size: 1.2rem;
        margin-bottom: 1rem;
      }

      nav a {
        color: #ecf0f1;
        margin: 0 10px;
        text-decoration: none;
        font-weight: bold;
        transition: color 0.3s ease;
      }

      nav a:hover {
        color: #3498db;
      }

      /*Proyectos*/
      .proyecto {
        margin-bottom: 1.5rem;
        padding: 1rem;
        border: 1px solid #ddd;
        border-radius: 6px;
        background-color: #fafafa;
      }

      .proyecto h3 {
        color: #2980b9;
        margin-bottom: 0.5rem;
      }

      .proyecto a {
        color: #3498db;
        text-decoration: none;
        font-weight: bold;
      }

      .proyecto a:hover {
        text-decoration: underline;
      }

      /* Video centrado */
      .video-container {
        display: flex;
        justify-content: center;
        margin-top: 1rem;
      }

      .video-container video {
        width: 100%;
        max-width: 500px;
        border-radius: 8px;
        box-shadow: 0 2px 6px rgba(0, 0, 0, 0.15);
      }

      /*Footer*/
      footer {
        background-color: #2c3e50;
        color: white;
        padding: 40px 20px 20px 20px;
        font-size: 0.95em;
      }
      .footer-container {
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        gap: 20px;
      }
      .footer-section {
        flex: 1;
        min-width: 250px;
      }
      .footer-section h3 {
        margin-bottom: 15px;
        font-size: 1.2em;
        border-bottom: 2px solid #3498db;
        padding-bottom: 5px;
        color: #ffffff;
      }
      .footer-section ul {
        list-style: none;
        padding: 0;
      }
      .footer-section ul li {
        margin-bottom: 10px;
        line-height: 1.4;
        color: #000000;
      }
      .footer-section strong {
        color: #000000;
      }
      .footer-section a {
        color: #000000;
        font-weight: bold;
        text-decoration: none;
        transition: color 0.3s ease;
      }
      .footer-section a:hover {
        color: #3498db;
        text-decoration: none;
      }
      .footer-bottom {
        text-align: center;
        margin-top: 30px;
        font-size: 0.85em;
        color: #aaa;
      }
    </style>
  </head>
  <body>
    <header>
      <img src="img/perfil.jpg" alt="Foto de Mikel Aritz Garay Pantoja" />
      <h1>Mikel Aritz Garay Pantoja</h1>
      <p>Desarrollador de Aplicaciones Multiplataforma</p>
      <nav>
        <a href="#sobre-mi">Sobre mí</a>
        <a href="#proyectos">Proyectos</a>
        <a href="#habilidades">Habilidades</a>
        <a href="#footer">Contacto</a>
      </nav>
    </header>

    <section id="sobre-mi">
      <h2>Sobre mí</h2>
      <p>
        Soy estudiante de DAM con pasión por el desarrollo móvil y de
        escritorio...
      </p>
    </section>

    <section id="proyectos">
      <h2>Proyectos</h2>
      <div class="proyecto">
        <h3>Desarrollo Web Empresa</h3>
        <p>
          Una web dinamica en la cual me dieron una web ya echa por wordpress,
          yo tuve que editarla practicamente desde cero haciendo todo lo que se
          ve en el video.
        </p>
        <p><strong>Tecnologías:</strong> Html, Css, JavaScript, php, MySQL</p>
        <div class="video-container">
          <video controls>
            <source src="img/Axionpadel.mp4" type="video/mp4" />
            Tu navegador no soporta la reproducción de video.
          </video>
        </div>
      </div>

      <div class="proyecto">
        <h3>Aplicacion Crud</h3>
        <p>
          Aplicación multiplataforma en Java con base de datos MySQL, en este
          proyecto sobre todo estuve trabajando la base de datos y lo que
          implicaba la base de datos, tambien trabaje en la parte de Java de la
          aplicacion.
        </p>
        <p><strong>Tecnologías:</strong> Java, MySQL</p>
        <div class="video-container">
          <video controls>
            <source src="img/Program.mp4" type="video/mp4" />
            Tu navegador no soporta la reproducción de video.
          </video>
        </div>
      </div>

      <div class="proyecto">
        <h3>Desarrollo web Clase</h3>
        <p>
          Web dinamica conectada a una base de datos, en esta web sobre todo
          desarrolle Html, Css y Xml para la base de datos.
        </p>
        <p>
          <strong>Tecnologías:</strong> Html, Css, JavaScript, Xml, php, Xquery
        </p>
        <div class="video-container">
          <video controls>
            <source src="img/Gimnasio.mp4" type="video/mp4" />
            Tu navegador no soporta la reproducción de video.
          </video>
        </div>
      </div>
    </section>

    <section id="habilidades">
      <h2>Habilidades Técnicas</h2>
      <ul>
        <li>Java</li>
        <li>Desarrollo Web</li>
        <li>MySQL</li>
        <li>Git</li>
      </ul>
    </section>

    <footer>
      <div class="footer-container" id="footer">
        <div class="footer-section">
          <h3>Información de Contacto</h3>
          <ul>
            <li>
              <strong>Dirección:</strong> Avenida Sabino Arana Etorbidea 18
              5a-48940-Leioa (Vizcaya)
            </li>
            <li><strong>Teléfono:</strong> +34 644 185 339</li>
            <li><strong>Email:</strong> garaymikelaritz@gmail.com</li>
          </ul>
        </div>

        <div class="footer-section">
          <h3>Enlaces Útiles</h3>
          <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#sobre-mi">Sobre mí</a></li>
            <li><a href="#proyectos">Proyectos</a></li>
          </ul>
        </div>

        <div class="footer-section">
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d5805.486144311176!2d-2.993751623333163!3d43.3196376101284!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd4e5a4f8981862d%3A0xa6a2cca56679e4eb!2sAv.%20Sabino%20Arana%20Etorbidea%2C%2018%2C%2048940%20Leioa%2C%20Vizcaya!5e0!3m2!1ses!2ses!4v1757756923823!5m2!1ses!2ses"
            width="100%"
            height="200"
            style="border: 0"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
          >
          </iframe>
        </div>
      </div>

      <div class="footer-bottom">
        <p>© 2025 Mikel Aritz Garay</p>
      </div>
    </footer>
  </body>
</html>
