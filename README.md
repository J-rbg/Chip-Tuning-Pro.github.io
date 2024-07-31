<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trading Pro</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="scripts.js"></script>
</head>
<body>
    <header>
        <div class="container">
            <h1>Trading Pro</h1>
            <nav>
                <a href="#">Inicio</a>
                <a href="#services">Servicios</a>
                <a href="#about">Sobre Nosotros</a>
                <a href="#contact">Contacto</a>
            </nav>
        </div>
    </header>

    <main>
        <section class="hero">
            <div class="container">
                <h2>Maximiza tus inversiones con Trading Pro</h2>
                <p>Ofrecemos estrategias avanzadas de trading para ayudarte a alcanzar tus objetivos financieros.</p>
                <a href="#contact" class="cta-button">Contáctanos</a>
            </div>
        </section>

        <section id="services" class="services">
            <div class="container">
                <h2>Servicios</h2>
                <div class="service-item">
                    <h3>Asesoramiento en Trading</h3>
                    <p>Recibe consejos personalizados sobre las mejores estrategias de trading.</p>
                </div>
                <div class="service-item">
                    <h3>Gestión de Carteras</h3>
                    <p>Te ayudamos a gestionar y optimizar tu cartera de inversiones.</p>
                </div>
                <div class="service-item">
                    <h3>Capacitación en Trading</h3>
                    <p>Accede a cursos y talleres para mejorar tus habilidades en trading.</p>
                </div>
            </div>
        </section>

        <section id="about" class="about">
            <div class="container">
                <h2>Sobre Nosotros</h2>
                <p>En Trading Pro, somos un equipo de expertos en finanzas y trading con años de experiencia en el mercado. Nos dedicamos a proporcionar soluciones de inversión personalizadas para ayudarte a lograr el éxito financiero.</p>
            </div>
        </section>

        <section id="contact" class="contact">
            <div class="container">
                <h2>Contacto</h2>
                <form id="contact-form">
                    <label for="name">Nombre:</label>
                    <input type="text" id="name" name="name" required>

                    <label for="email">Correo Electrónico:</label>
                    <input type="email" id="email" name="email" required>

                    <label for="message">Mensaje:</label>
                    <textarea id="message" name="message" rows="5" required></textarea>

                    <button type="submit">Enviar</button>
                </form>
                
                <h3>Realiza un Pago</h3>
                <!-- PayPal Button -->
                <div id="paypal-button-container"></div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Trading Pro. Todos los derechos reservados.</p>
        </div>
    </footer>

    <!-- PayPal SDK -->
    <script src="https://www.paypal.com/sdk/js?client-id=YOUR_CLIENT_ID"></script>
</body>
</html>
