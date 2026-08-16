<!DOCTYPE html>
<html lang="sr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>Pripreme za prijemni — Blok 70</title>

<style>
*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:Arial,Helvetica,sans-serif;
    background:#f7f9fc;
    color:#172033;
    line-height:1.6;
}

a{
    text-decoration:none;
    color:inherit;
}

.container{
    width:min(1120px,92%);
    margin:auto;
}

header{
    position:sticky;
    top:0;
    z-index:100;
    background:rgba(255,255,255,.94);
    backdrop-filter:blur(14px);
    border-bottom:1px solid #e8ebf2;
}

.nav{
    min-height:76px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:25px;
}

.logo{
    font-size:22px;
    font-weight:800;
    color:#175cff;
}

.logo span{
    color:#172033;
}

nav{
    display:flex;
    gap:25px;
}

nav a{
    font-size:14px;
    font-weight:700;
    color:#536078;
}

nav a:hover{
    color:#175cff;
}

.btn{
    display:inline-flex;
    align-items:center;
    justify-content:center;
    padding:14px 22px;
    border-radius:12px;
    font-weight:800;
    border:2px solid transparent;
    transition:.2s;
}

.btn-primary{
    background:#175cff;
    color:white;
}

.btn-primary:hover{
    transform:translateY(-2px);
    box-shadow:0 12px 28px rgba(23,92,255,.25);
}

.btn-light{
    background:white;
    border-color:#dfe5ef;
}

