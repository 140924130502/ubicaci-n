<html>
<head> 
	<meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Ubicación </title>
<style>
	* {
		box-sizing: border-box;
	}

	body {
		font-family: century ghotic; 
		padding: 50px;
		background: #FFFFCC;
	}

	/* Header/Blog Title */
	.header {
		padding: 30px; 
		text-align: center; 
		background: yellow;
	}

	.header h1 { 
		font-size: 60px;
	}

	/* Style the top navigation bar*/
	.topnav {
		overflow: hidden; 
		background-color: #663300;
	}

	/* Style the topnav links */ 
	.topnav a {
		float: left;
		display: block; 
		color: #ffffff; 
		text-align: center;
		padding: 16px 16px; 
		text-decoration: none;
	}

	/* Change color on hover */ 
	.topnav a:hover {
		background-color: #ffffff; 
		color: black;
	}

	/* Create two unequal columns that floats next to each other / / Left column */
	.leftcolumn {
		float: left; 
		width: 75%;
	}

	/* Right column */
	.rightcolumn {
		float: left; 
		width: 25%;
		background-color: #663300; 
		padding-left: 10px;
	}

	/* Fake image */ 
	.fakeimg {
		background-color: #ffffff; 
		width: 100%; 
		padding: 20px;
	}

	/* Add a card effect for articles */ 
	.card {
		background-color: white;
		padding: 20px; 
		margin-top: 20px;
	}

	/* Clear floats after the columns */ 
	.row::after{
		content: ""; 
		display: table; 
		clear: both;
	}

	/* Footer */ 
	.footer{
		padding: 20px; 
		text-align: center; 
		background: #ddd; 
		margin-top: 20px;
	}

/*Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
	.leftcolumn, .rightcolumn {
		width: 100%;
		padding: 0;
	}
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */ 
@media screen and (max-width: 800px){
	.topnav a {
		float: none; 
		width: 100%;
	}
}
</style> 
</head>
<body>
	<div class="header">
		<h1 > "Ubicación" </h1>

	</div>

	<div class="topnav">
		<a href="http://localhost/UV/men%C3%BA.html"> Menú </a> 
		<a href="http://localhost/UV/ubicaci%C3%B3n.html"> Ubicación </a> 
		<a href="http://localhost/UV/promociones.html"> Promociones </a>
		<a href="http://localhost/UV/sitioweb.html" style="float:right"> Inicio</a>
	</div>

	<div class="row">
		<div class="leftcolumn">
			<div class="card">
				<h1> ¡¡ Nuestra ubicación !!</h1>
				<h2> Para su más facil llegada </h2>
				<div class="" style="height:100px;"></div> 
				<div class="resposive">
		<div class="gallery">
			<a target="_blank" href="img/taco7.jpg">
				<img src="img/taco7.jpg" alt="taco7" width="1100" height="1100">
			</a>
		</div>
	</div>
					<h2> </h2> 
				</div> 
				<div class="card"> 
				
					<div class="fakeimg" style="height:70px;"></div> 
					<h2>  Esperamos la Ubicación sea de su agrado.</h2>
					<h3> De ser el caso contrario, podria dejar una opinión con algun lugar que seria de su agrado en el apartado de opiniones, Gracias!.</h3>
					<h4> Opinión:
					@......:</h4>
			</div> 
		</div>

		<div class="rightcolumn">
			<div class="card">
				<div class="resposive">
		<div class="gallery">
			<a target="_blank" href="img/taco8.jpg">
				<img src="img/taco8.jpg" alt="taco8" width="400" height="600">
			</a>
		</div>
				<div class="pizza2img" style="height: 70px;"></div> 

			</div> 

			<div class="card"> 
				<h1 text= "center"> Nuestras Redes</h1> 
			<div class="card">
		<div class="gallery">
			<a target="_blank" href="img/taco4.jpg">
				<img src="img/taco4.jpg" alt="taco4" width="350" height="400">
			</a>
		</div>
				<h3 text= "center">¡ No olvides seguirnos en nuestras redes sociales!</h3>
				<div class="pizza4img" style="height: 50px; width: "></div>
			</div>
		</div>
	</div>
	<div class="footer"> 
		<h2>www.TaqueAMORdidaPerfecta.com</h2>
		<h2> Contacto: 2256-874-102</h2>
		<h2> Horario de atención</h2>
		<h3> Lun-Vie:   12:00 a  22:00</h3>
		<h3> Sab-Dom:   10:00 a  24:00</h3>
		<div class="pizza4img" style="height: 80px; width:60px; "></div>
	</div>
</body> 
</html>
