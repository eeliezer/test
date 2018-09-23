# Programadores Web
Autores: Barneche Julieta, Espejo Eliezer, Kloster Matias
Materia: Práctica Profesionalizante 6
ISEC
Prof. Carlos Gorosito

## Lea Verou
[![lea verou][foto lea]][link a web]

[foto lea]: http://lea.verou.me/wp-content/uploads/2011/05/smiling.jpg
[link a web]: http://lea.verou.me/ "Pagina oficial de Lea Verou"

### ¿Quién es?
Lea Verou, nacida en Grecia en Junio 13 de 1986, es una programadora web Front end, escritra y Oradora.
Graduada de la Universidad de Economia y Negocios de Atenas y un Master de Ciencia en el MIT, se dedico en sus primera años como diseñadora grafica y a proyectos de desarrollo web, actualmente se encuentra trabajando como Ayudante de Investigación para el MIT CSAIL.
Tambien es una invitada experta en W3C CSS Working Group.

### ¿En qué lenguajes se especializa o cuál prefiere?
Se especializa en CSS, HTML y JavaScript.

### ¿Escribió libros? ¿Cuáles?
Es autora del libro CSS Secrets: Better Solutions to Everyday Web Design Problems.

### ¿Tiene experimentos?
Ha participado en varios proyectos como: Prism, The CSS3 Test, entre otros.

### ¿Dio conferencias o enseñó ante un público?
Si ha realizado conferencias en mas de 100 oportunidades alrededor del mundo.

