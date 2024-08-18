<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Colección de Juguetes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            background-color: #ffcc00;
            color: #333;
            text-align: center;
            padding: 20px;
        }

        h1 {
            font-size: 2.5em;
            margin: 0;
            color: #333;
        }

        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.2em;
        }

        .container {
            padding: 20px;
        }

        .section {
            margin-bottom: 40px;
        }

        .section h2 {
            color: #ff5733;
            font-size: 2em;
            border-bottom: 3px solid #ffcc00;
            padding-bottom: 10px;
        }

        .section p {
            font-size: 1.2em;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .gallery img {
            width: 100%;
            height: auto;
            border: 5px solid #333;
            border-radius: 10px;
            transition: transform 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Mi Colección de Juguetes</h1>
</header>

<nav>
    <a href="#descripcion">Descripción</a>
    <a href="#toy-story">Toy Story</a>
    <a href="#marvel">Marvel</a>
    <a href="#chespirito">Chespirito</a>
</nav>

<div class="container">
    <section id="descripcion" class="section">
        <h2>Descripción</h2>
        <p>Bienvenido a mi página personal sobre coleccionismo. Aquí podrás encontrar una selección de mis coleccionables favoritos de Toy Story, Marvel, Chespirito, y otros temas. Cada pieza tiene un valor especial para mí, y me encanta compartir esta pasión con otros entusiastas.</p>
    </section>

    <section id="toy-story" class="section">
        <h2>Toy Story</h2>
        <div class="gallery">
            <img src="toy_story_1.jpg" alt="Coleccionable de Toy Story 1">
            <img src="toy_story_2.jpg" alt="Coleccionable de Toy Story 2">
            <img src="toy_story_3.jpg" alt="Coleccionable de Toy Story 3">
        </div>
    </section>

    <section id="marvel" class="section">
        <h2>Marvel</h2>
        <div class="gallery">
            <img src="marvel_1.jpg" alt="Coleccionable de Marvel 1">
            <img src="marvel_2.jpg" alt="Coleccionable de Marvel 2">
            <img src="marvel_3.jpg" alt="Coleccionable de Marvel 3">
        </div>
    </section>

    <section id="chespirito" class="section">
        <h2>Chespirito</h2>
        <div class="gallery">
            <img src="chespirito_1.jpg" alt="Coleccionable de Chespirito 1">
            <img src="chespirito_2.jpg" alt="Coleccionable de Chespirito 2">
            <img src="chespirito_3.jpg" alt="Coleccionable de Chespirito 3">
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2024 Mi Colección de Juguetes. Todos los derechos reservados.</p>
</footer>

</body>
</html>