.hero{
    padding:100px 0 80px;
    background:
        radial-gradient(circle at 85% 20%,#dce7ff 0,transparent 35%),
        linear-gradient(180deg,#fff,#f7f9fc);
}

.hero-grid{
    display:grid;
    grid-template-columns:1.1fr .9fr;
    align-items:center;
    gap:70px;
}

.badge{
    display:inline-block;
    padding:8px 13px;
    border-radius:50px;
    background:#e9f0ff;
    color:#175cff;
    font-size:13px;
    font-weight:800;
    margin-bottom:20px;
}

h1{
    font-size:clamp(42px,6vw,70px);
    line-height:1.02;
    letter-spacing:-2.5px;
    margin-bottom:24px;
}

h1 span{
    color:#175cff;
}

.hero p{
    color:#5d687d;
    font-size:18px;
    max-width:620px;
    margin-bottom:30px;
}

.actions{
    display:flex;
    gap:12px;
    flex-wrap:wrap;
}

.hero-card{
    background:white;
    border:1px solid #e5eaf2;
    border-radius:26px;
    padding:30px;
    box-shadow:0 25px 70px rgba(23,32,51,.1);
}

.hero-card h3{
    font-size:24px;
    margin-bottom:20px;
}

.info{
    display:flex;
    gap:15px;
    align-items:flex-start;
    padding:15px 0;
    border-bottom:1px solid #edf0f5;
}

.info:last-child{
    border-bottom:0;
}

.icon{
    width:42px;
    height:42px;
    display:grid;
    place-items:center;
    background:#edf3ff;
    color:#175cff;
    border-radius:12px;
    font-weight:900;
}

.info strong{
    display:block;
}

.info small{
    color:#6a7487;
}

section{
    padding:90px 0;
}

.section-head{
    max-width:700px;
    margin-bottom:45px;
}

.section-head.center{
    margin-left:auto;
    margin-right:auto;
    text-align:center;
}

.label{
    color:#175cff;
    font-size:13px;
    font-weight:900;
    letter-spacing:1.5px;
    text-transform:uppercase;
    margin-bottom:12px;
}

h2{
    font-size:clamp(32px,5vw,50px);
    line-height:1.1;
    letter-spacing:-1.5px;
    margin-bottom:16px;
}

.section-head p{
    color:#69758a;
    font-size:17px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:22px;
}

.card{
    background:white;
    border:1px solid #e5eaf2;
    border-radius:20px;
    padding:28px;
    transition:.25s;
}

.card:hover{
    transform:translateY(-5px);
    box-shadow:0 20px 45px rgba(23,32,51,.08);
}

.card-icon{
    width:54px;
    height:54px;
    display:grid;
    place-items:center;
    border-radius:15px;
    background:#175cff;
    color:white;
    font-size:22px;
    font-weight:900;
    margin-bottom:20px;
}

.card h3{
    font-size:23px;
    margin-bottom:10px;
}

.card p{
    color:#69758a;
}

.test-section{
    background:#101827;
    color:white;
}

.test-section .section-head p{
    color:#aeb8c9;
}

.test-box{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:20px;
}

.test-card{
    border:1px solid #29354a;
    background:#182235;
    border-radius:20px;
    padding:28px;
}

.test-card h3{
    margin-bottom:12px;
    font-size:23px;
}

.test-card p{
    color:#b8c1d0;
}

.teacher{
    display:flex;
    align-items:center;
    gap:18px;
    margin-top:15px;
}

.avatar{
    width:62px;
    height:62px;
    display:grid;
    place-items:center;
    border-radius:50%;
    background:#eaf0ff;
    color:#175cff;
    font-size:20px;
    font-weight:900;
}

.teacher strong{
    display:block;
}

.teacher span{
    color:#68758a;
    font-size:14px;
}

.schedule{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:20px;
}

.schedule-card{
    background:white;
    border:1px solid #e5eaf2;
    border-radius:20px;
    padding:28px;
}

.schedule-card strong{
    display:block;
    color:#175cff;
    margin-bottom:8px;
}

.schedule-card p{
    color:#69758a;
}

.location{
    background:#eaf0ff;
}

.location-box{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:30px;
    align-items:center;
}

.location-info{
    background:white;
    padding:35px;
    border-radius:24px;
    box-shadow:0 18px 50px rgba(23,32,51,.08);
}

.location-info p{
    color:#69758a;
    margin:12px 0 25px;
}

.contact{
    background:#175cff;
    color:white;
    text-align:center;
}

.contact p{
    max-width:650px;
    margin:0 auto 28px;
    color:#dce6ff;
}

.contact .btn-light{
    color:#172033;
}

footer{
    padding:30px 0;
    background:#0c1320;
    color:#9da8ba;
    text-align:center;
    font-size:14px;
}

.phone{
    font-size:27px;
    font-weight:900;
    color:#175cff;
}

@media(max-width:800px){

    nav{
        display:none;
    }

    .hero{
        padding:70px 0;
    }

    .hero-grid,
    .test-box,
    .location-box{
        grid-template-columns:1fr;
    }

    .grid,
    .schedule{
        grid-template-columns:1fr;
    }

    h1{
        letter-spacing:-1.5px;
    }

    section{
        padding:65px 0;
    }
}
</style>
</head>

<body>

<header>
<div class="container nav">

<a class="logo" href="#">
Pripreme<span>70</span>
</a>

<nav>
<a href="#predmeti">Predmeti</a>
<a href="#nastavnici">Nastavnici</a>
<a href="#testovi">Testovi</a>
<a href="#kontakt">Kontakt</a>
</nav>

<a class="btn btn-primary" href="tel:0629656676">
Pozovi
</a>

</div>
</header>

<main>

<section class="hero">
<div class="container hero-grid">

<div>

<div class="badge">
PRIPREME ZA PRIJEMNI ISPIT
</div>

<h1>
Spremi se za prijemni
<span>sigurno i kvalitetno.</span>
</h1>

<p>
Profesionalne pripreme iz srpskog jezika,
matematike i izbornih predmeta.
Radimo zadatke, testove i vežbe koje
pomažu učenicima da budu spremni za prijemni.
</p>

<div class="actions">
<a class="btn btn-primary" href="#kontakt">
Zakaži čas →
</a>

<a class="btn btn-light" href="#predmeti">
Pogledaj predmete
</a>
</div>

</div>

<div class="hero-card">

<h3>
Brze informacije
</h3>

<div class="info">
<div class="icon">⏱</div>
<div>
<strong>90 minuta</strong>
<small>Trajanje jednog časa</small>
</div>
</div>

<div class="info">
<div class="icon">📚</div>
<div>
<strong>Više predmeta</strong>
<small>Srpski, matematika i izborni</small>
</div>
</div>

<div class="info">
<div class="icon">📝</div>
<div>
<strong>Testovi i zadaci</strong>
<small>Vežbanje kroz konkretne primere</small>
</div>
</div>

<div class="info">
<div class="icon">📍</div>
<div>
<strong>Blok 70</strong>
<small>Novi Beograd</small>
</div>
</div>

</div>

</div>
</section>

<section id="predmeti">

<div class="container">

<div class="section-head center">
<div class="label">Predmeti</div>

<h2>
Sve što ti je potrebno
za prijemni.
</h2>

<p>
Fokusirani časovi, zadaci i testovi
za bolju pripremu.
</p>
</div>

<div class="grid">

<div class="card">
<div class="card-icon">A</div>
<h3>Srpski jezik</h3>
<p>
Rad na zadacima, testovima i oblastima
koje su važne za prijemni ispit.
</p>
</div>

<div class="card">
<div class="card-icon">∑</div>
<h3>Matematika</h3>
<p>
Vežbanje zadataka i testova uz
objašnjenja i sistematičan rad.
</p>
</div>

<div class="card">
<div class="card-icon">✓</div>
<h3>Izborni predmeti</h3>
<p>
Priprema i za izborni predmet koji
učenik odabere za prijemni.
</p>
</div>

</div>
</div>
</section>

<section id="nastavnici">

<div class="container">

<div class="section-head">
<div class="label">Nastavnici</div>

<h2>
Iskusni i profesionalni
nastavnici.
</h2>

<p>
Rad je usmeren na razumevanje gradiva,
redovno vežbanje i što bolju pripremu učenika.
</p>
</div>

<div class="grid">

<div class="card">

<div class="teacher">

<div class="avatar">
OŠ
</div>

<div>
<strong>Olivera Šapar</strong>
<span>Srpski jezik</span>
</div>

</div>

<p style="margin-top:20px">
Časovi srpskog jezika sa fokusom na
gradivo, zadatke i testove za prijemni.
</p>

</div>

<div class="card">

<div class="teacher">

<div class="avatar">
NC
</div>

<div>
<strong>Nataša Caprić</strong>
<span>Matematika</span>
</div>

</div>

<p style="margin-top:20px">
Priprema iz matematike kroz zadatke,
vežbu i rad na testovima.
</p>

</div>

<div class="card">

<div class="card-icon">★</div>

<h3>
Profesionalan pristup
</h3>

<p>
Cilj je da učenik ne uči napamet,
već da razume gradivo i bude sigurniji
u rešavanju zadataka.
</p>

</div>

</div>
</div>
</section>

<section class="test-section" id="testovi">

<div class="container">

<div class="section-head center">

<div class="label">
Praktičan rad
</div>

<h2>
Ne učimo samo teoriju.
Radimo testove.
</h2>

<p>
Učenici kroz časove rade konkretne
zadatke i testove kako bi se navikli
na način rada koji ih očekuje.
</p>

</div>

<div class="test-box">

<div class="test-card">
<h3>📝 Testovi</h3>
<p>
Redovno rešavanje testova omogućava
učenicima da provere svoje znanje,
uoče greške i rade na oblastima
koje im predstavljaju problem.
</p>
</div>

<div class="test-card">
<h3>🎯 Fokus na prijemni</h3>
<p>
Časovi su usmereni na ono što je
učeniku potrebno da bi što spremnije
dočekao prijemni ispit.
</p>
</div>

</div>
</div>
</section>

<section>

<div class="container">

<div class="section-head center">

<div class="label">
Organizacija
</div>

<h2>
Čas traje 1 sat i 30 minuta.
</h2>

<p>
Dovoljno vremena za objašnjenje,
vežbanje i rad na zadacima.
</p>

</div>

<div class="schedule">

<div class="schedule-card">
<strong>⏱ Trajanje</strong>
<h3>90 minuta</h3>
<p>
Jedan čas traje sat i po.
</p>
</div>

<div class="schedule-card">
<strong>📅 Vikend</strong>
<h3>Časovi i vikendom</h3>
<p>
Pripreme se održavaju i tokom vikenda.
</p>
</div>

<div class="schedule-card">
<strong>📚 Program</strong>
<h3>Prijemni + testovi</h3>
<p>
Gradivo, zadaci i testovi kroz pripremu.
</p>
</div>

</div>
</div>
</section>

<section class="location">

<div class="container location-box">

<div>

<div class="label">
Lokacija
</div>

<h2>
Vidimo se u
Novom Beogradu.
</h2>

<p>
Pripreme se održavaju u
Bloku 70 na Novom Beogradu.
</p>

<a
class="btn btn-primary"
href="https://www.google.com/maps/search/?api=1&query=Blok+70+Novi+Beograd"
target="_blank">
Otvori lokaciju →
</a>

</div>

<div class="location-info">

<h3>
📍 Blok 70
</h3>

<p>
Novi Beograd, Beograd
</p>

<div class="phone">
062 965 6676
</div>

<p>
Za informacije o terminima,
predmetima i prijavi pozovite
navedeni broj telefona.
</p>

<a
class="btn btn-primary"
href="tel:0629656676">
Pozovi odmah
</a>

</div>

</div>
</section>

<section class="contact" id="kontakt">

<div class="container">

<div class="label" style="color:#cddaff">
Kontakt
</div>

<h2>
Spremni za prijemni?
</h2>

<p>
Pozovite i raspitajte se o terminima,
predmetima i mogućnosti prijave
za pripreme.
</p>

<a
class="btn btn-light"
href="tel:0629656676">
📞 062 965 6676
</a>

</div>

</section>

</main>

<footer>
<div class="container">
© 2026 Pripreme za prijemni · Novi Beograd · Blok 70
</div>
</footer>

</body>
</html>
