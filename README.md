
<html>
<head>
 <title>web page notpad </title>

<style>
/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}







body{
text-align:center;
}

.header{
display:flex;
justify-content:center;
align-items:center;
}

.navbar {
display: flex;
align-items:center;
justify-content:center;

}

.list-saucers {
display: flex;
align-items: center;
justify-content:center;
}

.list-saucers figure {
display:flex;
justify-content:center;
align-items:center;
flex-flow:column;

}

.header {
height: 450px;
background: url(header.jpg) no-repeat center top ;
background-size:cover;
}

.navbar {
height: 63px;
background: #212121;
border-bottom: 1px dashed #d6e199;
}

.navbar a {
padding: 0 20px;
color:#fff;
text-decoration:none;
text-transform: uppercase;
font:20px;
}

.title {
margin-bottom: 40px;
font: 60px;
text-transform: uppercase;
}

p {
margin-bottom: 40px;
}

.btn {
display: inline-block;
padding:10px 40px;
border:2px solid #fff;
color:#fff;
text-decoration:none;
}

.content {
padding:80px 0;
}

.abo {
background:#ff9000;
color:#fff;
}

.abo p {
max-width: 1055px;
margin: 0 auto;
}

.saucers {
background: #3d3f36;
color:#fff;
}

.price {
background:url(imagen23.jpg) no-repeat center top;
color:#fff;
text-aling:left;
background-size:cover;
}

.contain {
max-width: 1055px;
margin:0 auto;
}

.price p {
max-width: 450px;
}

.contact{
background:#3d3f36;
color:#fff;
padding-bottom:0;
}

.contact.map img {
max-width:100%
height:100%
}

.list-saucers figure {
position:relative;
width:100px;
height:100px;
}

.list-saucers figure:after{
content:""
position:absolute;
left:0;
top:0;
z-index:0;
background:#fff9000;
border-radius:50%;
width:100%
heigth:100%
}

.list-saucers img{
position: relative;
z-index:1;
}

.list-saucers li {
padding: 0 30px;
}

.list-saucers figcaption {
position: absolute;
left:0;
right:0;
bottom:-40px;
}

</style>


</head>
<body>



<header class="header">

</header>


<nav class="navbar">
 
  <li><a href="">Inicio</a></li>
  <li><a href="pagina 1.html">Comidas</a></li>
  <li><a href="pagina2.html">Bebidas</a></li>
  <li><a href="pagina3.html">Postres</a></li>
  <li><a href="pagina4-.html">Pasteles</a></li>
</nav>

<section class="content abo">
  <FONT FACE="impact" SIZE=8 >
  <h2 class="title">Bienvenidos a "MORE FIT"</h2>
 </FONT>
  <br>En More Fit encontraras comidas de ensueño y sobre todo que son saludables</p>
  <br>Disgustaras de muchas variedades de sabores y colores
  <br>Vivir saludable tambien es increible con las opciones que te podemos ofrecer</p>
</section>
 
<section class="content saucers">
  <h2 class="title"Saurcers</h2>
  <p>Hemos implementado una variedad de productos para el deleite de nuestros clientes!</p>
  <p>Tu casa More fit te ofrece:

<ul class="list-saucers"

  <li>
  <figure>
    <img src="imagen2.png"width="100"/>
    <figcaption>Bebidas</figcaption>

<li><a href="pagina 7.html">Bebidas</a></li>
  </figure>
 </li>

 <li>
  <figure>
    <img src="imagen2.png"width="100" height="100" />
    <figcaption>Comidas</figcaption>
<li><a href="pagina 6.html">Comidas</a></li>
  </figure>
  </li>

  <li>
   <figure>
    <img src="imagen2.png"width="100" height="100" />
     <figcaption>Pasteles</figcaption>
<li><a href="pagina8.html">Pasteles</a></li>
  </figure>
 </li>
</ul>
</section>

<section class="content price"
  <article class= "contain">
<FONT FACE="impact" SIZE=4 COLOR: white>
  <li><a href="pagina5.html">Precio</a>
</FONT>
 </article>
</section>

<section class="content contact">
  <h2 class="title">Contacto</h2>
  <p>Nos puedes encontrar en la siguiente direccion:</p>
  <figure class="map"><img src="mapa.png"></figure>
</section>

</body>
</html>
