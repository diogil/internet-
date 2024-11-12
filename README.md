<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicias Caseras - Repostería Artesanal</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Encabezado -->
    <header>
        <div class="container">
            <h1>Delicias Caseras</h1>
            <nav>
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#productos">Productos</a></li>
                    <li><a href="#nosotros">Sobre Nosotros</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Sección de inicio -->
    <section id="inicio" class="section">
        <div class="container">
            <h2>Bienvenidos a Delicias Caseras</h2>
            <p>Repostería artesanal hecha con amor y los mejores ingredientes. Descubre nuestros postres, perfectos para cualquier ocasión.</p>
        </div>
    </section>

    <!-- Sección de productos -->
    <section id="productos" class="section">
        <div class="container">
            <h2>Nuestros Productos</h2>
            <div class="product">
                <h3>Tortas Personalizadas</h3>
                <p>Perfectas para cumpleaños, bodas y eventos especiales.</p>
            </div>
            <div class="product">
                <h3>Cupcakes</h3>
                <p>Pequeños y deliciosos, disponibles en diferentes sabores y decoraciones.</p>
            </div>
            <div class="product">
                <h3>Galletas Artesanales</h3>
                <p>Hechas a mano, ideales para regalos o simplemente para disfrutar.</p>
            </div>
        </div>
    </section>

    <!-- Sección sobre nosotros -->
    <section id="nosotros" class="section">
        <div class="container">
            <h2>Sobre Nosotros</h2>
            <p>Somos una pequeña empresa familiar dedicada a la repostería artesanal. Nuestra misión es ofrecer postres deliciosos que alegren cada ocasión. Utilizamos ingredientes frescos y de alta calidad en cada una de nuestras creaciones.</p>
        </div>
    </section>

    <!-- Sección de contacto -->
    <section id="contacto" class="section">
        <div class="container">
            <h2>Contacto</h2>
            <p>¿Tienes una pregunta o quieres hacer un pedido especial? Contáctanos:</p>
            <p>Email: contacto@deliciascaseras.com</p>
            <p>Teléfono: +123 456 7890</p>
            <p>Síguenos en redes sociales para ver nuestras últimas creaciones y promociones.</p>
        </div>
    </section>

    <!-- Pie de página -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Delicias Caseras. Todos los derechos reservados.</p>
        </div>
    </footer>
</body>
</html>

/* Reset general */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Estilo general */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
}

.container {
    width: 960px;
    margin: 0 auto;
    padding: 20px;
}

/* Encabezado */
header {
    background-color: #d2691e;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5em;
}

header nav ul {
    list-style: none;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Secciones */
.section {
    padding: 60px 0;
    text-align: center;
}

.section h2 {
    font-size: 1.8em;
    color: #d2691e;
    margin-bottom: 20px;
}

.section p {
    font-size: 1em;
    color: #555;
}

/* Productos */
.product {
    margin: 20px 0;
}

.product h3 {
    font-size: 1.5em;
    color: #333;
}

.product p {
    font-size: 1em;
    color: #777;
}

/* Sección de contacto */
#contacto {
    background-color: #f4f4f4;
}

/* Pie de página */
footer {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
    font-size: 0.9em;
}
