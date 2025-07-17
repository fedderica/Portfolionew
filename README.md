<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Federica Bartoli</title>
  <style>
    /* Reset básico */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #fff;
      color: #222;
    }
    /* Navbar */
    nav {
      background: #f8f8f8;
      border-bottom: 1px solid #ddd;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    .nav-container {
      max-width: 960px;
      margin: 0 auto;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0.75rem 1rem;
    }
    .nav-title {
      font-weight: 700;
      font-size: 1.8rem;
      color: #222;
      flex: 1;
      text-align: center;
    }
    ul.nav-links {
      list-style: none;
      padding: 0;
      margin: 0;
      display: flex;
      gap: 1rem;
      flex: 2;
      justify-content: flex-end;
      flex-wrap: wrap;
    }
    ul.nav-links li {
    }
    ul.nav-links li a {
      text-decoration: none;
      color: #222;
      font-weight: 600;
      font-size: 1rem;
      padding: 0.3rem 0.5rem;
      border-radius: 4px;
      transition: background-color 0.3s ease;
      display: inline-block;
    }
    ul.nav-links li a:hover,
    ul.nav-links li a:focus {
      background-color: #007bff;
      color: white;
    }

    /* Main contenido */
    main {
      max-width: 900px;
      margin: 3rem auto 5rem auto;
      padding: 0 1rem;
      text-align: center;
    }
    main h1 {
      font-weight: 800;
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }
    main p.subtitle {
      font-size: 1.2rem;
      font-weight: 400;
      color: #555;
      margin-bottom: 2rem;
    }

    /* Secciones ejemplo */
    section {
      margin-bottom: 4rem;
      text-align: left;
    }
    section h2 {
      font-weight: 700;
      font-size: 2rem;
      margin-bottom: 1rem;
      border-bottom: 2px solid #007bff;
      padding-bottom: 0.3rem;
      color: #222;
    }
    section p {
      font-size: 1.1rem;
      line-height: 1.6;
      color: #444;
    }

    /* Responsive */
    @media (max-width: 600px) {
      .nav-container {
        flex-wrap: wrap;
      }
      .nav-title {
        order: 2;
        flex-basis: 100%;
        margin-top: 0.5rem;
        text-align: center;
      }
      ul.nav-links {
        flex-basis: 100%;
        justify-content: center;
        order: 3;
        margin-top: 0.5rem;
        gap: 0.75rem;
      }
      main h1 {
        font-size: 2.2rem;
      }
      section h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>
  <nav>
    <div class="nav-container">
      <div class="nav-title">Federica Bartoli</div>
      <ul class="nav-links">
        <li><a href="#inicio">Inicio</a></li>
        <li><a href="#sobre-mi">Sobre mí</a></li>
        <li><a href="#proyectos">Proyectos</a></li>
        <li><a href="#habilidades">Habilidades</a></li>
        <li><a href="#contacto">Contacto</a></li>
        <li><a href="#blog">Blog</a></li>
      </ul>
    </div>
  </nav>

  <main>
    <section id="inicio">
      <h1>Hola, soy Federica Bartoli</h1>
      <p class="subtitle">Desarrolladora Full Stack & Apasionada por la Tecnología</p>
    </section>

    <section id="sobre-mi">
      <h2>Sobre mí</h2>
      <p>
        Soy una profesional con experiencia en desarrollo web y ciberseguridad. Me apasiona crear soluciones tecnológicas eficientes y elegantes. Siempre busco aprender y crecer en mi carrera.
      </p>
    </section>

    <section id="proyectos">
      <h2>Proyectos</h2>
      <p>Algunos proyectos destacados incluyen aplicaciones web, portafolios personales y blogs tecnológicos.</p>
    </section>

    <section id="habilidades">
      <h2>Habilidades</h2>
      <p>JavaScript, React, Node.js, SQL, HTML5, CSS3, Ciberseguridad, Git, Docker, entre otras.</p>
    </section>

    <section id="contacto">
      <h2>Contacto</h2>
      <p>Email: <a href="mailto:federica@example.com">federica@example.com</a></p>
      <p>LinkedIn: <a href="https://linkedin.com/in/federicabartoli" target="_blank" rel="noopener noreferrer">linkedin.com/in/federicabartoli</a></p>
      <p>GitHub: <a href="https://github.com/tuusuario" target="_blank" rel="noopener noreferrer">github.com/tuusuario</a></p>
    </section>

    <section id="blog">
      <h2>Blog</h2>
      <p>Próximamente compartiré artículos y tutoriales relacionados con desarrollo y tecnología.</p>
    </section>
  </main>
</body>
</html>
