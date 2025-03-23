# sticky_gummy.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="icon" type="image/png" href="https://www.bing.com/images/search?view=detailV2&ccid=744mxzC5&id=328D501768AE348BACBFBFBEDBCE6F9AFCA5DC9B&thid=OIP.744mxzC5wmuJwSAv6Ej3XwHaHa&mediaurl=https%3a%2f%2femaillistvalidation.com%2fblog%2fcontent%2fimages%2f2023%2f09%2fHTML5_logo_and_wordmark.svg.png&cdnurl=https%3a%2f%2fth.bing.com%2fth%2fid%2fR.ef8e26c730b9c26b89c1202fe848f75f%3frik%3dm9yl%252fJpvztu%252bvw%26pid%3dImgRaw%26r%3d0&exph=1200&expw=1200&q=html&simid=607997804734399637&FORM=IRPRST&ck=8BAC6CDE3C144673F97DFAC53EF67734&selectedIndex=7&itb=1">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coding</title>
</head>
<body>
    <header>
    <h1>Aprendiendo HTML</h1>
    </header>
    
    <h2 id="start">Inicio</h2>

    <nav>
        <a href="#labels">Etiquetas</a>
        <a href="#links">Enlaces</a>
        <a href="#lists">listas</a>
        <a href="#table">Tablas</a>
        <a href="#form">Formulario</a>
        <a href="#music">Musica y videos</a>
        <a href="#graf">Graficos</a>


    <p>Aqui irian los enlaces</p>
    </nav>

    <a target="_blank" href="https://www.bing.com/images/search?view=detailV2&ccid=kYpE8fdV&id=9E20D2AB31948F10D62518BB60923B67663FC23D&thid=OIP.kYpE8fdVW0BhrDXUWUJZuwAAAA&mediaurl=https%3a%2f%2fcdn.memegenerator.es%2fimagenes%2fmemes%2ffull%2f2%2f6%2f2067294.jpg&cdnurl=https%3a%2f%2fth.bing.com%2fth%2fid%2fR.918a44f1f7555b4061ac35d4594259bb%3frik%3dPcI%252fZmc7kmC7GA%26pid%3dImgRaw%26r%3d0&exph=320&expw=400&q=si+tuviea+uno&simid=608009121962598706&FORM=IRPRST&ck=3D51FDFA97DEB3D2C1CCE25879840AB0&selectedIndex=0&itb=0">
        <img src="https://th.bing.com/th/id/OIP.kYpE8fdVW0BhrDXUWUJZuwAAAA?w=225&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7" alt="El papa de timmy Turner", title="Si tan solo tuviera uno..." width="400", height="300">    
    </a>

    <header><h2 id="labels">Etiquetas</h2></header>  <nav> <a href="#start">Inicio</a> </nav>-----------------------------------------------------------------------------------------------------------------------

    <hr>
    <header> <strong>header</strong> es para el encabezado</header>
   
    <aside> <strong>aside</strong> lleva informacion adicional</aside>
    <br>
    <hr>

    <section> <strong>Organizar con <strong>section</strong> </strong> <article> informacion </article> <article>areas</article> <article>Se usa <strong>article</strong> para organizar</article> </section>


    <P> <strong>p</strong> sirve para hacer parrafos, <b>b son para negritas</b>, <strong>strong es para negritas pero con mas fuerza</strong> <br> <strong>br</strong> sirve para hacer un salto de linea</P> 

    <hr>

    <p> <em> <strong>em</strong> es para cursivas con enfasis </em>  <br> <i> <strong>i</strong> para cursiva <br> y el <strong>hr</strong> es para hacer lineas horizontales</i></p>
    <footer> Pie de pagina con <strong>footer</strong> </footer>


    <hr>------------------------------------------------------------------------------------------------------------------------------------------------------------------

    <h2 id="links">Enlaces</h2> <nav> <a href="#start">Inicio</a> </nav>

    <p>Aqui observamos los enlaces que se manejan abriendo <i><strong> nav </strong></i> y dentro de el agregamos la variable <strong> "a" </strong> y dentro de la pagina podemos ponerles id a las partes a las que queremos navegar</p> <br>
    <p>para mas informacion clickea el siguiente link</p>

    <nav>
        <a target="_blank" href="https://www.youtube.com/watch?v=uphhHrkRLQA&t=688s"> youtube </a> <br>
        <a target="_blank"  href="2daPag.html">Mi segunda pagina aqui</a> <br>
        <a target="_blank"  href="C:\Users\Hp Elitebook G5\Pictures\th.jpg"> Imagen </a> <br>
        <p>Si te esta gustando puedes descargar mi archivo justo en el siguiente enlace "archivo"</p> <br>
        <a href="C:\Users\Hp Elitebook G5\Documents\UnPocoDeHTML.rar">archivo</a>
    </nav>

    <hr>------------------------------------------------------------------------------------------------------------------------------------------------------------------

    <h2 id="lists">Listas</h2> <nav> <a href="#start">Inicio</a> </nav>

    <ul type="square"> 
        <li>Item</li>
        <li>Item</li>
        <li>Item</li>
        <li>Item</li>
        <ul>
            <li>dentro</li>
        </ul>
    </ul>

    <ol type="I">
        <li>Item</li>
        <li>Item</li>
        <li>Item</li>
        <li>Item</li>
    </ol>

    <dl>
        <dt>HTML</dt>
            <dd>HTML es...</dd>
    </dl>

    <hr>
    <h2 id="table">Tablas</h2> <nav> <a href="#start">Inicio</a> </nav>

    <table border="2">
        <caption>Mi horario</caption>
        <tr>
            <th colspan="5"> HORARIO </th>
            <th colspan="2"> FINDE </th>
        </tr>
        <tr>
            <th>Lunes</th>
            <th>Martes</th>
            <th>Miercoles</th>
            <th>Jueves</th>
            <th>Viernes</th>
            <th>Sabado</th>
            <th>Domingo</th>
        </tr>
        <tr>
            <td>Programar</td>
            <td>Programar</td>
            <td>Programar</td>
            <td>Programar</td>
            <td>Programar</td>
            <td rowspan="2">Descanso</td>
            <td>Descanso</td>
        </tr>
        <tr>
            <td>Programar</td>
            <td>Programar</td>
            <td>Programar</td>
            <td>Programar</td>
            <td>Programar</td>
            <td>Descanso</td>
        </tr>
    </table>

    <hr>

    <h2 id="form">Formularios</h2> <nav> <a href="#start">Inicio</a> </nav>

    <form action="">

        <fieldset>
            <legend>Dato del usuario</legend>
        

                <label for="name">Nombre:</label><br>
                <input type="text" id="name" name="name", placeholder="Ingresa tu nombre">

                <br> 

                <label for="">Correo</label><br>
                <input type="email" id="" name="email", placeholder="Ingresa tu correo">

                <br> 

                <label for="pass">Contraseña</label><br>
                <input type="password" id="pass" name="pass", placeholder="Ingresa tu Contraseña"><br>

                <label for="birt">Fecha de nacimiento</label><br>
                <input type="date" name="birt" id="birt"><br><br>

                <label for="cv">Ingresa tu cv:</label>
                <input type="file" name="cv" id="cv"><br>

                <textarea name="Description" id="Description" cols="50" rows="15"></textarea>

        </fieldset>

        <fieldset>
            <legend>Color favorito</legend>

            <input type="radio" id="red" name="col" value="red">
            <label for="red">Rojo</label><br>

            <input type="radio" id="bl" name="col" value="blue">
            <label for="bl">Azul</label><br>

            <input type="radio" id="gr" name="col" value="green">
            <label for="gr">Verde</label><br>

            <input type="color" name="color"><br>

            <select name="color2" id="color2">
                <option value="blue">Azul</option><br>
                <option value="red">Rojo</option><br>
                <option value="green">Verde</option><br>
            </select>

        </fieldset>

        <fieldset>
            <legend>Hobbyes</legend>

            <input type="checkbox" id="read" name="hobbye1" value="read">
            <label for="read">leer</label> <br>

            <input type="checkbox" id="dance" name="hobbye2" value="dance">
            <label for="dance">bailar</label> <br>

            <input type="checkbox" id="coding" name="hobbye3" value="coding">
            <label for="coding">programar</label> <br>

        </fieldset>
        <br>
        <input type="submit" value="Listo">
        <input type="reset" value="Borrar">

    </form>

    <br>
    <hr>

    <h2 id="music">Musica y videos</h2> <nav> <a href="#start">Inicio</a> </nav>
    <audio controls>
        <source src="C:\Users\Hp Elitebook G5\Music\AnyUkit\music\PERREO INCÓMODO (Al Volante).mp3" type="audio/mp3"> 
    </audio> <br>
    <hr>

    <video src="C:\Users\Hp Elitebook G5\Videos\WhatsApp Video 2024-10-17 at 10.56.59 PM.mp4" controls height="300" width="500"></video>
    <br>
    <hr>

    <iframe width="560" height="315" src="https://www.youtube.com/embed/akFzU5K8VL0?si=dpgJaL-f6kkz7Y7W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

    <br>
    <hr>
    
    <h2 id="graf">Graficos</h2> <nav> <a href="#start">Inicio</a></nav>

    


</body>
</html>
