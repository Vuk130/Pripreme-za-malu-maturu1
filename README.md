<!DOCTYPE html>
<html lang="sr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Pripreme Učionica | Pripreme za prijemni na Novom Beogradu</title>

<meta name="description" content="Pripreme Učionica – profesionalne pripreme za prijemni na Novom Beogradu, Blok 70. Srpski jezik, matematika i izborni predmeti. Časovi traju 90 minuta i održavaju se i vikendom.">
<meta name="keywords" content="Pripreme Učionica, pripreme za prijemni, Novi Beograd, Blok 70, matematika, srpski jezik, izborni predmeti">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:Arial,Helvetica,sans-serif;
    background:#f3f7ff;
    color:#111827;
    line-height:1.6;
}

a{
    text-decoration:none;
}

.container{
    width:min(1150px,92%);
    margin:auto;
}

/* HEADER */

header{
    position:sticky;
    top:0;
    z-index:999;
    background:rgba(255,255,255,.92);
    backdrop-filter:blur(15px);
    border-bottom:1px solid #dce5f5;
}

.nav{
    min-height:76px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:25px;
}

.logo{
    font-size:23px;
    font-weight:900;
    color:#1455d9;
}

.logo span{
    color:#111827;
}

nav{
    display:flex;
    gap:26px;
}

nav a{
    color:#4b5870;
    font-size:14px;
    font-weight:700;
    transition:.2s;
}

nav a:hover{
    color:#1455d9;
}

.btn{
    display:inline-flex;
    justify-content:center;
    align-items:center;
    padding:14px 22px;
    border-radius:13px;
    font-weight:800;
    transition:.25s;
}

.btn-primary{
    background:#1455d9;
    color:white;
    box-shadow:0 10px 25px rgba(20,85,217,.25);
}

.btn-primary:hover{
    transform:translateY(-3px);
    box-shadow:0 16px 35px rgba(20,85,217,.32);
}

.btn-white{
    background:white;
    color:#1455d9;
}

/* HERO */

.hero{
    min-height:720px;
    display:flex;
    align-items:center;
    background:
        radial-gradient(circle at 85% 15%,rgba(54,121,255,.45),transparent 28%),
        radial-gradient(circle at 10% 90%,rgba(72,203,255,.28),transparent 30%),
        linear-gradient(135deg,#071a3a,#103c87 55%,#1677d2);
    color:white;
    overflow:hidden;
}

.hero-grid{
    display:grid;
    grid-template-columns:1.1fr .9fr;
    gap:65px;
    align-items:center;
}

.badge{
    display:inline-block;
    background:rgba(255,255,255,.13);
    border:1px solid rgba(255,255,255,.25);
    padding:9px 15px;
    border-radius:50px;
    font-size:13px;
    font-weight:800;
    margin-bottom:22px;
}

.hero h1{
    font-size:clamp(43px,6vw,72px);
    line-height:1.02;
    letter-spacing:-3px;
    margin-bottom:25px;
}

.hero h1 span{
    color:#63d8ff;
}

.hero-text{
    font-size:18px;
    color:#dceaff;
    max-width:650px;
    margin-bottom:32px;
}

.actions{
    display:flex;
    gap:13px;
    flex-wrap:wrap;
}

.hero-card{
    background:rgba(255,255,255,.1);
    border:1px solid rgba(255,255,255,.2);
    backdrop-filter:blur(15px);
    border-radius:28px;
    padding:30px;
    box-shadow:0 25px 70px rgba(0,0,0,.2);
}

.hero-card h3{
    font-size:25px;
    margin-bottom:20px;
}

.quick{
    display:flex;
    align-items:center;
    gap:15px;
    padding:16px 0;
    border-bottom:1px solid rgba(255,255,255,.15);
}

.quick:last-child{
    border-bottom:0;
}

.quick-icon{
    width:45px;
    height:45px;
    display:grid;
    place-items:center;
    border-radius:13px;
    background:#63d8ff;
    color:#092052;
    font-weight:900;
}

.quick strong{
    display:block;
}

.quick small{
    color:#c8d9f4;
}

/* SECTIONS */

section{
    padding:95px 0;
}

.section-head{
    max-width:720px;
    margin-bottom:48px;
}

.center{
    text-align:center;
    margin-left:auto;
    margin-right:auto;
}

.label{
    color:#1455d9;
    text-transform:uppercase;
    font-size:13px;
    font-weight:900;
    letter-spacing:1.5px;
    margin-bottom:12px;
}

h2{
    font-size:clamp(34px,5vw,52px);
    line-height:1.08;
    letter-spacing:-1.8px;
    margin-bottom:17px;
}

.section-head p{
    color:#637089;
    font-size:17px;
}

/* SUBJECTS */

.subjects{
    background:white;
}

.cards{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:22px;
}

.card{
    background:#f8faff;
    border:1px solid #dce6f5;
    border-radius:22px;
    padding:30px;
    transition:.25s;
}

.card:hover{
    transform:translateY(-7px);
    border-color:#a9c6ff;
    box-shadow:0 20px 45px rgba(20,85,217,.1);
}

.card-icon{
    width:58px;
    height:58px;
    display:grid;
    place-items:center;
    border-radius:16px;
    background:linear-gradient(135deg,#1455d9,#4dbfff);
    color:white;
    font-size:23px;
    font-weight:900;
    margin-bottom:21px;
}

.card h3{
    font-size:23px;
    margin-bottom:10px;
}

.card p{
    color:#68758c;
}

/* WHY */

.why{
    background:#eef5ff;
}

.why-grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:20px;
}

.why-card{
    background:white;
    border-radius:20px;
    padding:27px;
    border:1px solid #dbe6f7;
}

.why-card strong{
    display:block;
    font-size:20px;
    margin-bottom:7px;
}

.why-card p{
    color:#68758c;
}

/* TEACHERS */

.teachers{
    background:white;
}

.teacher-grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:25px;
}

