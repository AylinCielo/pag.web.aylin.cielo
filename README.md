@charset "utf-8";
* {
  box-sizing: border-box;
}

.imagen {
  background-image: url(" img/Sin-título-1.jpg");
  filter: blur(8px);
  -webkit-filter: blur(2px);
  height: 100%; 
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.bg-text {
  background-color: rgb(0,0,0); 
  background-color: rgba(0,0,0, 0.4); 
  color: white;
  font-weight: bold;
  border: 3px solid #f1f1f1;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 2;
  width: 80%;
  padding: 20px;
  text-align: center;
text-decoration: none; 
}
.button button {
    border-radius: 50px;
    text-shadow: 0px 0px #00BEFF;
	border: none;
    outline: 0;
    display: inline-block;
    padding: 10px 25px;
    color: black;
    background-color: #ddd;
    text-align: center;
    cursor: pointer;
    margin-top: 21px;
    margin-right: 12px;
	text-decoration: none;
	
}
<html>
<head>
<meta charset="utf-8">
<title>Pagina personal</title>


<style>
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}


</style>
<link href="stylepag.css" rel="stylesheet" type="text/css">
</head>
<body>

<div class="imagen"></div>

<div class="bg-text">
  <h2>Página personal</h2>
  <h1 style="font-size:50px">Aylín Cielo</h1>
	<p>Diseñadora Gráfica</p>
	  <p>
		  <div class="button">
	  	<ul>
			<button><il><a href="sobre_mi.html">Sobre mi</a></il></button>
			<button><il><a href="curriculum.html">Curriculum</a></il></button>
			<button><il><a href="RECONOCIMIENTOS.html">RECONOCIMIENTOS</a></il></button>
			<button><il><a href="diseños.html">Área de diseño</a></il></button>
			<button><il><a href="Contacto.html">Contactos</a></il></button>
	  		<button><il><a href="esqueleto.html">Inicio</a></il></button>
		</ul>
			  </div>
	  </p>
	</div>

</body>
<footer></footer>
</html>


