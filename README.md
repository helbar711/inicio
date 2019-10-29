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
  width: 480px;
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
    margin-left: 140px;
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
        <img class="logoUnad" src="img/unad.jpg" alt="git_logo"></a>
        <li><a href="https://raw.githubusercontent.com/damian1414/OviUnad/9ce4b8391b964fcf6183d466b77a10d8fba40319/OVI_UNAD/inicial.html">Inicio</a></li>
        <li><a href="https://github.com/damian1414/OviUnad/commit/9ce4b8391b964fcf6183d466b77a10d8fba40319">Lecturas</a></li>
        <li><a href="#contact">Multimedia</a></li>
        <li><a href="#contact">Actividades</a></li>
        <li><a href="#about">Autores</a></li>
      </ul>

<div id="contenedor" class="content">

</div>

</body>
</html>
