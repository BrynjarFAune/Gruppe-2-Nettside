
<header>
<div class="content">

<p class="contact">Ring kontaktperson: +47 123 123 123</p>
<section class="medier">
<div class="twitter-wrapper">bird</div>
<div class="tiktok-wrapper"></div>
<div class="facebook-wrapper"></div>
<div class="instagram-wrapper"></div>
</section>
</div>
</header>

<nav>
<div class="content">

<a href="/" class="logo-link">
  <span class="logo">
    <img src="./logo.png" alt="tromsokommune logo">
  </span>
  <h3 class="title">2IT Breivang VGS</h3>
</a>


<span class="nav-links">
<a href="/"><h4 class="link">Hjem</h4></a>
<a href="/database"><h4 class="link">Database</h4></a>
<a href="/events"><h4 class="link">Eventer</h4></a>
<a href="/contact"><h4 class="link">Kontakt</h4></a>
</span>
</div>
</nav>

<slot></slot>

<footer>
<div class="content">
<p class="footer-txt">© 2023 Breivang VGS. Alle rettigheter forbeholdt.</p>
<p class="footer-txt">Adresse: Dramsvegen 199, 9010 Tromsø | Telefon: 77 78 85 00 | E-post: breivang@tffk.no</p>
<p class="footer-txt">Designet & Utviklet av 2IT</p>
</div>
</footer>

<style>

* {
    margin: 0;
    display: flex;
}

a, a > * {
    text-decoration: none;
}

/* Header styling */

header {
    height: 31px;
    background-color: #C9C9CA;
}


/* Navbar styling */

nav { 
    height: 65px;
    flex-direction: row;
    background-color: green;
    background-color: #1E1E1E;
}

.nav-links {
    align-items: center;
    text-decoration: none;
}

.logo-link {
    display: flex;
    align-items: center;
}

.logo img {
    height: 45px;
    width: auto;
}



.title, .link {
    color: #ffffff;
    font-size: 16;
    text-decoration: none;
    margin-left: 15px;
}


/* Footer styles */

footer {
    height: 67px;
    background-color: #1E1E1E;
       
    /*send to bottom*/
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
}

.content {
    height: 100%;
    background-color: inherit;
    margin: 0 31px;
    justify-content: space-between;
    width: 100%;
    align-items: center;
}
.footer-txt {
    background-color: #1E1E1E;
    color: #ffffff;
    font-size: 12;
}

</style>
