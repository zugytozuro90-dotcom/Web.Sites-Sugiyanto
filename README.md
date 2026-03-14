<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Profil Sugiyanto</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:linear-gradient(135deg,#3a7bd5,#00d2ff);
color:#333;
}

/* NAVBAR */

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:white;
box-shadow:0 5px 20px rgba(0,0,0,0.1);
position:sticky;
top:0;
z-index:100;
}

nav h2{
color:#3a7bd5;
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

/* HERO */

.hero{
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
height:90vh;
color:white;
padding:20px;
}

.hero img{
width:160px;
height:160px;
border-radius:50%;
border:5px solid white;
margin-bottom:20px;
animation:float 3s infinite ease-in-out;
}

@keyframes float{
0%{transform:translateY(0);}
50%{transform:translateY(-10px);}
100%{transform:translateY(0);}
}

.hero h1{
font-size:42px;
margin-bottom:10px;
}

.hero p{
font-size:18px;
opacity:0.9;
}

/* SECTION */

.section{
padding:80px 10%;
background:white;
}

.section h2{
text-align:center;
margin-bottom:40px;
font-size:32px;
color:#3a7bd5;
}

/* CARD */

.card-container{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:30px;
}

.card{
background:#f8f8f8;
padding:25px;
border-radius:12px;
width:280px;
box-shadow:0 10px 25px rgba(0,0,0,0.1);
transition:0.3s;
}

.card:hover{
transform:translateY(-10px);
}

/* BUTTON */

.btn{
display:inline-block;
margin-top:15px;
padding:10px 20px;
background:#3a7bd5;
color:white;
text-decoration:none;
border-radius:25px;
font-size:14px;
}

/* FOOTER */

footer{
text-align:center;
padding:30px;
background:#222;
color:white;
}

/* RESPONSIVE */

@media(max-width:768px){

.hero h1{
font-size:30px;
}

.card{
width:100%;
}

nav{
flex-direction:column;
}

nav ul{
margin-top:10px;
}

}

</style>
</head>

<body>

<nav>
<h2>SUGIYANTO</h2>
<ul>
<li><a href="#about">Tentang</a></li>
<li><a href="#biodata">Biodata</a></li>
<li><a href="#contact">Kontak</a></li>
</ul>
</nav>

<section class="hero">

<img src="https://i.imgur.com/4Z7K6Kk.png">

<h1>Sugiyanto</h1>
<p>Karyawan Swasta | Pecinta Touring Motor</p>

</section>

<section class="section" id="about">

<h2>Tentang Saya</h2>

<div class="card-container">

<div class="card">
<p>
Halo! Saya Sugiyanto, biasa dipanggil Sugi.
Saya bekerja sebagai karyawan swasta dan memiliki hobi
touring motor untuk menikmati perjalanan dan menjelajahi
tempat-tempat baru.
</p>
</div>

<div class="card">
<p>
Website ini dibuat sebagai profil pribadi yang berisi
informasi singkat tentang diri saya, biodata, serta
kontak yang dapat dihubungi.
</p>
</div>

</div>

</section>

<section class="section" id="biodata">

<h2>Biodata</h2>

<div class="card-container">

<div class="card">
<strong>Nama</strong>
<p>Sugiyanto</p>
</div>

<div class="card">
<strong>Panggilan</strong>
<p>Sugi</p>
</div>

<div class="card">
<strong>Profesi</strong>
<p>Karyawan Swasta</p>
</div>

<div class="card">
<strong>Tempat, Tanggal Lahir</strong>
<p>Sukoharjo, 03 Agustus 1989</p>
</div>

<div class="card">
<strong>Hobi</strong>
<p>Touring Motor</p>
</div>

<div class="card">
<strong>Alamat</strong>
<p>Karangasem RT 02/04, Kel. Gumpang,
Kec. Kartasura, Kab. Sukoharjo,
Jawa Tengah</p>
</div>

</div>

</section>

<section class="section" id="contact">

<h2>Kontak</h2>

<div class="card-container">

<div class="card">
<p>Email</p>
<a class="btn" href="mailto:zugytozuro90@gmail.com">
Kirim Email
</a>
</div>

<div class="card">
<p>Telepon</p>
<a class="btn" href="tel:+6285724000073">
Hubungi Saya
</a>
</div>

</div>

</section>

<footer>
© 2026 Website Profil Sugiyanto
</footer>

</body>
</html>

