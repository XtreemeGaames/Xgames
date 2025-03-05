# Xgames
Evento social y deportivo, competencia para superar tus limites
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Xtreme Games</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Xtreme Games</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#inscripcion">Inscripción</a></li>
                <li><a href="#contacto">Contacto & Tienda</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="inicio">
        <h2>¿Quiénes Somos?</h2>
        <p>Descripción del evento y su historia.</p>
        <h3>Próximos Eventos</h3>
        <p>Detalles de los próximos eventos y fechas importantes.</p>
        <h3>Testimonios</h3>
        <p>Declaraciones de participantes anteriores.</p>
        <h3>Galería</h3>
        <p>Fotos de eventos anteriores.</p>
        <h3>Patrocinadores</h3>
        <p>Logos y enlaces de empresas que apoyan el evento.</p>
    </section>
    
    <section id="inscripcion">
        <h2>Inscríbete en la Próxima Competición</h2>
        <p>Descarga el formulario y completa tu inscripción.</p>
        <a href="formulario.pdf" download>Descargar Formulario</a>
        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>
            <button type="submit">Enviar</button>
        </form>
    </section>
    
    <section id="contacto">
        <h2>Contacto & Tienda</h2>
        <p>Comunícate con nosotros para entrenamientos personalizados o compra de indumentaria.</p>
        <form>
            <label for="mensaje">Tu mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2025 Xtreme Games. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
