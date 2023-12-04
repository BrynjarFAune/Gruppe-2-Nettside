<main>
<header>
<p class="contact">Ring kontaktperson: +47 123 123 123</p>
<section class="medier">
<div class="twitter-wrapper">bird</div>
<div class="tiktok-wrapper"></div>
<div class="facebook-wrapper"></div>
<div class="instagram-wrapper"></div>
</section>
</header>

<nav>
<span><icon><img src="./logo.png"></icon><h3 class="title">2IT Breivang VGS</h3></span>
<span class="nav-links">
<a href="/"><h4 class="link">Hjem</h4></a>
<a href="/database"><h4 class="link">Database</h4></a>
<a href="/events"><h4 class="link">Eventer</h4></a>
<a href="/contact"><h4 class="link">Kontakt</h4></a>
</span>
</nav>

<slot></slot>

<footer>
<div class="footer-content">
<p>© 2023 Breivang VGS. Alle rettigheter forbeholdt.</p>
<p>Adresse: Dramsvegen 199, 9010 Tromsø | Telefon: 77 78 85 00 | E-post: breivang@tffk.no</p>
<p>Designet & Utviklet av 2IT</p>
</div>
</footer>
</main>


<style>

header {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    background-color: #C9C9CA;
    color: #1E1E1E;
    height: 31px;
}

header * {
    margin: 31px;
}

nav > *{
    margin: 31px;
    display: flex;
    flex-direction: row;
}

nav > * > * {
    margin: 10px;
}

nav {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    height: 96px;
    background-color: #1E1E1E;
}

.link, .title {
    text-decoration: none;
    color: #ffffff;
}

.footer-content {
    margin: 31px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

footer {
    height: 67px;
    background-color: #1E1E1E;
    alignn-items: center;
    position: absolute;
    bottom: 0;
    width: 100%;
}

.footer-content > p {
    color: #ffffff;
}
</style>
