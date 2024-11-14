<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Servicios Fotográficos y Alquiler de Togas</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Encabezado -->
    <header>
        <h1>Servicios Fotográficos y Alquiler de Togas</h1>
        <p id="datetime"></p>
    </header>

    <!-- Sección de servicios -->
    <section id="services">
        <h2>Nuestros Servicios</h2>
        <div class="service-card">
            <h3>Fotografía Profesional</h3>
            <p>Captura momentos inolvidables con nuestra fotografía profesional. Sesiones en estudio o exteriores.</p>
        </div>
        <div class="service-card">
            <h3>Alquiler de Togas</h3>
            <p>Ofrecemos togas de alta calidad para graduaciones y ceremonias. Disponibilidad en varias tallas y estilos.</p>
        </div>
    </section>

    <!-- Sección de contacto -->
    <section id="contact">
        <h2>Contáctanos</h2>
        <p>¿Tienes alguna pregunta? ¡Envíanos un mensaje y estaremos encantados de ayudarte!</p>
        <form>
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Servicios Fotográficos y Alquiler de Togas</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
