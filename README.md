<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barbería Yambeque</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #444;
            text-align: center;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 10px;
        }
        nav a:hover {
            background-color: #555;
        }
        section {
            padding: 20px;
            margin: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .services {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .service {
            background-color: #fff;
            border: 1px solid #ddd;
            padding: 15px;
            margin: 10px;
            border-radius: 8px;
            width: 200px;
            text-align: center;
        }
        .service h3 {
            margin-top: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Bienvenidos a la página web de la mejor barbería de Ibagué</h1>
</header>

<nav>
    <a href="#bienvenidos">Bienvenidos</a>
    <a href="#sobre-mi">Sobre mí</a>
    <a href="#servicios">Servicios</a>
</nav>

<section id="bienvenidos">
    <h2>Bienvenidos</h2>
    <p>¡Gracias por visitar Barbería Yambeque, donde la excelencia y el estilo se encuentran! Nos enorgullece ofrecer un servicio de calidad en el corazón de Ibagué. Con un ambiente único, dedicado a resaltar tu personalidad, nuestra misión es que cada cliente se sienta especial.</p>
</section>

<section id="sobre-mi">
    <h2>Sobre mí</h2>
    <p>Hola, soy Kevin Flórez, un barbero apasionado por lo que hago. Es un gusto conocerte y ofrecerte lo mejor de mi arte en el cuidado personal. Me esfuerzo por ofrecerte un corte de pelo, barba o diseño que te haga sentir renovado y seguro.</p>
</section>

<section id="servicios">
    <h2>Servicios</h2>
    <div class="services">
        <div class="service">
            <h3>Corte de Pelo</h3>
            <p>El corte de pelo perfecto para ti, adaptado a tu estilo y personalidad.</p>
        </div>
        <div class="service">
            <h3>Barba</h3>
            <p>Recorta, perfila y da forma a tu barba para que luzca impecable.</p>
        </div>
        <div class="service">
            <h3>Cejas</h3>
            <p>Alineación y perfilado de cejas para complementar tu rostro.</p>
        </div>
        <div class="service">
            <h3>Diseños</h3>
            <p>Diseños artísticos en el cabello y la barba, personalizados para ti.</p>
        </div>
    </div>
</section>

<footer>
    <p>© 2024 Barbería Yambeque | Todos los derechos reservados</p>
</footer>

</body>
</html>

