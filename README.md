# AlejandroOjeda.github.io
Alejandro Ojeda Tarín Web

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Silas - Portafolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      line-height: 1.6;
      background: #f4f4f4;
      color: #333;
    }

    header {
      background: #222;
      color: #fff;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 2rem;
      color: #222;
    }

    .projects, .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .project-card, .skill-card {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      flex: 1 1 250px;
      max-width: 300px;
    }

    .project-card h3 {
      margin-top: 0;
    }

    .contact a {
      color: #222;
      text-decoration: none;
      margin: 0 10px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #222;
      color: #fff;
    }
  </style>
</head>
<body>

  <header>
    <h1>Silas</h1>
    <p>Programador Junior | Apasionado por Python y desarrollo web</p>
  </header>

  <section id="about">
    <h2>Sobre mí</h2>
    <p>Soy un programador junior con experiencia en Python, HTML, CSS y JavaScript. Me encanta construir soluciones limpias y eficientes, aprender nuevas tecnologías y mejorar constantemente.</p>
  </section>

  <section id="projects">
    <h2>Proyectos</h2>
    <div class="projects">
      <div class="project-card">
        <h3>Proyecto 1</h3>
        <p>Descripción breve del proyecto y tecnologías usadas.</p>
        <a href="#">Ver repositorio</a>
      </div>
      <div class="project-card">
        <h3>Proyecto 2</h3>
        <p>Descripción breve del proyecto y tecnologías usadas.</p>
        <a href="#">Ver repositorio</a>
      </div>
    </div>
  </section>

  <section id="skills">
    <h2>Habilidades</h2>
    <div class="skills">
      <div class="skill-card">Python</div>
      <div class="skill-card">HTML/CSS</div>
      <div class="skill-card">JavaScript</div>
      <div class="skill-card">Git/GitHub</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contacto</h2>
    <p class="contact">
      <a href="mailto:tuemail@ejemplo.com">Email</a> |
      <a href="https://github.com/tuusuario" target="_blank">GitHub</a> |
      <a href="https://www.linkedin.com/in/tuusuario" target="_blank">LinkedIn</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 Silas. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
