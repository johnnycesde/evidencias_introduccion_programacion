<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


## Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5
Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 Imagenes
- 2 Videos
- 4 Audios
- 2 Inline Frame

```html
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #8c1497;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #0f15c1;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>Aguila</h2>
        <h3></h3>
        <P>Como todas las aves de presa, las águilas poseen un pico grande, poderoso
            y puntiagudo para desprender la carne de su presa. Cuentan también con tarsos y garras poderosas. Llama
            también la atención la fuerza de las águilas, <a
                href="https://es.wikipedia.org/wiki/%C3%81guila#:~:text=Las%20%C3%A1guilas%20se%20caracterizan%20principalmente,mundo%20excepto%20en%20la%20Ant%C3%A1rtida.">Mas
                informacion</a>
        </P>

        <img src="imagen1.jpg" alt="" width="100">

        <h2>montaña</h2>

        <P> Una montaña es una figura topográfica del relieve terrestre positiva, una eminencia natural que se
            caracteriza por su altitud y, más generalmente, por su altura relativa, o incluso por su volumen, pendiente,
            espaciado o continuidad.2​ Aparecen como parte de un conjunto —una cadena montañosa, sea cordillera, macizo,
            sierra...— o formando un relieve aislado.Nota 1​Nota 2​Nota 3​Nota 4​ No existe una definición única de
            montaña, un término que apareció en Europa entre los siglos x y xii, y son numerosos los localismos y
            regionalismos usados para describir este accidente geográfico, que puede referirse tanto a una cumbre
            empinada como a una elevación simple del terreno como una colina <a
                href="https://www.nationalgeographic.es/perpetual-planet/2018/02/las-montanas-del-mundo-datos-clave#:~:text=La%20mayor%C3%ADa%20de%20los%20ge%C3%B3logos,las%20unas%20de%20las%20otras..">Mas
                informacion</a>
        </P>

        <img src="imagen2.jpg" alt="" width="100">






    </section>


    <section>

        <h2>ovejas</h2>
        <p>la oveja es una animal muy necesario en la vida del ser humana...</p>
        <source src="video.mp4" type="video/mp4">
        <video controls>

        </video>
        <video src="video2.mp4" alt="" width="400" controls></video>
    </section>



    <section>
        <h2>Audios</h2>
        <p>Contenido sobre audios...</p>
        <audio src="audio1.mp3" controls></audio>
    </section>

    <section>
        <h2>iFrames</h2>
        <p> Significado de  programacion en wikipedia...</p>
        <iframe src="https://es.wikipedia.org/wiki/programaci%c3%B3n" width="600" height="700"></iframe>

    </section>

    <footer>
        johnny londoño henao
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```