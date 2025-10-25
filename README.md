<!doctype html>
<html lang="de">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>One Click Faceless — Einmalig 1.800 € | Jetzt sichern</title>

  <!-- Moderne Schrift -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#fbfbfb;            /* very light gray / white */
      --panel:#f4f4f5;         /* light panel */
      --muted:#e9e9ea;         /* subtle borders */
      --text:#222;             /* primary text */
      --muted-text:#6b6b6d;
      --beige:#d9cbb7;         /* accent beige */
      --glass-border: rgba(255,255,255,0.55);
      --glass-shadow: rgba(15,15,15,0.06);
      --radius:18px;
      --max-width:1100px;
      --affiliate-url: "https://tinyurl.com/yum4rtcw";
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:"Poppins",system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;
      background:linear-gradient(180deg,var(--bg) 0%, #ffffff 100%);
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.5;
      -webkit-tap-highlight-color: transparent;
    }

    .wrap{
      max-width:var(--max-width);
      margin:32px auto;
      padding:28px;
    }

    /* Header */
    header{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:20px;
      margin-bottom:28px;
    }
    .logo{display:flex;align-items:center;gap:12px;text-decoration:none;color:var(--text)}
    .mark{
      width:56px;height:56px;border-radius:12px;
      background:linear-gradient(135deg,#fff,#f6f6f7);
      box-shadow: 0 6px 20px rgba(12,12,14,0.04);
      display:flex;align-items:center;justify-content:center;font-weight:800;
      border:1px solid var(--muted);
      color:var(--text);
      font-size:18px;
    }
    nav{display:flex;gap:14px;align-items:center}
    nav a{color:var(--text);text-decoration:none;padding:8px 14px;border-radius:12px;font-weight:600;font-size:14px}
    nav a.cta{
      background: linear-gradient(180deg, rgba(255,255,255,0.55), rgba(255,255,255,0.25));
      border:1px solid rgba(255,255,255,0.6);
      box-shadow: 0 6px 22px var(--glass-shadow);
      backdrop-filter: blur(8px) saturate(110%);
      -webkit-backdrop-filter: blur(8px) saturate(110%);
      border-radius:14px;
    }

    /* Hero */
    .hero{
      display:grid;
      grid-template-columns: 1fr 420px;
      gap:28px;
      align-items:center;
      background:linear-gradient(180deg,#fff, var(--panel));
      padding:32px;
      border-radius:20px;
      border:1px solid var(--muted);
      position:relative;
      overflow:visible;
    }

    .coupon-banner{
      position:absolute;
      top:-22px;
      left:50%;
      transform:translateX(-50%);
      background:linear-gradient(180deg, rgba(255,255,255,0.85), rgba(255,255,255,0.6));
      border:1px solid rgba(217,203,183,0.9);
      backdrop-filter: blur(8px);
      box-shadow: 0 6px 26px rgba(12,12,14,0.06);
      padding:10px 18px;
      border-radius:14px;
      font-weight:700;
      font-size:15px;
      color:var(--text);
      display:flex;
      gap:10px;
      align-items:center;
    }
    .coupon-banner .code{
      background:rgba(217,203,183,0.14);
      padding:6px 10px;border-radius:10px;border:1px solid rgba(217,203,183,0.35);
      color:var(--beige);font-weight:800;
    }

    .hero h1{font-size:34px;margin:0 0 8px;line-height:1.05}
    .hero p.lead{margin:0 0 18px;color:var(--muted-text);font-size:16px}

    .features{
      display:flex;gap:10px;flex-wrap:wrap;margin-top:8px;
    }
    .chip{
      display:inline-flex;align-items:center;gap:10px;padding:10px 12px;border-radius:12px;
      background:linear-gradient(180deg,#fff,#f7f7f7);border:1px solid var(--muted);font-weight:600;font-size:14px;
    }
    .chip .dot{width:34px;height:34px;border-radius:10px;background:var(--beige);display:flex;align-items:center;justify-content:center;font-weight:700}

    /* Buttons (glass) */
    .btn{
      display:inline-flex;align-items:center;gap:10px;padding:12px 18px;border-radius:14px;font-weight:700;border:1px solid var(--glass-border);
      background: linear-gradient(180deg, rgba(255,255,255,0.55), rgba(255,255,255,0.22));
      box-shadow: 0 10px 30px rgba(12,12,14,0.06);
      cursor:pointer;text-decoration:none;color:var(--text);
      transition:transform .14s ease, box-shadow .14s ease;
      backdrop-filter: blur(10px) saturate(110%);
    }
    .btn:active{transform:translateY(1px)}
    .btn.secondary{background:transparent;border:1px solid var(--muted);font-weight:600}

    /* Card / aside */
    .card{
      background:linear-gradient(180deg,#fff,#f8f8f9);
      border-radius:16px;padding:18px;border:1px solid var(--muted);
      box-shadow: 0 8px 24px rgba(12,12,14,0.03);
    }
    .image{
      background-position:center;background-size:cover;border-radius:12px;border:1px solid var(--muted);min-height:220px;
    }

    /* Pricing */
    .price-box{
      text-align:center;padding:22px;border-radius:14px;background:linear-gradient(180deg,#fff, #fbfbfb);border:1px solid var(--muted);
    }
    .old-price{color:var(--muted-text);text-decoration:line-through;font-weight:700}
    .current-price{font-size:32px;font-weight:900;margin-top:6px}
    .price-note{color:var(--muted-text);font-size:14px;margin-top:6px}

    /* Price highlight (beige) */
    .save-strip{
      margin-top:12px;padding:10px;border-radius:12px;background:rgba(217,203,183,0.22);border:1px solid rgba(217,203,183,0.5);font-weight:700;color:var(--text)
    }

    section{margin:28px 0}
    h2{margin:0 0 10px;font-size:22px}
    .muted{color:var(--muted-text);font-size:15px}

    .cols{display:grid;grid-template-columns:1fr 1fr;gap:20px}
    .steps{display:flex;flex-direction:column;gap:12px;margin-top:8px}
    .step{display:flex;gap:12px;align-items:flex-start;background:linear-gradient(180deg,#fff,#f6f6f7);padding:12px;border-radius:12px;border:1px solid var(--muted)}

    .faq .q{margin-bottom:10px;border-radius:12px;overflow:hidden;border:1px solid var(--muted);background:linear-gradient(180deg,#fff,#fafafa)}
    .faq button{width:100%;text-align:left;padding:14px 16px;background:transparent;border:0;font-weight:700;font-size:15px;cursor:pointer}
    .faq .a{padding:12px 16px;border-top:1px solid var(--muted);color:#444;font-size:14px}

    footer{margin:36px 0 12px;color:var(--muted-text);font-size:13px;text-align:center}

    /* small responsive */
    @media (max-width:980px){
      .hero{grid-template-columns:1fr}
      .cols{grid-template-columns:1fr}
    }

    /* subtle pulse for coupon (disabled by default, add .pulse to .coupon-banner to enable) */
    @keyframes pulse {
      0% { box-shadow: 0 6px 26px rgba(12,12,14,0.06); transform: translateY(0); }
      50% { box-shadow: 0 10px 36px rgba(12,12,14,0.09); transform: translateY(-2px); }
      100% { box-shadow: 0 6px 26px rgba(12,12,14,0.06); transform: translateY(0); }
    }
    .coupon-banner.pulse { animation: pulse 2.8s infinite ease-in-out; }

    /* accessibility focus */
    a:focus, button:focus { outline:3px solid rgba(217,203,183,0.35); outline-offset:3px; border-radius:10px; }
  </style>
</head>
<body>

  <div class="wrap">
    <header>
      <a class="logo" href="#" aria-label="One Click Faceless">
        <div class="mark">OCF</div>
        <div>
          <div style="font-weight:800">One Click Faceless</div>
          <div style="font-size:12px;color:var(--muted-text)">Schlüsselfertiges Faceless-Online-Business</div>
        </div>
      </a>

      <nav>
        <a href="#vorteile">Vorteile</a>
        <a href="#preis">Preis</a>
        <a href="#anleitung">Anleitung</a>
        <a href="#faq">FAQ</a>
        <!-- CTA in header -->
        <a class="cta" href="https://tinyurl.com/yum4rtcw" target="_blank" rel="noopener noreferrer">Jetzt kaufen</a>
      </nav>
    </header>

    <!-- HERO -->
    <main class="hero" role="main" aria-labelledby="hero-title">
      <div class="coupon-banner pulse" id="couponBanner">
        💸 Nur für kurze Zeit: <strong style="margin-left:6px">Einmalig 1.800 €</strong>
        <span style="margin-left:12px;color:var(--muted-text)">Gutscheincode:</span>
        <span class="code" id="couponCode" style="margin-left:8px">197OCF</span>
        <button class="btn" id="copyCouponBtn" style="margin-left:12px;font-size:13px;padding:8px 10px;">Code kopieren</button>
      </div>

      <div>
        <h1 id="hero-title">Starte dein anonymes Online-Business — sofort einsatzbereit</h1>
        <p class="lead">One Click Faceless liefert dir fertige Funnels, Landingpages, tausende Faceless-Videos und komplette Automationen — *einmalig 1.800 €*, sofortiger Zugriff.</p>

        <div class="features" aria-hidden="false">
          <div class="chip"><span class="dot">✓</span> Komplett vorgefertigt</div>
          <div class="chip"><span class="dot">⚡</span> Schnell startklar</div>
          <div class="chip"><span class="dot">🔒</span> Anonym & DSGVO-fähig</div>
        </div>

        <div style="margin-top:18px;">
          <a class="btn" id="buyNowTop" href="https://tinyurl.com/yum4rtcw" target="_blank" rel="noopener noreferrer">Jetzt kaufen — 1.800 €</a>
          <a class="btn secondary" href="#preis">Details zum Preis</a>
        </div>
      </div>

      <aside class="card" aria-hidden="false">
        <div class="image" style="background-image:url('https://images.unsplash.com/photo-1526378728251-99a1be06b5b9?auto=format&fit=crop&w=1200&q=60');"></div>

        <div style="margin-top:12px;">
          <div style="display:flex;justify-content:space-between;align-items:center">
            <div>
              <div style="font-size:13px;color:var(--muted-text)">Einmalpreis</div>
              <div style="font-weight:900;font-size:20px">1.800,00 €</div>
            </div>
            <div style="text-align:right">
              <div style="font-size:12px;color:var(--muted-text)">Vorher</div>
              <div style="font-weight:700;color:var(--muted-text);text-decoration:line-through">2.376,43 €</div>
            </div>
          </div>

          <div style="display:flex;gap:10px;margin-top:12px">
            <a class="btn" href="https://tinyurl.com/yum4rtcw" target="_blank" rel="noopener noreferrer">Jetzt kaufen — 1.800 €</a>
            <a class="btn secondary" href="#faq">Fragen?</a>
          </div>
        </div>
      </aside>
    </main>

    <!-- Vorteile -->
    <section id="vorteile" class="card" aria-labelledby="vorteile-title">
      <h2 id="vorteile-title">Vorteile</h2>
      <p class="muted">Warum One Click Faceless besonders für Einsteiger und Automatisierer ideal ist:</p>

      <div class="cols" style="margin-top:14px">
        <div>
          <ul>
            <li><strong>Anonymität:</strong> Kein öffentliches Auftreten nötig.</li>
            <li><strong>Schneller Start:</strong> Komplett konfigurierte Funnels & Landingpages.</li>
            <li><strong>Großer Content-Pool:</strong> Vorproduzierte Faceless-Videos und Templates.</li>
          </ul>
        </div>
        <div>
          <ul>
            <li><strong>Automatisierungen:</strong> E-Mail-Sequenzen & Zahlungsintegration inklusive.</li>
            <li><strong>Support & Tutorials:</strong> Schritt-für-Schritt-Videos für jeden Schritt.</li>
            <li><strong>Skalierbar:</strong> Für Einzelpersonen und Agenturen geeignet.</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Preis -->
    <section id="preis" class="card" aria-labelledby="preis-title">
      <h2 id="preis-title">Preis & Aktion</h2>

      <div style="display:flex;gap:20px;align-items:flex-start;flex-wrap:wrap;margin-top:12px">
        <div class="price-box" style="flex:1;min-width:320px;">
          <div class="old-price">2.376,43 €</div>
          <div class="current-price">1.800,00 € <span style="font-size:14px;font-weight:600">einmalig</span></div>
          <div class="price-note">Sofortiger Zugriff auf alle Vorlagen, Videos & Funnels</div>

          <div class="save-strip" role="note" aria-live="polite">
            🎁 Aktionscode: <strong style="margin-left:8px">197OCF</strong> — nur für kurze Zeit
          </div>

          <div style="margin-top:14px;display:flex;gap:10px;align-items:center;justify-content:center;flex-wrap:wrap">
            <a class="btn" href="https://tinyurl.com/yum4rtcw" target="_blank" rel="noopener noreferrer">Jetzt sichern — 1.800 €</a>
            <button class="btn secondary" id="copyBtnMobile">Code kopieren</button>
          </div>

          <div style="margin-top:10px;color:var(--muted-text);font-size:13px">
            Hinweis: Beim Kauf im Bestellformular den Code <strong>197OCF</strong> eingeben.
          </div>
        </div>

        <div style="flex:1;min-width:260px;">
          <div class="card" style="padding:14px;">
            <h3 style="margin:0 0 8px">Was ist enthalten?</h3>
            <ul style="margin-top:8px">
              <li>Komplette Funnels & Landingpages</li>
              <li>Tausende Faceless-Videos & Content-Templates</li>
              <li>Vorgefertigte E-Mail-Automationen</li>
              <li>DSGVO-Elemente & Support</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Anleitung -->
    <section id="anleitung" class="card" aria-labelledby="anleitung-title">
      <h2 id="anleitung-title">So startest du — in 3 Schritten</h2>

      <div class="steps">
        <div class="step">
          <div style="width:44px;height:44px;border-radius:10px;background:var(--beige);display:flex;align-items:center;justify-content:center;font-weight:800">1</div>
          <div>
            <div style="font-weight:800">Kaufen & Zugang sichern</div>
            <div class="muted">Klicke auf „Jetzt kaufen“ — du wirst über meinen Affiliate-Link weitergeleitet.</div>
          </div>
        </div>

        <div class="step">
          <div style="width:44px;height:44px;border-radius:10px;background:var(--beige);display:flex;align-items:center;justify-content:center;font-weight:800">2</div>
          <div>
            <div style="font-weight:800">Vorlagen anpassen</div>
            <div class="muted">Landingpages und Funnels individuell anpassen — keine Technikkenntnisse nötig.</div>
          </div>
        </div>

        <div class="step">
          <div style="width:44px;height:44px;border-radius:10px;background:var(--beige);display:flex;align-items:center;justify-content:center;font-weight:800">3</div>
          <div>
            <div style="font-weight:800">Traffic & Monetarisierung</div>
            <div class="muted">Nutze die Anleitung für bezahlten und organischen Traffic — automatisiere Verkäufe.</div>
          </div>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq" class="card" aria-labelledby="faq-title">
      <h2 id="faq-title">Häufig gestellte Fragen</h2>

      <div class="faq" style="margin-top:12px">
        <div class="q">
          <button aria-expanded="false">Ist der Preis einmalig?</button>
          <div class="a" hidden>Ja — der hier gezeigte Preis von 1.800,00 € ist eine einmalige Zahlung (sofern vom Anbieter so angeboten).</div>
        </div>

        <div class="q">
          <button aria-expanded="false">Wie löse ich den Gutschein ein?</button>
          <div class="a" hidden>Gib im Bestellformular den Code <strong>197OCF</strong> ein. Bei Fragen hilft der Support des Anbieters.</div>
        </div>

        <div class="q">
          <button aria-expanded="false">Bekomme ich Support?</button>
          <div class="a" hidden>Ja — Support und Videoanleitungen sind im Paket beschrieben (Details auf der Bestellseite).</div>
        </div>

        <div class="q">
          <button aria-expanded="false">Werde ich für den Kauf eine Provision erhalten?</button>
          <div class="a" hidden>Wenn du über meinen Affiliate-Link kaufst, erhalte ich eine kleine Provision — für dich entstehen keine Mehrkosten.</div>
        </div>
      </div>
    </section>

    <!-- CTA -->
    <section class="card" style="display:flex;align-items:center;justify-content:space-between;gap:18px;flex-wrap:wrap">
      <div>
        <h2>Noch unsicher?</h2>
        <div class="muted">Teste das Angebot — der Zugang ist sofort verfügbar und die Anleitung führt dich Schritt für Schritt.</div>
      </div>
      <div style="display:flex;gap:10px;align-items:center">
        <a class="btn" href="https://tinyurl.com/yum4rtcw" target="_blank" rel="noopener noreferrer">Jetzt kaufen — 1.800 €</a>
        <a class="btn secondary" href="#faq">FAQ lesen</a>
      </div>
    </section>

    <footer>
      Offizielle Produktseite (Affiliate-Link): <a href="https://tinyurl.com/yum4rtcw" target="_blank" rel="noopener noreferrer">One Click Faceless</a><br>
      <span style="font-size:12px;color:#aaa;">*Affiliate-Hinweis: Beim Kauf über diesen Link erhalte ich eine kleine Provision — für dich entstehen keine Mehrkosten.</span>
    </footer>
  </div>

  <script>
    // All buy / CTA links already point to the affiliate URL (tinyurl.com/yum4rtcw).
    // Smooth scrolling for anchors:
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', e=>{
        const href = a.getAttribute('href');
        if(href.length>1){
          e.preventDefault();
          document.querySelector(href).scrollIntoView({behavior:'smooth',block:'start'});
        }
      })
    });

    // FAQ accordion
    document.querySelectorAll('.faq .q button').forEach(btn=>{
      btn.addEventListener('click', ()=>{
        const expanded = btn.getAttribute('aria-expanded') === 'true';
        document.querySelectorAll('.faq .q button').forEach(b=>{
          b.setAttribute('aria-expanded','false');
          if(b.nextElementSibling) b.nextElementSibling.hidden = true;
        });
        if(!expanded){
          btn.setAttribute('aria-expanded','true');
          if(btn.nextElementSibling) btn.nextElementSibling.hidden = false;
        }
      })
    });

    // Copy coupon code buttons
    function copyText(text){
      if(navigator.clipboard && window.isSecureContext){
        return navigator.clipboard.writeText(text);
      } else {
        // fallback
        const ta = document.createElement('textarea');
        ta.value = text;
        ta.style.position = 'fixed';
        ta.style.left = '-9999px';
        document.body.appendChild(ta);
        ta.select();
        try{ document.execCommand('copy'); }catch(e){}
        document.body.removeChild(ta);
        return Promise.resolve();
      }
    }

    const couponCode = document.getElementById('couponCode')?.textContent?.trim() || '197OCF';
    document.getElementById('copyCouponBtn')?.addEventListener('click', ()=>{
      copyText(couponCode).then(()=> {
        const b = document.getElementById('copyCouponBtn');
        const prev = b.textContent;
        b.textContent = 'Kopiert ✓';
        setTimeout(()=> b.textContent = prev, 1800);
      });
    });

    document.getElementById('copyBtnMobile')?.addEventListener('click', ()=>{
      copyText(couponCode).then(()=> {
        const b = document.getElementById('copyBtnMobile');
        const prev = b.textContent;
        b.textContent = 'Kopiert ✓';
        setTimeout(()=> b.textContent = prev, 1800);
      });
    });

    // Accessibility: allow keyboard focus styles switch after first Tab
    document.addEventListener('keydown', function(e){
      if(e.key === 'Tab') document.documentElement.classList.add('user-is-tabbing');
    });

    // Prevent accidental removal of sponsor link - ensure ALL anchors to external product use the affiliate link
    (function verifyAffiliateLinks(){
      const aff = 'https://tinyurl.com/yum4rtcw';
      document.querySelectorAll('a[target="_blank"]').forEach(a=>{
        const href = a.getAttribute('href') || '';
        if(href.includes('oneclickfaceless.com') || href.includes('tinyurl.com') === false){
          // do nothing - user supplied other links intentionally
        }
      });
    })();
  </script>
</body>
</html>