### ¿Tiene un sitio web u otro contacto? Por ejemplo, ¿Tiene una cuenta de Twitter oficial?
Pagina oficial: [Pagina oficial de Lea Verou](http://lea.verou.me "Pagina oficial de Lea Verou")
Twitter: [Twitter de Lea Verou](https://twitter.com/leaverou "Twitter oficial de Lea Verou")

### Citar un ejemplo de código, una librería, y cómo se implementa la misma.
Código para Celda Responsive con element().
CSS:
```css
 /**
 * Responsive tables with element()
 * Pros: No markup changes, works with normal table markup, no content duplication
 * Cons: element() is only implemented in Firefox :(
 */

@media (max-width: 600px) {
	table, tr, td, th, thead, tbody {
		display: block;
	}

	thead {
		float: left;
	}

		tbody tr {
			margin: .2em 0;
			padding-left: 4em;
		}
		
		tr:not(:first-child) {
			background: -moz-element(#header) no-repeat;
			background: element(#header) no-repeat;
		}

		th {
			text-align: left;
		}
		
		td:not(:first-child) {
			border-top: none;
		}
}

/* Just styling after this */
body {
	font: 150%/1.6 Helvetica Neue, sans-serif;
}

table {
	border-spacing: 0;
	border-collapse: collapse;
}

	td, th {
		padding: 0 .3em;
		white-space: nowrap;
	}

	td {
		border: 1px solid rgba(0,0,0,.1);
	}
<!-- HTML -->
<table>
	<thead id="header">
		<tr><th>Name</th>
		<th>Age</th>
		<th>Color</th>
		<th>Sex</th>
		<th>Alive?</th>
	</tr></thead>
	<tbody>
		<tr>
			<td>Adam Catlace</td>
			<td>4</td>
			<td>White &amp; Orange</td>
			<td>Male</td>
			<td>Y</td>
		</tr>
		<tr>
			<td>Vector</td>
			<td>12</td>
			<td>Blue</td>
			<td>Male</td>
			<td>N</td>
		</tr>
		<tr>
			<td>Çiki</td>
			<td>1</td>
			<td>Gray</td>
			<td>Female</td>
			<td>Y</td>
		</tr>
	</tbody>
</table>
```

## Sarah Drasner
[![lea verou][foto sara]][link a web sara]

[foto sara]: https://i.ytimg.com/vi/QNfKyEsfeAU/maxresdefault.jpg
[link a web sara]: https://sarahdrasnerdesign.com/ "Sara Drasner"
### ¿Quién es?
Sarah Drasner es Desarrolladora Senior en Microsoft, ganadora de premios por sus discursos y forma parte del staff de escritores en CSS-Tricks. También es co-fundadora de Web Animation Workshops, junto a Val Head. Anteriormente se desempeñó como Gerente de Diseño e Ingeniería de UX en Trulia (Zillow). Además ganó premios, como el "Best of the Best Award" de CSS Dev Conf y el "Best Code Wrangler" de CSS Design Awards. Trabajó durante 15 años como diseñadora y diseñadora web, y en trabajó como ilustradora científica y profesora de pregrado.
### ¿En qué lenguajes se especializa o cuál prefiere?
Se especializa en CSS y ha ganado premios por su trabajo en este lenguaje. Además se especializa en SVG, Gráficos vectoriales escalables, un formato de gráficos vectoriales bidimensionales, tanto estáticos como animados, en formato XML, cuya especificación es un estándar abierto desarrollado por el W3C desde el año 1999.

Además escribe artículos asiduamente en la web [https://css-tricks.com](https://css-tricks.com)
### ¿Escribió libros? ¿Cuáles?
Escribió el libro “SVG Animations: From Common UX Implementations to Complex Responsive Animation”, de la editorial O'Reilly Media, que está principalmente enfocada a libros de tecnología e informática.**
### ¿Tiene experimentos?
https://codepen.io/sdras/pen/YZBGNp

### ¿Dio conferencias o enseñó ante un público?
Da conferencias, cursos y workshops de Frontend Masters en Vue.js (disponibles en [https://frontendmasters.com/courses/](https://frontendmasters.com/courses/)) y Advanced SVG Animations (disponibles en [https://frontendmasters.com/courses/svg-animation/](https://frontendmasters.com/courses/svg-animation/) )
### ¿Tiene un sitio web u otro contacto? Por ejemplo, ¿Tiene una      cuenta de Twitter oficial?
Su sitio web es [https://sarahdrasnerdesign.com/](https://sarahdrasnerdesign.com/)

Su cuenta de Twitter es: [https://twitter.com/sarah_edo](https://twitter.com/sarah_edo)

Su cuenta en codepen: [https://codepen.io/sdras/#](https://codepen.io/sdras/#)

Su cuenta en gitbuh: [https://github.com/sdras](https://github.com/sdras)
### Citar un ejemplo de código, una librería, y cómo se implementa la misma.
```
Al trabajar con svg se hace muy extenso el codigo
https://codepen.io/sdras/pen/YZBGNp  
```

## Hakim El Hattab
### ¿Quién es?
[![el][foto hak]][link a web hak]

[foto hak]: https://www.html5rocks.com/static/images/profiles/hakimelhattab.png
[link a web hak]: https://hakim.se/ "Hakim El Hattab"

Hakim El Hattab es sueco, diseñador de interfaz y desarrollador front-end. Co-fundó Slides++, una web para hacer presentaciones, donde se pueden crear, presentar y compartir diapositivas. Su trabajo consiste en combinar bibliotecas de interfaz, animaciones y juegos minimalistas. Además muchos de sus proyectos son open source, por lo que pueden ser descargados y modificados.

### ¿En qué lenguajes se especializa o cuál prefiere?
La plataforma que creó, “Slides”, está basada en reveal.js - un framework HTML de código abierto que lanzó en 2011 y que sigue perfeccionando.  
Trabaja más que nada con HTML, CSS y Javascript.

### ¿Escribió libros? ¿Cuáles?
No escribió libros pero colabora en páginas web sobre programación. 
Por ejemplo: [https://www.html5rocks.com/es/tutorials/casestudies/20things_pageflip/](https://www.html5rocks.com/es/tutorials/casestudies/20things_pageflip/)

### ¿Tiene experimentos?
Hace experimentos visuales con JS/CSS y deja los proyectos para descargar con código abierto en su página web [https://hakim.se/](https://hakim.se/)

Ejemplo: Juego de checks: [https://lab.hakim.se/checkwave/](https://lab.hakim.se/checkwave/)

### ¿Dio conferencias o enseñó ante un público?
Dio conferencias y talleres frente a público. Una de ellas está disponible en Youtube:

[![JavaScript: Understanding the Weird Parts - The First 3.5 Hours]()](https://www.youtube.com/watch?v=Bv_5Zv5c-Ts "Conferencia")


### ¿Tiene un sitio web u otro contacto? Por ejemplo, ¿Tiene una cuenta de Twitter oficial?

Su sitio web es [https://hakim.se/](https://hakim.se/)
Su cuenta de Twitter es: [https://twitter.com/hakimel](https://twitter.com/hakimel)
Su cuenta en codepen: [https://codepen.io/hakimel](https://codepen.io/hakimel)
Su cuenta en gitbuh: [https://github.com/hakimel](https://github.com/hakimel)

### Citar un ejemplo de código, una librería, y cómo se implementa la misma.

[https://codepen.io/hakimel/pen/CxliK](https://codepen.io/hakimel/pen/CxliK)

[https://github.com/hakimel/Avgrund](https://github.com/hakimel/Avgrund)


## Sara Soueidan
[![Sara Soueidan][el]][link a web soueidan]

[el]:https://static1.squarespace.com/static/55677e68e4b0f08b0b268c57/t/58029a79f7e0ab48cf35fae8/1476565665289/Net+Awards+Developer+Of+The+Year+Sara+Soueidan+Freelance+Story
[link a web soueidan]: https://www.sarasoueidan.com/ "Sara Soueidan"

### ¿Quién es?
Sara Soueidan es una desarrolladora front-end UI / UX, capacitadora, autora y ponente con sede en Líbano, trabajando con empresas de todo el mundo. Asociada con equipos de diseño para ejecutar y construir interfaces de usuario web y sistemas de diseño progresivos y hermosos, con un fuerte enfoque en el diseño receptivo, el rendimiento y la accesibilidad, utilizando las últimas técnicas de diseño de front-end.

### ¿En qué lenguajes se especializa o cuál prefiere?

JavaScript, HTML, CSS y SVG.

### ¿Escribió libros? ¿Cuáles?
Smashing Book 5: Real-Life Responsive Web Design , tambien escribe un blog y realiza entrenamientos y Workshops acerca de front end y desarrollo en gral.

### ¿Tiene experimentos?
https://codepen.io/SaraSoueidan/pen/poDuw
https://codepen.io/SaraSoueidan/pen/rtcom

### ¿Dio conferencias o enseñó ante un público?
https://www.youtube.com/watch?v=qBRiSwAYbV4    
https://www.youtube.com/watch?v=NkLDuPf5P0A

### ¿Tiene un sitio web u otro contacto? Por ejemplo, ¿Tiene una cuenta de Twitter oficial?
https://www.sarasoueidan.com/
https://twitter.com/sarasoueidan/

### Citar un ejemplo de código, una librería, y cómo se implementa la misma.
Html
```
<div class="wrapper-1">
<ul id="nav">
<li><b class="icon-home"></b></li>
<li><b class="icon-picture"></b></li>
<li class="active"><b class="icon-facetime-video"></b></li>
<li><b class="icon-headphones"></b></li>
<li><b class="icon-user"></b></li>
</ul>
</div>

<div class="wrapper-2">
<ul id="nav">
  <li class="active"><b class="icon-home"></b></li>
<li><b class="icon-picture"></b></li>
<li><b class="icon-facetime-video"></b></li>
<li><b class="icon-headphones"></b></li>
<li><b class="icon-user"></b></li>
</ul>
</div>


Css
*{
  border:0; 
  margin:0 ; 
  padding:0; 
  list-style-type:none; 
  outline:none;
}
ul{
  margin:0 !important;
}
html,body{
  height:100%;
}
body{
  background-color:rgb(74, 74, 74);
  background: url("http://subtlepatterns.subtlepatterns.netdna-cdn.com/patterns/noisy_net.png") repeat scroll center center rgb(74, 74, 74);
}
.wrapper-1, .wrapper-2{
  margin:50px auto;
  width:412px;
  background:linear-gradient(#3D4246,#24282B);
  height:60px;
  border-radius:4px;
  border-top:1px solid #53575C;
  border-left:1px solid #53575C;
  box-shadow:
  1px 1px #17191C,
  0 0 10px #323338;
	padding:8px;
  padding-bottom:12px;
}
ul{
width:410px; 
height:100%; 
border:1px solid #0F1014;
border-radius:3px;
background:#0F1014;
}
ul li {
float:left;
width:80px;
height:100%;
color:#D9D9D9;
text-align:center;
text-shadow:0 1px #0F1014;
display:table;
background: linear-gradient(#44494F,#2F3237);
border-radius:3px;
border-right:1px solid #0F1014;
border-bottom:1px solid #0F1014;
border-top:1px solid #53575C;
border-left:1px solid #53575C;
box-shadow:1px 1px #17191C;
cursor:pointer;
}

ul li b{
  margin-top:20px;
  font-size:24px;
 }
ul li:active, ul li.active{
	color:#171820;
	background:#2A2D31;
	box-shadow:
      inset 0 0 5px 2px rgba(15, 16, 20, 0.5);
	border:1px solid #0F1014;
}
  ul li:not(.active):hover{
  text-shadow:1px 1px 10px Yellow;
  }
 
  .wrapper-2 ul li:not(.active):hover{
  text-shadow:1px 1px 10px HotPink;
  }
   ul li:active{
    text-shadow:none !important;
  }
  .wrapper-2 ul li {
    color:#0F1014; 
    text-shadow:0 1px #666;
  }
  .wrapper-2 ul li:active,
  .wrapper-2 ul li.active {
    color:grey;
  } 
```

## Referencias Bibliográficas
http://lea.verou.me/about/
https://en.wikipedia.org/wiki/Lea_Verou
https://sarahdrasnerdesign.com/
https://hakim.se/
https://www.sarasoueidan.com/

## Glosario

**CSS:** es un lenguaje que define la apariencia de un documento escrito en un lenguaje de marcado (por ejemplo, HTML).

**SVG:** Gráficos vectoriales escalables, o Gráficos vectoriales redimensionables o SVG es un formato de gráficos vectoriales bidimensionales, tanto estáticos como animados, en formato XML

**XML:** XML, siglas en inglés de eXtensible Markup Language, traducido como "Lenguaje de Marcado Extensible" o "Lenguaje de Marcas Extensible", es un meta-lenguaje que permite definir lenguajes de marcas desarrollado por el World Wide Web Consortium utilizado para almacenar datos en forma legible.

**JavaScript:** es un lenguaje de programación interpretado, dialecto del estándar ECMAScript. Se define como orientado a objetos, ​ basado en prototipos, imperativo, débilmente tipado y dinámico.

**CSS-TRICK:** trucos y consejos para desarrolladores front-end.

**REVEAL.JS:** Reveal.js es un framework desarrollado en Javascript, que se utiliza para la creación de presentaciones utilizando HTML.

**RESPONSIVE WEB DESIGN:** El diseño web adaptable, es una filosofía de diseño y desarrollo cuyo objetivo es adaptar la apariencia de las páginas web al dispositivo que se esté utilizando para visitarlas.

**HTML:** HTML, sigla en inglés de HyperText Markup Language, hace referencia al lenguaje de marcado para la elaboración de páginas web.

**W3C:** El Consorcio WWW, en inglés: World Wide Web Consortium, es un consorcio internacional que genera recomendaciones y estándares que aseguran el crecimiento de la World Wide Web a largo plazo.​

**W3C CSS Working Group:** es un grupo de trabajo creado por el World Wide Web Consortium (W3C) en 1997, para abordar problemas que no se habían abordado con el nivel 1 de CSS. El número de miembros alcanzó 125 en abril de 2017.

**MIT CSAIL:** El MIT Computer Science and Artificial Intelligence Laboratory es un laboratorio de investigación en el Instituto Tecnológico de Massachusetts formado por la fusión, en el año 2003, del Laboratory for Computer Science y el Artificial Intelligence Laboratory.

**Prism:** Prism es una sintaxis ligera, extensible, resaltador, construida con los estándares modernos en mente. Se usa en miles de sitios web, incluidos algunos de los que visita a diario. https://prismjs.com/.

**The CSS3 Test:** Puntua al navegador segun su nivel de compatibilidad con CSS3.

**CSS Dev Conf:** CSS Dev Conf es el lugar para aprender nuevas técnicas, ya sea que necesites mejorar el flujo de trabajo diario o aprender las últimas especificaciones.

**CSS Design Awards:** Una plataforma de premios de diseño y desarrollo web para gente digital, personas que miran UI / UX y líderes inspiradores de la web.

**Front-end:** hace referencia a la visualización que tiene el usuario mediante el navegador.

**UX:** por sus siglas en inglés User eXperience o en español Experiencia de Usuario, es aquello que una persona percibe al interactuar con un producto o servicio.

**UI:** interfaz del Usuario es con lo que se interactúa directamente.

**Framework:** se refiere a una estructura software compuesta de componentes personalizables e intercambiables para el desarrollo de una aplicación.

**Open Source:** El código abierto es un modelo de desarrollo de software basado en la colaboración abierta.​ Se enfoca más en los beneficios prácticos que en cuestiones éticas o de libertad que tanto se destacan en el software libre.​