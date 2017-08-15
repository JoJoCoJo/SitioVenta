# SitioVenta
Sitio web en el cual se venden celulares y tabletas, asi como productos tecnologicos de ultimo moda.


## Site Map

<p align="center">
  <img src="docs/images/MapaSitio.png" />
</p>

El sitio contará con:
  * Index: O página principal/bienvenida.
  * Galería de Productos General: Se mostrarán todo los productos en general con los que cuenta el sitio.
  * Telefonos: Página donde se muestran sólo los Telefonos con los que cuenta el sitio.
  * Tablets: Página donde se muestran sólo las Tablets disponibles en el sitio.
  * Novedades: Página donde se muestran las noticias/gadgets más recientes.

## Wireframing

### Index

La pantalla de inicio:

<p align="center">
  <img src="docs/images/Mockups/Index.png" />
</p>

En la cuál podemos observar que nos da la bienvenida, un link donde podemos ir directamente a la galería de productos y un video introductorio de la tienda en linea.

<p align="center">
  <img src="docs/images/Mockups/Index2.png" />
</p>

En la siguiente sección de la página principal podemos ver Testimonios de las personas que han comprado en nuesto sitio.

<p align="center">
  <img src="docs/images/Mockups/Index3.png" />
</p>

Y como último una sección de la página principal encontramos un área para poder mandar quejas y/ sugerencias en donde el usuario ingreará su correo electrónico, escojerá si es una "**queja**" o una "**sugerencia**", rellenar el mensaje dependiendo a su experiencia con la plataforma y por último el botón de enviar.

### Galería

Para la galería empezamos de la siguiente manera:

<p align="center">
  <img src="docs/images/Mockups/GaleriaGeneral.png" />
</p>

Donde se muestran los productos principales en venta de la página que son los Telefonos, Tablets y un apartado para las Novedades.

<p align="center">
  <img src="docs/images/Mockups/GaleriaGenerall2.png" />
</p>

Y cuando se terminan de ver los productos disponibles, se muestra un icono de "**HOME**" que nos regresa a la página principal.


### Productos

Por último se hicieron los Mockups de los productos individuales donde se muestran según sean Telefonos, Tablets o en sus caso las Novedades más recientes y cuando se terminan de ver los productos disponibles según su tipo, se muestra un icono de "**HOME**" que nos regresa a la página principal.

#### Telefonos

<p align="center">
  <img src="docs/images/Mockups/Telefonos.png" />
</p>

#### Tablets

<p align="center">
  <img src="docs/images/Mockups/Tablets.png" />
</p>

#### Novedades

<p align="center">
  <img src="docs/images/Mockups/Novedades.png" />
</p>

## Diseño

  Se implemetará el siguiente diseño:

  * BODY:
    * Fuente: Droid Sans.

  * TITULOS:
    * Fuente: Tangerine.


  Usando de preferencia los colores:


<style type="text/css">