.teacher{
    padding:30px;
    border-radius:23px;
    background:linear-gradient(145deg,#f7faff,#edf5ff);
    border:1px solid #d8e5f8;
}

.avatar{
    width:70px;
    height:70px;
    border-radius:50%;
    display:grid;
    place-items:center;
    background:linear-gradient(135deg,#1455d9,#52cfff);
    color:white;
    font-size:21px;
    font-weight:900;
    margin-bottom:20px;
}

.teacher h3{
    font-size:25px;
    margin-bottom:4px;
}

.subject-name{
    color:#1455d9;
    font-weight:800;
    margin-bottom:14px;
}

.teacher p{
    color:#68758c;
}

/* TESTS */

.tests{
    background:
        radial-gradient(circle at 80% 20%,rgba(73,161,255,.22),transparent 30%),
        #071a3a;
    color:white;
}

.tests .label{
    color:#63d8ff;
}

.tests .section-head p{
    color:#b8cae5;
}

.test-grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:22px;
}

.test-card{
    padding:30px;
    background:#10284f;
    border:1px solid #294b7d;
    border-radius:22px;
}

.test-card h3{
    font-size:24px;
    margin-bottom:12px;
}

.test-card p{
    color:#b9cbe5;
}

/* SCHEDULE */

.schedule{
    background:#f5f8ff;
}

.schedule-grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:20px;
}

.schedule-card{
    background:white;
    padding:28px;
    border-radius:20px;
    border:1px solid #dce6f5;
}

.schedule-card .big{
    color:#1455d9;
    font-size:24px;
    font-weight:900;
    margin:7px 0;
}

.schedule-card p{
    color:#68758c;
}

/* LOCATION */

.location{
    background:linear-gradient(135deg,#dceaff,#f3fbff);
}

.location-grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:30px;
    align-items:center;
}

.location h2{
    max-width:550px;
}

.location-text{
    color:#627089;
    font-size:17px;
    margin-bottom:27px;
}

.location-box{
    background:white;
    border-radius:25px;
    padding:35px;
    box-shadow:0 20px 55px rgba(20,85,217,.12);
}

.location-box h3{
    font-size:27px;
    margin-bottom:7px;
}

.location-box p{
    color:#68758c;
    margin-bottom:20px;
}

.phone{
    color:#1455d9;
    font-size:29px;
    font-weight:900;
    margin-bottom:20px;
}

/* CONTACT */

