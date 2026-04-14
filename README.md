<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Zenya</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #F4F6F6;
        }

        header {
            background-color: #2ECC71;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav {
            background-color: #1E8449;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #145A32;
        }

        section {
            padding: 40px;
            text-align: center;
        }

        .btn {
            background-color: #2ECC71;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        .btn:hover {
            background-color: #27AE60;
        }

        footer {
            background-color: #1E8449;
            color: white;
            text-align: center;
            padding: 10px;
        }

        .card {
            background: white;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
            display: inline-block;
            width: 250px;
        }
    </style>
</head>

<body>

<header>
    <h1>Zenya</h1>
    <p>Pequeños cambios, gran impacto</p>
</header>

<nav>
    <a href="#inicio">Inicio</a>
    <a href="#sobre">Sobre</a>
    <a href="#tips">Tips</a>
    <a href="#mapa">Mapa</a>
</nav>

<section id="inicio">
    <h2>Bienvenido a Zenya 🌿</h2>
    <p>Tu guía digital para un estilo de vida ecológico</p>
    <button class="btn">Explorar</button>
</section>

<section id="sobre">
    <h2>¿Qué es Zenya?</h2>
    <p>Zenya es una plataforma digital que promueve hábitos ecológicos y sostenibles.</p>
</section>

<section id="tips">
    <h2>Tips Ecológicos</h2>

    <div class="card">
        <h3>♻️ Recicla</h3>
        <p>Separa correctamente tus residuos.</p>
    </div>

    <div class="card">
        <h3>💧 Ahorra agua</h3>
        <p>Cierra la llave cuando no la uses.</p>
    </div>

    <div class="card">
        <h3>🌱 Reduce plástico</h3>
        <p>Usa bolsas reutilizables.</p>
    </div>

</section>

<section id="mapa">
    <h2>Mapa del Sitio</h2>
    <p>Inicio → Sobre → Tips</p>
</section>

<footer>
    <p>© 2026 Zenya - Proyecto educativo</p>
</footer>

</body>
</html>