.primary-1 { background-color: #FF4848 }
.primary-2 { background-color: #FF1313 }
.primary-0 { background-color: #FF0000 }
.primary-3 { background-color: #E30000 }
.primary-4 { background-color: #B00000 }

.secondary-1-1 { background-color: #FFC548 }
.secondary-1-2 { background-color: #FFB413 }
.secondary-1-0 { background-color: #FFAE00 }
.secondary-1-3 { background-color: #E39B00 }
.secondary-1-4 { background-color: #B07800 }

.secondary-2-1 { background-color: #9D46D7 }
.secondary-2-2 { background-color: #8A1CD5 }
.secondary-2-0 { background-color: #8106D5 }
.secondary-2-3 { background-color: #5C0598 }
.secondary-2-4 { background-color: #480376 }

body {
	margin:0; padding: 2em;
	background: #fff;
	color: #000;
	font: 12px/1.33 "Segoe UI", "Helvetica Neue", Helvetica, sans-serif;
	text-align:left;
	}
h1 {
	margin: 0.5em 0;
	font-size: 200%;
	}
p {
	margin: 0.5em 0;
	}

.color-table {
	margin: 2em 2em 5em;
	border-collapse:collapse;
	border:none;
	border-spacing:0;
	font-size:100%;
	}
.color-table th {
	padding: 0 1em 0 0;
	text-align: right;
	vertical-align: middle;
	font-size: 100%;
	font-weight: normal;
	border: none;
	}
.color-table td.sample {
	width:6em; height:6em;
	padding: 10px;
	text-align:center;
	vertical-align:middle;
	font-size:90%;
	border: 1px solid white;
	white-space:nowrap;
	}
.color-table td.sample-0 {
	width:18em;
	}
.color-table.small td.sample {
	width:3em; height:3em;
	padding:0;
	border:none;
	}
.color-table.small td.sample-0 {
	width:9em;
	}
.color-table .white { margin-bottom:0.2em; color:white }
.color-table .black { margin-top:0.2em; color:black }

hr {
	margin: 2em 0 1em 0;
	border:none;
	border-bottom:1px solid silver;
	}
#footer {
	padding:1em;
	text-align:center;
	font-size:80%;
	}

</style>
  <table class="color-table">
  	<tr>
  		<th>Primary color:</th>
  		<td class="sample sample-1 primary-1">
  			<div class="white">#FF4848</div>
  			<div class="black">#FF4848</div>
  		</td>
  		<td class="sample sample-2 primary-2">
  			<div class="white">#FF1313</div>
  			<div class="black">#FF1313</div>
  		</td>
  		<td class="sample sample-0 primary-0">
  			<div class="white">#FF0000</div>
  			<div class="black">#FF0000</div>
  		</td>
  		<td class="sample sample-3 primary-3">
  			<div class="white">#E30000</div>
  			<div class="black">#E30000</div>
  		</td>
  		<td class="sample sample-4 primary-4">
  			<div class="white">#B00000</div>
  			<div class="black">#B00000</div>
  		</td>
  	</tr>
  	<tr>
  		<th>Secondary color (1):</th>
  		<td class="sample sample-1 secondary-1-1">
  			<div class="white">#FFC548</div>
  			<div class="black">#FFC548</div>
  		</td>
  		<td class="sample sample-2 secondary-1-2">
  			<div class="white">#FFB413</div>
  			<div class="black">#FFB413</div>
  		</td>
  		<td class="sample sample-0 secondary-1-0">
  			<div class="white">#FFAE00</div>
  			<div class="black">#FFAE00</div>
  		</td>
  		<td class="sample sample-3 secondary-1-3">
  			<div class="white">#E39B00</div>
  			<div class="black">#E39B00</div>
  		</td>
  		<td class="sample sample-4 secondary-1-4">
  			<div class="white">#B07800</div>
  			<div class="black">#B07800</div>
  		</td>
  	</tr>
  	<tr>
  		<th>Secondary color (2):</th>
  		<td class="sample sample-1 secondary-2-1">
  			<div class="white">#9D46D7</div>
  			<div class="black">#9D46D7</div>
  		</td>
  		<td class="sample sample-2 secondary-2-2">
  			<div class="white">#8A1CD5</div>
  			<div class="black">#8A1CD5</div>
  		</td>
  		<td class="sample sample-0 secondary-2-0">
  			<div class="white">#8106D5</div>
  			<div class="black">#8106D5</div>
  		</td>
  		<td class="sample sample-3 secondary-2-3">
  			<div class="white">#5C0598</div>
  			<div class="black">#5C0598</div>
  		</td>
  		<td class="sample sample-4 secondary-2-4">
  			<div class="white">#480376</div>
  			<div class="black">#480376</div>
  		</td>
  	</tr>
  </table>

  <table class="color-table small">
  	<tr>
  		<th>Primary color:</th>
  		<td class="sample sample-1 primary-1"></td>
  		<td class="sample sample-2 primary-2"></td>
  		<td class="sample sample-0 primary-0"></td>
  		<td class="sample sample-3 primary-3"></td>
  		<td class="sample sample-4 primary-4"></td>
  	</tr>
  	<tr>
  		<th>Secondary color (1):</th>
  		<td class="sample sample-1 secondary-1-1"></td>
  		<td class="sample sample-2 secondary-1-2"></td>
  		<td class="sample sample-0 secondary-1-0"></td>
  		<td class="sample sample-3 secondary-1-3"></td>
  		<td class="sample sample-4 secondary-1-4"></td>
  	</tr>
  	<tr>
  		<th>Secondary color (2):</th>
  		<td class="sample sample-1 secondary-2-1"></td>
  		<td class="sample sample-2 secondary-2-2"></td>
  		<td class="sample sample-0 secondary-2-0"></td>
  		<td class="sample sample-3 secondary-2-3"></td>
  		<td class="sample sample-4 secondary-2-4"></td>
  	</tr>
  </table>
