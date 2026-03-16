<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>EcoGrow</title>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>

body{
margin:0;
font-family:Arial;
background:#f6f3ef;
text-align:center;
}

/* BARRA SUPERIOR */

nav{
background:#7a4b2a;
padding:8px 20px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo-area{
display:flex;
align-items:center;
gap:10px;
}

.logo{
width:40px;
}

.logo-text{
color:white;
font-size:22px;
font-style:italic;
font-weight:bold;
}

.menu a{
color:white;
margin:10px;
font-size:15px;
text-decoration:none;
font-weight:bold;
}

.icons{
color:white;
font-size:18px;
}

.icons i{
margin-left:15px;
cursor:pointer;
}

/* HERO */

.hero{
background-image:url("macetas.png");
background-size:cover;
background-position:center;
height:90vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
color:white;
text-shadow:2px 2px 10px rgba(0,0,0,0.6);
}

.hero h1{
font-size:60px;
font-style:italic;
margin:10px;
}

.hero p{
font-size:25px;
}

/* PRODUCTOS */

.productos{
padding:60px;
}

.productos h2{
font-size:35px;
color:#5a3e2b;
}

.grid{
display:flex;
justify-content:center;
flex-wrap:wrap;
gap:30px;
margin-top:40px;
}

.card{
background:white;
width:250px;
padding:20px;
border-radius:15px;
box-shadow:0 10px 20px rgba(0,0,0,0.1);
}

.card img{
width:200px;
border-radius:10px;
}

.card h3{
color:#5a3e2b;
}

/* VENTAS */

.ventas{
padding:60px;
background:#f2ede6;
}

.ventas h2{
font-size:35px;
color:#5a3e2b;
}

.precio{
font-size:22px;
font-weight:bold;
color:#7a4b2a;
}

button{
background:#7a4b2a;
color:white;
border:none;
padding:10px 20px;
border-radius:8px;
cursor:pointer;
margin-top:10px;
}

button:hover{
background:#5c3620;
}

/* REDES SOCIALES */

.redes{
padding:40px;
background:#e8e2d9;
}

.redes h2{
color:#5a3e2b;
}

.redes a{
font-size:35px;
margin:20px;
color:#7a4b2a;
text-decoration:none;
}

.redes a:hover{
color:#5c3620;
}

/* FOOTER */

footer{
background:#7a4b2a;
color:white;
padding:20px;
margin-top:20px;
}

</style>
</head>

<body>

<nav>

<div class="logo-area">
<img src="logo.png" class="logo">
<span class="logo-text">EcoGrow</span>
</div>

<div class="menu">
<a href="#">Inicio</a>
<a href="#">Nosotros</a>
<a href="#">Macetas</a>
<a href="#">Galería</a>
<a href="#">Contacto</a>
</div>

<div class="icons">
<i class="fa-solid fa-magnifying-glass"></i>
<i class="fa-solid fa-cart-shopping"></i>
</div>

</nav>

<section class="hero">

<p>BIENVENIDOS</p>

<h1>EcoGrow</h1>

<p>De la cascara a la Vida</p>

</section>

<section class="productos">

<h2>Nuestras Macetas</h2>

<div class="grid">

<div class="card">
<img src="maceta1.png">
<h3>Maceta EcoGrow</h3>
<p>Hecha con cáscaras de frutas.</p>
</div>

<div class="card">
<img src="maceta2.png">
<h3>Maceta Natural</h3>
<p>100% biodegradable.</p>
</div>

<div class="card">
<img src="maceta3.png">
<h3>Maceta Plant</h3>
<p>Ideal para plantas pequeñas.</p>
</div>

</div>

</section>

<section class="ventas">

<h2>Macetas en Venta</h2>

<div class="grid">

<div class="card">
<img src="maceta1.png">
<h3>Maceta EcoGrow</h3>
<p>Maceta biodegradable hecha con cáscaras de frutas.</p>
<p class="precio">$50</p>
<button>Agregar al carrito</button>
</div>

<div class="card">
<img src="maceta2.png">
<h3>Maceta Natural</h3>
<p>Perfecta para plantas pequeñas.</p>
<p class="precio">$45</p>
<button>Agregar al carrito</button>
</div>

<div class="card">
<img src="maceta3.png">
<h3>Maceta Plant</h3>
<p>100% ecológica y sustentable.</p>
<p class="precio">$55</p>
<button>Agregar al carrito</button>
</div>

</div>

</section>

<section class="redes">

<h2>Síguenos</h2>

<a href="https://www.instagram.com/ecogrow.mx?igsh=MXBicnRhcmhvZTFwbA==" target="_blank">
<i class="fa-brands fa-instagram"></i>
</a>

<a href="#">
<i class="fa-brands fa-facebook"></i>
</a>

</section>

<footer>

<p>© 2026 EcoGrow | Cuidando el planeta</p>

</footer>

</body>
</html>
