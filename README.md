# elitec
Empresa de tecnología 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Laboratios UTJ CDD</title>
    <meta name="Nombre" content="caso practico">
    <meta name="Autor" content="Susana Felix y Karla Molina">
    <meta name="Descripción" content="Laboratorios UTJ">
    <meta name="keywords" content="Laboratorios, UTJ, CCD">
    <meta name="Tamaño de ventanas" content="width=device-width, initial-scale=1.0">
    <link  rel="shortcut icon" href="ico/favicon.png" type="image/png">


    <link rel="stylesheet" type="text/css" href="https://use.fontawesome.com/releases/v5.4.2/css/all.css" integrity="sha384-/rXc/GQVaYpyDdyxK+ecHPVYJSN9bmVFBvJA/9eOB+pb3F2w2N6fc5qB9Ew5yIns">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
    

  <style type="text/css">
    .navbard-brand{
      background-color: #AFAFAF
    }
  </style>

</head>

<body data-spy="scroll" data-target=".bs-docs-sidebar">
    <!--CONTENIDO DE LA PAGINA-->
<div class="container">
<!--ENCABEZADO-->
    <header>
  <?php include_once("header.php");

   ?>  
</header>
    <!--BARRA DE NAVEGACION-->
<nav>
<div class="container">
<div class="navbar navbar-expand-lg bg-secondary navbar-dark">
  <a class="navbar-brand" href="index.php"> <font>Página Principal</font> </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <ul class="navbar-nav">
      
      <li><a class="nav-item nav-link" href="login.php">Iniciar sesión</a></li>
    </ul>
  </div>
  </div>
</div>
    <!--CONTENIDO PRINCIPAL-->
    <main class="row col-12" > 
        <section class="col-9">
            <article class="card bg-light">
                <div class="card-body">
                    <h1 class="blog-tittle" align="center"> Laboratorios UTJ</h1><br>
                    <img src="../../img/lab.jpg" width="100% height="580" ><br><br>
                    <u><i>Publicado 01 Jul 2020</i> </u><br>
                    <div align="justify"><br>
                    <p>
                        El laboratorio de computación (también conocido como laboratorio de informática o como centro de cómputo) es el lugar donde se prestan servicios de cómputo a los miembros de una comunidad o institución educativa. En el contexto educativo, el laboratorio de cómputo se ubica dentro de la propia institución académica, y tiene como objetivo proporcionar a los usuarios del recinto (estudiantes y personal docente) el servicio de préstamo de equipos de cómputo, para la enseñanza o el aprendizaje de la informática.</p>

                       <p> Además del préstamo de equipos, en el laboratorio de cómputo se pueden realizar prácticas didácticas para enseñar acerca o con computadoras, con el fin de desarrollar habilidades instrumentales que harán posible la interacción de los usuarios con los sistemas de información. De esta manera, “el laboratorio de cómputo es un espacio destinado a la realización de las experiencias prácticas y actividades vinculadas con el uso de computadoras; en él se desarrollan los conocimientos básicos de la informática como parte de los medios de comunicación de vanguardia, donde los conocimientos adquiridos permiten la aplicación del software adecuado; asimismo, se propicia la aplicación de los conocimientos necesarios para la programación de las computadoras”.</p>

                        <p>El laboratorio de cómputo surge entonces como una entidad para propiciar la relación entre la investigación que es aplicada, la formación de recursos humanos, y la vinculación existente en el área de las Ciencias de la Computación4​ y de otras disciplinas académicas
                    </p>
                 </div>
                </div>
            </article>
        </section>

        <aside class="col-3"><br>
            <img src="../../img/ccd.jpg" width=100% height=200px>
            <div align="justify"><br>
                <b>Ciudad Creativa Digital (CCD) </b>
                <p>Es un proyecto llevado a cabo por la Secretaría de Economía del Gobierno Federal, ProMéxico, Sociedad Hipotecaria Federal, el Gobierno de Jalisco, la CANIETI y el Ayuntamiento de Guadalajara que busca la renovación del entorno urbano para crear un espacio idóneo para el desarrollo de las personas, generar un escenario moderno e interconectado donde el talento y la creatividad generen conocimiento, impulsando el uso de nuevas tecnologías. El proyecto fue anunciado por el presidente Felipe Calderón Hinojosa y el gobernador Emilio González Márquez el 30 de enero de 2012.</p>

                <p>Ubicada en el corazón de la capital de Jalisco, CCD concentra industrias creativas tales como firmas productoras de cine, televisión, videojuegos, animación digital, medios interactivos y aplicaciones móviles, entre otras más.</p>
            </div>
        </aside>
    </main><br>

     <!--PIE DE PAGINA-->
    <footer>
     <?php 
        include_once("footer.php");
     ?> 
    </footer>

    </div>
</body>
</html>
