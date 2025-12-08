<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mi Proyecto - Página Web Moderna</title>
    <style>
        :root {
            --color-primario: #0d6efd;
            --color-secundario: #6c757d;
            --color-fondo: #f8f9fa;
            --color-texto: #212529;
            --color-blanco: #ffffff;
        }

        body {
            margin: 0;
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
            background: var(--color-fondo);
            color: var(--color-texto);
            line-height: 1.6;
        }

        header {
            background: var(--color-primario);
            color: var(--color-blanco);
            padding: 40px 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
            letter-spacing: 1px;
        }

        nav {
            background: var(--color-blanco);
            padding: 10px 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        nav ul {
            list-style: none;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline-block;
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: var(--color-texto);
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: var(--color-primario);
        }

        .hero {
            background: linear-gradient(to right, #0d6efdcc, #0d6efd66), url('https://picsum.photos/1200/500');
            background-size: cover;
            background-position: center;
            color: var(--color-blanco);
            padding: 100px 20px;
            text-align: center;
        }

        .hero h2 {
            font-size: 2.3rem;
            margin-bottom: 10px;
        }

        .hero p {
            max-width: 700px;
            margin: auto;
            font-size: 1.2rem;
        }

        .contenedor {
            max-width: 1100px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .seccion {
            margin-bottom: 60px;
        }

        .seccion h3 {
            font-size: 1.8rem;
            margin-bottom: 15px;
            border-left: 5px solid var(--color-primario);
            padding-left: 10px;
        }

        .card {
            background: var(--color-blanco);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }

        footer {
            background: var(--color-secundario);
            color: var(--color-blanco);
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sector Agrícola - Innovación y Desarrollo</h1>
        <p>Soluciones modernas y sostenibles para el sector agrícola, con enfoque en productividad, tecnología y eficiencia.</p>
    </header>

    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#servicios">Servicios</a></li>
            <li><a href="#nosotros">Nosotros</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>

    <section class="hero" id="inicio">
        <h2>Agricultura Moderna y Sostenible</h2>
        <p>Explora información, servicios y soluciones enfocadas en el crecimiento y optimización del sector agrícola.</p>
    </section>

    <div class="contenedor">
        <section class="seccion" id="servicios">
            <h3>Servicios</h3>
            <div class="card">
                <h4>Asesoría Agrícola Integral</h4>
                <p>Ofrecemos asesoramiento profesional en manejo de cultivos, planificación agrícola y mejora de la productividad.</p>
            </div>
            <div class="card">
                <h4>Tecnología y Automatización Rural</h4>
                <p>Implementación de herramientas tecnológicas para el monitoreo, control y toma de decisiones estratégicas en el campo.</p>
            </div>
        </section>

        <section class="seccion" id="nosotros">
            <h3>Sobre Nosotros</h3>
            <div class="card">
                <p>Somos un equipo comprometido con la innovación agrícola, impulsando prácticas sostenibles y soluciones que mejoran la rentabilidad y eficiencia del productor.</p>
            </div>
        </section>

        <section class="seccion" id="contacto">
            <h3>Contacto</h3>
            <div class="card">
                <p>Correo: ejemplo@correo.com</p>
                <p>Teléfono: +591 70000000</p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 - Todos los derechos reservados</p>
    </footer>
</body>
</html>
