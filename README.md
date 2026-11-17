# nombre-del-emprendimiento
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SHOKO 3D - Impresiones 3D</title>
    <style>
        /* Estilos Generales */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            background-color: #f9f4e9;
            color: #333;
        }

        /* Header / Navegación */
        header {
            background-color: #f7941e;
            padding: 15px 30px;
        }

        .logo-container {
            display: flex;
            align-items: center;
            justify-content: space-between;
            max-width: 1000px;
            margin: 0 auto;
        }

        .logo-img {
            height: 60px;
            width: auto;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
            font-size: 16px;
        }

        nav a:hover {
            color: #333;
        }

        /* Sección Hero / Inicio */
        .hero {
            background-color: #f7941e;
            color: white;
            text-align: center;
            padding: 40px 20px;
            border-bottom-left-radius: 30px;
            border-bottom-right-radius: 30px;
        }

        .hero-img {
            width: 180px;
            max-width: 100%;
            margin-bottom: 15px;
        }

        .hero h1 {
            font-size: 36px;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 18px;
            max-width: 600px;
            margin: 0 auto 20px auto;
        }

        /* Categorías / Productos Destacados */
        .content-section {
            max-width: 1000px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .section-title {
            text-align: center;
            font-size: 28px;
            color: #f7941e;
            margin-bottom: 30px;
        }

        .cards-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }

        .card {
            background-color: #ffffff;
            border-radius: 15px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .card h3 {
            color: #333;
            font-size: 20px;
        }

        /* Banner Pedidos / Contacto */
        .cta-banner {
            background-color: #f7941e;
            color: white;
            text-align: center;
            padding: 40px 20px;
            margin-top: 40px;
            border-radius: 20px;
        }

        .cta-banner h2 {
            font-size: 28px;
            margin-bottom: 10px;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            padding: 30px 20px;
            margin-top: 50px;
        }

        .footer-container {
            max-width: 1000px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 20px;
        }

        .footer-col h4 {
            margin-bottom: 10px;
            color: #f7941e;
        }

        .footer-col p, .footer-col a {
            color: #ccc;
            text-decoration: none;
            line-height: 1.6;
        }

        .copyright {
            text-align: center;
            margin-top: 30px;
            padding-top: 15px;
            border-top: 1px solid #444;
            color: #888;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <!-- Header / Menú -->
    <header>
        <div class="logo-container">
            <img src="shoko logo png.png" alt="Shoko 3D Logo" class="logo-img">
            <nav>
                <a href="#inicio">Inicio</a>
                <a href="#productos">Productos</a>
                <a href="#contacto">Contacto</a>
            </nav>
        </div>
    </header>

    <!-- Sección Principal (Hero) -->
    <section id="inicio" class="hero">
        <img src="SHOKO FELIZ .png" alt="Mascota Shoko 3D" class="hero-img">
        <h1>SHOKO 3D</h1>
        <p>Somos un emprendimiento de impresiones 3D. Podés encontrar un montón de juguetes y accesorios para todos.</p>
    </section>

    <!-- Sección Productos Destacados -->
    <section id="productos" class="content-section">
        <h2 class="section-title">Productos Destacados</h2>
        <div class="cards-grid">
            <div class="card">
                <img src="ef9e4122c3f9b07a.webp" alt="Juguetes articulados">
                <h3>Juguetes</h3>
            </div>
            <div class="card">
                <img src="8183ce7175b6dd9e.webp" alt="Decoración 3D">
                <h3>Decoración</h3>
            </div>
            <div class="card">
                <img src="2024-05-10_1ad4105e1755e.webp" alt="Figuras coleccionables">
                <h3>Figuras</h3>
            </div>
            <div class="card">
                <img src="88d7c49bd518d2ad.webp" alt="Accesorios y más">
                <h3>Accesorios</h3>
            </div>
        </div>
    </section>

    <!-- Banner Hace tu pedido -->
    <div class="content-section">
        <div class="cta-banner">
            <h2>LO QUE IMAGINES LO PODEMOS CREAR</h2>
            <p>Hace tu pedido acá</p>
        </div>
    </div>

    <!-- Footer / Contacto -->
    <footer id="contacto">
        <div class="footer-container">
            <div class="footer-col">
                <h4>Sobre nosotros</h4>
                <p>Inicio</p>
                <p>Servicios</p>
                <p>Contacto</p>
            </div>
            <div class="footer-col">
                <h4>Contacto</h4>
                <p>Cel: 2216030322</p>
                <p>Berisso, Argentina</p>
            </div>
        </div>
        <div class="copyright">
            <p>&copy; SHOKO 3D - Todos los derechos reservados</p>
        </div>
    </footer>

</body>
</html>
