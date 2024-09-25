<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Parking seguro y cómodo para tu coche. Disponibilidad 24/7, tarifas competitivas.">
    <title>Parking Seguros - Inicio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Parking Seguros</div>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#servicios">Servicios</a></li>
                <li><a href="#precios">Precios</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio" class="hero">
        <h1>Bienvenido a Parking Seguros</h1>
        <p>Tu coche en buenas manos, 24/7.</p>
        <a href="#contacto" class="cta-button">Reserva Ahora</a>
    </section>

    <section id="servicios" class="servicios">
        <h2>Nuestros Servicios</h2>
        <div class="servicio">
            <h3>Vigilancia 24/7</h3>
            <p>Tu coche siempre estará seguro con nuestro servicio de seguridad activo las 24 horas del día.</p>
        </div>
        <div class="servicio">
            <h3>Precios Competitivos</h3>
            <p>Ofrecemos tarifas asequibles para todos nuestros clientes, con descuentos por largas estancias.</p>
        </div>
        <div class="servicio">
            <h3>Fácil Acceso</h3>
            <p>Ubicación céntrica y accesible para que puedas aparcar sin complicaciones.</p>
        </div>
    </section>

    <section id="precios" class="precios">
        <h2>Nuestras Tarifas</h2>
        <table>
            <tr>
                <th>Duración</th>
                <th>Precio</th>
            </tr>
            <tr>
                <td>1 Hora</td>
                <td>2€</td>
            </tr>
            <tr>
                <td>1 Día</td>
                <td>10€</td>
            </tr>
            <tr>
                <td>1 Semana</td>
                <td>60€</td>
            </tr>
            <tr>
                <td>1 Mes</td>
                <td>200€</td>
            </tr>
        </table>
    </section>

    <section id="contacto" class="contacto">
        <h2>Contacto</h2>
        <p>¿Tienes alguna pregunta? ¡Escríbenos!</p>
        <form action="#">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>

            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>

            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Parking Seguros. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
