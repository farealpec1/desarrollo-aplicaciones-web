# desarrollo-aplicaciones-web
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Arquitectura Cliente/Servidor en desarrollo web y DCU</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f9;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #2c3e50;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #34495e;
      padding: 10px;
      display: flex;
      justify-content: center;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 20px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #2c3e50;
    }
    footer {
      background: #2c3e50;
      color: #fff;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }
    .referencias li {
      margin-bottom: 10px;
    }
    .resaltar {
      background: #ecf0f1;
      padding: 10px;
      border-left: 4px solid #2980b9;
    }
  </style>
</head>
<body>
  <header>
    <h1>Arquitectura Cliente/Servidor y Diseño Centrado en el Usuario</h1>
  </header>

  <nav>
    <a href="#cliente-servidor">Cliente/Servidor</a>
    <a href="#dcu">Diseño Centrado en el Usuario</a>
    <a href="#investigacion">Investigación en el Entorno</a>
    <a href="#referencias">Referencias</a>
  </nav>

  <section id="cliente-servidor">
    <h2>Arquitectura Cliente/Servidor en Desarrollo Web</h2>
    <p>
      La arquitectura cliente/servidor es esencial en el desarrollo web, porque facilita la comunicación entre los usuarios y los sistemas. En este modelo, el <strong>cliente</strong> (como un navegador) solicita información, y el <strong>servidor</strong> la procesa, consulta bases de datos o servicios y envía la respuesta. 
    </p>
    <p class="resaltar">
      Este enfoque permite escalar sistemas, gestionar mejor los recursos y ofrecer a los usuarios una experiencia interactiva y ágil al acceder a la información.
    </p>
  </section>

  <section id="dcu">
    <h2>Diseño Centrado en el Usuario (DCU)</h2>
    <p>
      El Diseño Centrado en el Usuario es un enfoque que pone las necesidades, objetivos y características de los usuarios en el centro de cada etapa del desarrollo de un producto digital. Busca entender cómo las personas usan las interfaces para asegurar que sean accesibles, fáciles de usar y satisfactorias.
    </p>
    <p>
      Implementar el DCU ayuda a diseñar sistemas más intuitivos, facilita el aprendizaje de los usuarios y garantiza que la tecnología entregue un valor real a quienes la usan.
    </p>
  </section>

  <section id="investigacion">
    <h2>Importancia de la Investigación en el Entorno</h2>
    <p>
      La investigación del entorno para el análisis de requisitos es fundamental, pues ayuda a detectar las necesidades reales de los usuarios y el contexto donde se implementará el sistema. Este estudio consiste en recopilar información sobre los procesos, los actores involucrados, las limitaciones y las oportunidades existentes.
    </p>
    <p class="resaltar">
      Un análisis de requisitos bien fundamentado en la investigación previene errores costosos en etapas posteriores del desarrollo y garantiza que el producto final cumpla con los objetivos del negocio y las expectativas de los usuarios.
    </p>
  </section>

  <section id="referencias">
    <h2>Referencias</h2>
    <ul class="referencias">
      <li>Blog ingranetnetborking. (2019). Modelo cliente servidor. https://blog.infranetworking.com/modelo-cliente-servidor/  </li>
      <li>Blog La arquitectura Cliente-Servidor. (2021). https://reactiveprogramming.io/blog/es/estilosarquitectonicos/cliente-servidor </li>
      <li>Granollers, T. (2012).  Diseño de sistemas interactivos centrados en el usuario . Editorial UOC. (Pág. 23 a 49) https://elibro-net.bibliotecavirtual.unad.edu.co/es/ereader/unad/56326?page=24</li>
    </ul>
  </section>

  <footer>
    <p>© 2025 - Página educativa sobre Cliente/Servidor, DCU y Análisis de Requisitos</p>
  </footer>

  <script>
    // Pequeño script para destacar en navegación
    const links = document.querySelectorAll('nav a');
    links.forEach(link => {
      link.addEventListener('click', () => {
        links.forEach(l => l.style.textDecoration = 'none');
        link.style.textDecoration = 'underline';
      });
    });
  </script>
</body>
</html>