.contact{
    text-align:center;
    background:linear-gradient(135deg,#1455d9,#18a4e8);
    color:white;
}

.contact .label{
    color:#bfeeff;
}

.contact h2{
    margin-bottom:15px;
}

.contact p{
    color:#e0f3ff;
    max-width:650px;
    margin:0 auto 28px;
}

/* FOOTER */

footer{
    background:#061329;
    color:#9fb0c9;
    padding:30px 0;
    text-align:center;
    font-size:14px;
}

/* MOBILE */

@media(max-width:850px){

    nav{
        display:none;
    }

    .hero{
        padding:75px 0;
    }

    .hero-grid,
    .location-grid{
        grid-template-columns:1fr;
    }

    .cards,
    .teacher-grid,
    .test-grid,
    .schedule-grid,
    .why-grid{
        grid-template-columns:1fr;
    }

    section{
        padding:70px 0;
    }

    .hero h1{
        letter-spacing:-1.8px;
    }

    .hero-card{
        margin-top:15px;
    }
}
</style>
</head>

<body>

<header>
<div class="container nav">

<a href="#" class="logo">
Pripreme <span>Učionica</span>
</a>

<nav>
<a href="#predmeti">Predmeti</a>
<a href="#nastavnici">Nastavnici</a>
<a href="#testovi">Testovi</a>
<a href="#lokacija">Lokacija</a>
<a href="#kontakt">Kontakt</a>
</nav>

<a href="tel:0629656676" class="btn btn-primary">
Pozovi
</a>

</div>
</header>

<section class="hero">

<div class="container hero-grid">

<div>

<div class="badge">
PRIPREME ZA PRIJEMNI ISPIT
</div>

<h1>
Pripremi se za prijemni
<span>na Novom Beogradu.</span>
</h1>

<p class="hero-text">
Pripreme Učionica pružaju kvalitetnu pripremu
iz srpskog jezika, matematike i izbornih predmeta.
Na časovima se rade zadaci, testovi i vežbe
uz profesionalan pristup nastavnika.
</p>

<div class="actions">

<a href="#kontakt" class="btn btn-white">
Prijavi se →
</a>

<a href="#predmeti" class="btn" style="border:1px solid rgba(255,255,255,.3);color:white;">
Pogledaj predmete
</a>

</div>

</div>

<div class="hero-card">

<h3>
Zašto Pripreme Učionica?
</h3>

<div class="quick">
<div class="quick-icon">90</div>
<div>
<strong>90 minuta</strong>
<small>Trajanje časa</small>
</div>
</div>

<div class="quick">
<div class="quick-icon">✓</div>
<div>
<strong>Testovi i zadaci</strong>
<small>Praktičan rad na časovima</small>
</div>
</div>

<div class="quick">
<div class="quick-icon">★</div>
<div>
<strong>Profesionalni nastavnici</strong>
<small>Fokus na kvalitetnu pripremu</small>
</div>
</div>

<div class="quick">
<div class="quick-icon">📍</div>
<div>
<strong>Blok 70</strong>
<small>Na Novom Beogradu</small>
</div>
</div>

</div>

</div>
</section>

<section class="subjects" id="predmeti">

<div class="container">

<div class="section-head center">

<div class="label">Program</div>

<h2>
Predmeti koje možeš
da pripremaš
</h2>

<p>
Od osnovnog gradiva do testova i zadataka
za što bolju pripremu za prijemni.
</p>

</div>

<div class="cards">

<div class="card">

<div class="card-icon">A</div>

<h3>Srpski jezik</h3>

<p>
Rad na gradivu, zadacima i testovima
uz pripremu usmerenu na prijemni ispit.
</p>

</div>

<div class="card">

<div class="card-icon">∑</div>

<h3>Matematika</h3>

<p>
Detaljno objašnjenje gradiva, rešavanje
zadataka i rad na testovima.
</p>

</div>

<div class="card">

<div class="card-icon">✓</div>

<h3>Izborni predmeti</h3>

<p>
Priprema iz izbornog predmeta koji učenik
odabere za prijemni ispit.
</p>

</div>

</div>

</div>

</section>

<section class="why">

<div class="container">

<div class="section-head center">

<div class="label">Kako radimo</div>

<h2>
Više od običnog časa.
</h2>

<p>
Cilj je da učenik razume gradivo,
uvežba zadatke i bude sigurniji pred prijemni.
</p>

</div>

<div class="why-grid">

<div class="why-card">
<strong>📝 Rad na testovima</strong>
<p>
Učenici rade testove i zadatke kako bi
proverili svoje znanje i uočili oblasti
na kojima treba dodatno da rade.
</p>
</div>

<div class="why-card">
<strong>🎯 Fokus na prijemni</strong>
<p>
Časovi su usmereni na sistematičnu
pripremu i vežbanje gradiva potrebnog
za prijemni ispit.
</p>
</div>

<div class="why-card">
<strong>⏱️ 90 minuta rada</strong>
<p>
Jedan čas traje sat i po, što ostavlja
dovoljno vremena za objašnjenje i vežbu.
</p>
</div>

<div class="why-card">
<strong>📅 Časovi vikendom</strong>
<p>
Pripreme se održavaju i vikendom,
što omogućava lakše uklapanje u raspored.
</p>
</div>

</div>

</div>

</section>

<section class="teachers" id="nastavnici">

<div class="container">

<div class="section-head center">

<div class="label">Nastavnici</div>

<h2>
Profesionalan pristup
i kvalitetan rad.
</h2>

<p>
Časove vode nastavnici koji se posvećuju
radu sa učenicima i njihovoj pripremi.
</p>

</div>

<div class="teacher-grid">

<div class="teacher">

<div class="avatar">
OŠ
</div>

<h3>Olivera Šapar</h3>

<div class="subject-name">
Srpski jezik
</div>

<p>
Priprema iz srpskog jezika kroz
objašnjenje gradiva, zadatke i testove.
</p>

</div>

<div class="teacher">

<div class="avatar">
NC
</div>

<h3>Nataša Caprić</h3>

<div class="subject-name">
Matematika
</div>

<p>
Priprema iz matematike kroz
sistematičan rad, zadatke i testove.
</p>

</div>

</div>

</div>

</section>

<section class="tests" id="testovi">

<div class="container">

<div class="section-head center">

<div class="label">Praktičan rad</div>

<h2>
Vežbamo. Rešavamo.
Proveravamo znanje.
</h2>

<p>
Na časovima se ne svodi sve samo na teoriju.
Veliki deo pripreme čine zadaci i testovi.
</p>

</div>

<div class="test-grid">

<div class="test-card">

<h3>📝 Testovi</h3>

<p>
Učenici rade testove kako bi proverili
svoje znanje i navikli se na rešavanje
zadataka u određenom vremenu.
</p>

</div>

<div class="test-card">

<h3>🎯 Analiza grešaka</h3>

<p>
Greške su deo učenja. Kroz rad na zadacima
učenici mogu da uoče šta im predstavlja
problem i da dodatno vežbaju.
</p>

</div>

</div>

</div>

</section>

<section class="schedule">

<div class="container">

<div class="section-head center">

<div class="label">Organizacija</div>

<h2>
Pripreme prilagođene učenicima.
</h2>

</div>

<div class="schedule-grid">

<div class="schedule-card">

<div class="big">90 min</div>

<h3>Trajanje časa</h3>

<p>
Jedan čas traje 1 sat i 30 minuta.
</p>

</div>

<div class="schedule-card">

<div class="big">Vikendom</div>

<h3>Fleksibilni termini</h3>

<p>
Časovi se održavaju i vikendom.
</p>

</div>

<div class="schedule-card">

<div class="big">3 oblasti</div>

<h3>Širok izbor</h3>

<p>
Srpski, matematika i izborni predmeti.
</p>

</div>

</div>

</div>

</section>

<section class="location" id="lokacija">

<div class="container location-grid">

<div>

<div class="label">Lokacija</div>

<h2>
Pripreme na
Novom Beogradu.
</h2>

<p class="location-text">
Nalazimo se u Bloku 70 na Novom Beogradu.
Lako nas možeš pronaći i doći na pripreme.
</p>

<a
href="https://www.google.com/maps/search/?api=1&query=Blok+70+Novi+Beograd"
target="_blank"
class="btn btn-primary">
Otvori lokaciju →
</a>

</div>

<div class="location-box">

<h3>📍 Blok 70</h3>

<p>
Novi Beograd
</p>

<div class="phone">
062 965 6676
</div>

<a href="tel:0629656676" class="btn btn-primary">
Pozovi odmah
</a>

</div>

</div>

</section>

<section class="contact" id="kontakt">

<div class="container">

<div class="label">Kontakt</div>

<h2>
Spremni za prijemni?
</h2>

<p>
Za više informacija o terminima,
predmetima i prijavi pozovite nas.
</p>

<a href="tel:0629656676" class="btn btn-white">
📞 062 965 6676
</a>

</div>

</section>

<footer>

<div class="container">

<strong>Pripreme Učionica</strong><br>
Pripreme za prijemni na Novom Beogradu · Blok 70<br><br>
© 2026 Pripreme Učionica

</div>

</footer>

</body>
</html>
