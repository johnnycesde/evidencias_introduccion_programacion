<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->

# Actividad: Aplicando estilos con selectores CSS
## El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

## Solución

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Actividad8</title>
    <link rel="stylesheet" href="stylo.css">
</head>

<body>

    <header>
        <h1>VIDEOJUEGOS CLÁSICOS</h1>
    </header>
    <section>
        <h3 class="destacado">Donkey Kong</h3>
        <p>Donkey Kong es el primer juego creado por Shigeru Miyamoto y supuso la creación de dos de los personajes más
            importantes de Nintendo: Mario y Donkey Kong.</p><br>
        <h3 class="destacado">Pac-Man</h3>
        <p>El popular comecocos llegó a las máquinas de arcade en 1980 y es uno de los juegos clásicos más importantes
            de la
            historia. Un sencillo juego en el que tan solo hay que ir recogiendo puntos y otros objetos hasta limpiar el
            nivel y
            pasar al siguiente.</p><br>
        <h3 class="destacado">Super Mario Bros</h3>
        <p>Super Mario Bros es el primer juego con Mario de protagonista. Desarrollado por Miyamoto y publicado por
            Nintendo
            para NES en 1985, se trata de un juego de plataformas que ha trascendido al medio y se ha convertido en todo
            un
            icono de la cultura popular.</p><br>
    </section>
    <div>
        <p>Los recuerdas? Una década dorada que dio origen a multitud de clásicos</p>
        <img src="assets/character-l.png" alt="">
    </div>
    <footer>
        <p class="grande">johnny londoño henao</p>
        <p id="principal">Juegos clásicos de los 80s</p>
        <p id="sombras">Copyright © 2023, My Website. Todos los derechos reservados.</p>
    </footer>

</body>

</html>

~~~

### STYLO.CSS

~~~css

/*selectores de etiqueta*/
h1 {
    color: red;
}

p {
    color: blue;
}

img {
    border: 10px solid black;
}

/*seleccionadores de clase*/

.destacado {
    color: green;
}

.grande {
    font-size: large;
}

/*seleccionadores de ID*/

#principal {
    color: yellow;
}

#sombras {
    color: yellow;
    font-weight: 900;
    text-shadow: 3px 3px 0px green, 5px 5px 0px black;
}

/*seleccionadores descendientes*/
div p {
    color: gray;
    text-align: center;
}
section h3, p {
    text-align: center;
}

~~~