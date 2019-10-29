<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {margin: 0;}
ul.sidenav {
  list-style-type: none;
  margin: 0;
  padding: 0;
  width: 25%;
  background-color: #f1f1f1;
  position: fixed;
  height: 100%;
  overflow: auto;
}
ul.sidenav li a {
  display: block;
  color: #000;
  padding: 8px 16px;
  text-decoration: none;
}
 
ul.sidenav li a.active {
  background-color: #F0B429;
  color: white;
}
ul.sidenav li a:hover:not(.active) {
  background-color: #555;
  color: white;
}
div.content {
  margin-left: 25%;
  padding: 1px 16px;
  height: 1000px;
  background-color: #005883;
  
}
img.logoUnad{
  width: 330px;
  height: auto;
}
h1,h2,h3,h4,h5{
  color: #F0B429;
}
img {
    width: 250px;
    height: auto;
}
p{
  color: white;
}
@media screen and (max-width: 900px) {
  ul.sidenav {
    width: 100%;
    height: auto;
    position: relative;
  }
  
  ul.sidenav li a {
    float: left;
    padding: 15px;
  }
  
  div.content {margin-left: 0;}
}
footer {
    position: absolute;
    height: 70px;
    width: 950px;
    clear: both;
    top: 710px;
    margin-left: 20px;
    display: block;
}
@media screen and (max-width: 400px) {
  ul.sidenav li a {
    text-align: center;
    float: none;
  }
}
</style>
<script src="js/modernizr.js"></script>
<script src="js/prefixfree.min.js"></script>
<script src="js/jquery-3.2.0.js"></script>
</head>
<body>

<ul class="sidenav">
    <img class="logoUnad" src="https://raw.githubusercontent.com/damian1414/OviUnad/master/OVI_UNAD/img/unad.jpg" alt="git_logo"></a>
  <li><a href="inicio.html">Inicio</a></li>
  <li><a  class="active"  href="#news">Lecturas</a></li>
  <li><a href="#contact">Multimedia</a></li>
  <li><a href="#contact">Actividades</a></li>
  <li><a href="#about">Autores</a></li>
</ul>

<div id="contenedor" class="content">
  <center>
  <header>
      <h1 >LECTURAS</h1>
  </header>
</center>
  <br></br>
<section>
        <div align="center" style="margin-top:50px;">
        <h3>INTRODUCCIÓN AL DISEÑO DE SITIOS WEB</h3>
       </div>

    <article>
        <div align="center" style="margin-top:50px;">

        <h3>
            OBJETIVOS
        </h3>

        </div> 
        <p>
            El curso diseño de sitios web se divide en tres unidades, las cuales son: 1. Introduccion al diseño de sitios web, en esta vemos
            que es y como funciona el sistema de control de verciones GIT y el uso de GITHUB para sincronizar nuestros proyectos a travez de internet
            y asi poder trabajar de forma colaborativa, 2. HTML5 y 3. CSS3. En las unidades 2 y 3 veremos el uso de HTML y CSS para desarrollar paginas web. 
            
        </p>
        <p>
            El OVI Diseño de sitios web esta elaborado con el fin de dar a conocer informacion basica sobre el manejo de herramientas
            enfocadas al desarrollo web como los son GIT, GITHUB, HTML5 Y CSS3. Esto se realizara a travez de lecturas, videos y actividades
            cortas y faciles de entender.
        </p>
        <p>
            El objetivo de este OVI es el de dar a conocer a los visitantes del sitio informacion basica sobre que es y como funciona GIT, GITHUB, HTML5 y CSS3,
            ademas de presentar unos tutoriales sobre su intalacion y uso.
        </p>

      

    </article>

<aside>
    <div align="center" style="margin-top:50px;">
        <h3>DESCARGAS</h3>
        <figure>
           <a href="https://git-scm.com/downloads" target="_blank"><img src="https://raw.githubusercontent.com/damian1414/OviUnad/master/OVI_UNAD/img/GIT.png" alt="git_logo"></a>
           <a href="https://desktop.github.com/" target="_black"><img src="https://raw.githubusercontent.com/damian1414/OviUnad/master/OVI_UNAD/img/GITHUB.png" alt="github_logo"></a>
        </figure>
    </div>
       
</aside>

</section>
<div aling="center"> 
    <footer >
        <h4>
        UNIVERSIDAD NACIONAL ABIERTA Y A DISTANCIA || DISEÑO DE SITIOS WEB 301122_22  2019 TODOS LOS DERECHOS RESERVADOS
        </h4>
    </footer>


</div>

</div>

</body>
</html>
