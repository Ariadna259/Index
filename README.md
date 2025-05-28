<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Renueva Tu Forma de Estudio</title>
  <style>
    /* Reset básico */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f5f7fa;
      color: #333;
      line-height: 1.6;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    /* Navegación */
    nav {
      background: linear-gradient(90deg, #1a1f36, #3a72b9);
      padding: 15px 0;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 30px;
    }

    nav ul li a {
      color: #f0f0f0;
      font-weight: 600;
      font-size: 1.1rem;
      text-decoration: none;
      padding: 8px 16px;
      border-radius: 8px;
      transition: background-color 0.3s ease, color 0.3s ease;
    }

    nav ul li a:hover,
    nav ul li a:focus {
      background-color: #f0f0f0;
      color: #1a1f36;
      outline: none;
    }

    header {
      text-align: center;
      margin: 3rem 1rem 2rem;
    }

    header h2 {
      font-size: 2.8rem;
      color: #222;
      letter-spacing: 2px;
      text-transform: uppercase;
      text-shadow: 1px 1px 3px #3a72b9;
    }

    main {
      max-width: 900px;
      margin: 0 auto 3rem;
      padding: 0 1rem;
      flex-grow: 1;
    }

    section {
      margin-bottom: 3rem;
      background: #fff;
      padding: 2rem;
      border-radius: 15px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      transition: box-shadow 0.3s ease;
    }

    section:hover {
      box-shadow: 0 6px 20px rgba(0,0,0,0.1);
    }

    section h3 {
      font-size: 2rem;
      color: #3a72b9;
      margin-bottom: 1rem;
      border-bottom: 3px solid #1a1f36;
      display: inline-block;
      padding-bottom: 0.3rem;
    }

    p {
      font-size: 1.15rem;
      margin-bottom: 1rem;
      color: #444;
    }

    ul {
      list-style: inside disc;
      color: #555;
      font-size: 1.1rem;
      padding-left: 0;
      margin-left: 1rem;
    }

    ul li {
      margin-bottom: 0.6rem;
    }

    a[href^="tel:"],
    a[href^="mailto:"] {
      color: #3a72b9;
      font-weight: 600;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    a[href^="tel:"]:hover,
    a[href^="mailto:"]:hover {
      color: #1a1f36;
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #eaeaea;
      font-size: 0.9rem;
      color: #666;
      border-top: 1px solid #ccc;
      margin-top: auto;
    }
  </style>
</head>
<body>

  <nav>
    <ul>
      <li><a href="#inicio">Inicio</a></li>
      <li><a href="#sobre-nosotros">Sobre Nosotros</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>

  <header>
    <h2>RENUEVA TU FORMA DE ESTUDIO</h2>
  </header>

  <main>
    <section id="inicio" tabindex="0">
      <p>
        En Renueva Tu Forma de Estudio te apoyamos con tus tareas, proyectos y estudios a través de materiales personalizados y asesorías en distintas materias para que mejores tu aprendizaje.
      </p>
    </section>

    <section id="sobre-nosotros" tabindex="0">
      <h3>Sobre Nosotros</h3>
      <p>
        Somos un equipo apasionado por la educación y el aprendizaje. Nuestro objetivo es apoyarte en tu desarrollo académico ofreciéndote herramientas claras, eficientes y adaptadas a tus necesidades.
      </p>
      <p>¿Qué ofrecemos?</p>
      <ul>
        <li>Apoyo en la redacción de: resúmenes, esquemas, análisis y más.</li>
        <li>Apoyo en la redacción de textos: ensayos, presentaciones y más.</li>
        <li>Asesorías individuales en materias como Matemáticas y otras asignaturas clave.</li>
        <li>Ayuda para organizar tus ideas y mejorar tu forma de estudiar.</li>
      </ul>
    </section>

    <section id="contacto" tabindex="0">
      <h3>Contacto</h3>
      <p>Teléfono: <a href="tel:5550745590">555 074 5590</a></p>
      <p>Teléfono: <a href="tel:7204776717">720 477 6717</a></p>
      <p>Correo: <a href="mailto:areli.ahc@gmail.com">areli.ahc@gmail.com</a></p>
    </section>
  </main>

  <footer>
    &copy; 2025 Renueva Tu Forma de Estudio. Todos los derechos reservados.
  </footer>

</body>
</html>
