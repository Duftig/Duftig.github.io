<!doctype html>
<html lang="de">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>OCF — One Click Faceless</title>
<style>
:root {
  --bg: #f0f0f0;
  --card-bg: rgba(255,255,255,0.85);
  --glass-bg: rgba(255,255,255,0.6);
  --muted: #6b6f76;
  --accent: #0071e3;
  --accent-light: rgba(0,113,227,0.1);
  --radius: 16px;
  --shadow: 0 8px 24px rgba(0,0,0,0.08);
  --max-width: 1100px;
}
* { box-sizing: border-box; }
html, body { margin:0; padding:0; font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial; background:var(--bg); color:#0b1220; }
a { text-decoration:none; color:inherit; }
.container { max-width: var(--max-width); margin:0 auto; padding:24px 16px; }
header { display:flex; align-items:center; justify-content:space-between; margin-bottom:32px; }
.brand { display:flex; align-items:center; gap:12px; }
.logo-square { width:56px; height:56px; border-radius:12px; background:var(--glass-bg); border:1px solid var(--accent-light); display:flex; align-items:center; justify-content:center; box-shadow:var(--shadow); }
.logo-text { font-weight:800; font-size:16px; color:var(--accent); letter-spacing:0.5px; }
.brand-text .brand-title { font-size:18px; font-weight:700; }
.brand-text .brand-sub { font-size:13px; color:var(--muted); }
.btn-ghost { background:transparent; border:1px solid rgba(11,18,32,0.2); color:var(--muted); padding:10px 16px; border-radius:12px; cursor:pointer; font-weight:600; transition: all 0.2s; }
.btn-ghost:hover { background:var(--accent-light); }
.hero { display:grid; grid-template-columns:1fr 450px; gap:32px; align-items:center; padding:32px; background:var(--card-bg); border-radius:var(--radius); box-shadow:var(--shadow); backdrop-filter:blur(6px); }
@media(max-width:900px) { .hero { grid-template-columns:1fr; } }
.eyebrow { font-size:13px; color:var(--muted); font-weight:600; text-transform:uppercase; margin-bottom:12px; letter-spacing:1px; }
.title { font-size:32px; line-height:1.1; margin:0 0 14px 0; font-weight:700; }
.lead { color:var(--muted); font-size:16px; margin-bottom:22px; max-width:55ch; }
.features { display:flex; gap:10px; flex-wrap:wrap; margin-bottom:24px; }
.chip { background:var(--glass-bg); padding:10px 14px; border-radius:12px; font-weight:600; font-size:13px; border:1px solid rgba(11,18,32,0.12); }
.cta-row { display:flex; gap:14px; align-items:center; margin-bottom:12px; flex-wrap: wrap; }
.btn-primary { background:var(--accent); color:white; padding:14px 20px; border:none; border-radius:12px; font-weight:700; cursor:pointer; box-shadow:0 8px 30px rgba(0,113,227,0.25); transition: transform .14s ease, box-shadow .14s ease; }
.btn-primary:hover { box-shadow:0 12px 36px rgba(0,113,227,0.3); }
.btn-primary:active { transform:translateY(1px) scale(0.99); }
.meta { font-size:13px; color:var(--muted); }
.hero-right { position:relative; display:flex; flex-direction:column; align-items:center; gap:16px; }
.device-mockup { width:100%; max-width:380px; border-radius:var(--radius); overflow:hidden; border:1px solid rgba(11,18,32,0.15); background-color:#fff; }
.device-mockup img { display:block; width:100%; height:auto; object-fit:cover; border-radius:var(--radius); }
.glass-card { position:absolute; bottom:-30px; left:50%; transform:translateX(-50%); width:300px; padding:16px; border-radius:12px; background:var(--glass-bg); border:1px solid rgba(11,18,32,0.12); backdrop-filter:blur(8px); display:flex; justify-content:center; align-items:center; box-shadow:var(--shadow); font-weight:700; }
.section { margin-top:64px; }
.section-title { font-size:24px; font-weight:700; margin-bottom:24px; text-align:center; }
.grid-2 { display:grid; grid-template-columns:1fr 1fr; gap:32px; align-items:center; }
@media(max-width:800px) { .grid-2 { grid-template-columns:1fr; } }
.feature-image { width:100%; max-width:450px; height:auto; border-radius:var(--radius); }
.feature-list { display:flex; flex-direction:column; gap:16px; text-align:left; }
.feature-list h3 { margin:0; font-size:20px; font-weight:700; }
.feature-list p { margin:0; font-size:15px; color:var(--muted); }
.setup-steps { display:flex; flex-direction:column; align-items:center; text-align:center; gap:16px; max-width:600px; margin:0 auto; }
.setup-steps h3 { margin:0; font-size:20px; font-weight:700; }
.setup-steps p { margin:0; color:var(--muted); }
footer { margin-top:48px; text-align:center; color:var(--muted); font-size:13px; padding-bottom:32px; }
</style>
</head>
<body>
<div class="container">
<header>
<a class="brand" href="#">
<div class="logo-square"><span class="logo-text">OCF</span></div>
<div class="brand-text">
<div class="brand-title">OCF — One Click Faceless</div>
<div class="brand-sub">Schnell. Anonym. Conversion-optimiert.</div>
</div>
</a>
<nav>
<button class="btn-ghost" id="openDemo">Demo ansehen</button>
</nav>
</header>

<main>
<!-- Hero -->
<section class="hero">
<div class="hero-left">
<div class="eyebrow">Neu · Digital</div>
<h1 class="title">One Click Faceless — Checkout neu gedacht</h1>
<p class="lead">Einfacher Checkout, große Wirkung: Anonyme Bestellabwicklung, optimiert für höchste Conversion.</p>
<div class="features">
<span class="chip">Schnelle Einrichtung</span>
<span class="chip">DSGVO-freundlich</span>
<span class="chip">Conversion-boost</span>
<span class="chip">Leicht anpassbar</span>
</div>
<div class="cta-row">
<button class="btn-primary" id="buyNow">Jetzt starten</button>
<a href="https://www.oneclickfaceless.com/" target="_blank" class="btn-ghost">Offizielle Website</a>
</div>
<p class="meta">Preis: 2.376,43 € | Hosted & abgerechnet via Digistore24.</p>
</div>

<div class="hero-right">
<div class="device-mockup">
<img src="https://i.pinimg.com/736x/e8/fd/40/e8fd40dfbb9de0792112bb0a89a4ac88.jpg" alt="Device Mockup">
</div>
<div class="glass-card">Nur für kurze Zeit: 1800,00 € Gutscheincode 197OCF</div>
</div>
</section>

<!-- Vorteile -->
<section class="section">
<div class="section-title">Deine Vorteile mit OCF</div>
<div class="grid-2">
<div class="feature-list">
<h3>1. Blitzschnelle Integration</h3>
<p>In wenigen Minuten integrierbar in deine Seite oder dein System – keine komplizierten Einstellungen.</p>
<h3>2. Höhere Abschlussraten</h3>
<p>Minimaler Checkout reduziert Abbruch – mehr Käufer kommen ans Ziel.</p>
<h3>3. Datenschutz & Vertrauen</h3>
<p>Anonymisierte Flows und DSGVO-konforme Prozesse sorgen für Sicherheit und Vertrauen.</p>
<h3>4. Anpassbar & flexibel</h3>
<p>Gestalte Farben, Texte und Abläufe nach deinem Branding – ohne Programmieraufwand.</p>
</div>
<div>
<img class="feature-image" src="https://i.pinimg.com/736x/fa/56/f7/fa56f79a98d373a0a4f3340fb7bc4287.jpg" alt="Feature 1">
</div>
</div>
</section>

<!-- Ablauf / Einrichtung -->
<section class="section">
<div class="section-title">So richtest du OCF ein</div>
<div class="setup-steps">
<h3>Schritt 1: Setup & Verbindung</h3>
<p>Verbinde OCF mit deiner Landingpage oder deinem Shop-System in wenigen Klicks.</p>

<h3>Schritt 2: Template wählen</h3>
<p>Wähle ein Design aus oder passe es nach deinem Branding an.</p>

<h3>Schritt 3: Live schalten</h3>
<p>Gehe live und lasse den unsichtbaren Checkout automatisch laufen.</p>
</div>
</section>

</main>

<script>
const productUrl = "https://www.digistore24.com/product/547368?aff=Fynn567";
document.getElementById('buyNow').addEventListener('click', () => {
  window.open(productUrl,'_blank','noopener');
});

const demoUrl = "https://www.oneclickfaceless.com/";
document.getElementById('openDemo').addEventListener('click', () => {
  window.open(demoUrl, '_blank','noopener');
});
</script>

<footer>
<p>© 2025 OCF — One Click Faceless. Alle Rechte vorbehalten.</p>
</footer>
</body>
</html>
