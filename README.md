<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sugiyanto | Website Pribadi</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Segoe UI, sans-serif;
}

body{
background:#ffffff;
color:#333;
}

/* Navbar */

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
box-shadow:0 2px 10px rgba(0,0,0,0.05);
position:sticky;
top:0;
background:white;
}

nav h2{
font-weight:600;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:20px;
}

nav ul li a{
text-decoration:none;
color:#333;
font-weight:500;
}

/* Hero */

.hero{
height:80vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
flex-direction:column;
padding:20px;
}

.hero h1{
font-size:48px;
margin-bottom:10px;
}

.hero p{
color:#666;
margin-bottom:25px;
}

.hero button{
padding:12px 25px;
border:none;
background:#111;
color:white;
border-radius:30px;
cursor:pointer;
font-size:16px;
}

/* Section */

.section{
padding:80px 10%;
}

.section h2{
text-align:center;
margin-bottom:40px;
font-size:32px;
}

/* Card */

.card-container{
display:flex;
justify-content:center;
gap:30px;
flex-wrap:wrap;
}

.card{
background:#fafafa;
padding:30px;
border-radius:12px;
max-width:300px;
box-shadow:0 5px 20px rgba(0,0,0,0.05);
text-align:center;
}

/* Footer */

footer{
text-align:center;
padding:30px;
background:#f5f5f5;
margin-top:40px;
color:#777;
}

</style>
</head>

<body>

<nav>
<h2>Sugiyanto</h2>
<ul>
<li><a href="#about">Tentang</a></li>
<li><a href="#hobi">Hobi</a></li>
<li><a href="#kontak">Kontak</a></li>
</ul>
</nav>

<section class="hero">
<h1>Halo, Saya Sugiyanto</h1>
<p>Karyawan Swasta & Pecinta Touring</p>
<button>Lihat Profil</button>
</section>

<section class="section" id="about">
<h2>Tentang Saya</h2>

<div class="card-container">

<div class="card">
<p>
Saya adalah seorang karyawan swasta yang memiliki ketertarikan
pada perjalanan dan petualangan. Saya menikmati perjalanan jauh
untuk mengeksplorasi tempat baru.
</p>
</div>

</div>

</section>

<section class="section" id="hobi">
<h2>Hobi</h2>

<div class="card-container">

<div class="card">
<h3>Touring</h3>
<p>
Touring adalah hobi yang membuat saya bisa menikmati perjalanan,
melihat pemandangan baru, dan merasakan kebebasan di jalan.
</p>
</div>

</div>

</section>

<section class="section" id="kontak">
<h2>Kontak</h2>

<div class="card-container">

<div class="card">
<p>Email : sugytozuro90@gmail.com</p>
</div>

</div>

</section>

<footer>
© 2026 Sugiyanto - Website Pribadi
</footer>

</body>
</html>
```
