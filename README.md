
<html lang="de">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Impressum</title>
  <meta name="robots" content="index,follow">
  <style>
    :root { --bg: #0b0c0f; --card: #12141a; --text: #e7e9ee; --muted:#9aa3b2; --accent:#7aa2ff; }
    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body { margin: 0; font-family: system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, "Helvetica Neue", Arial, "Apple Color Emoji", "Segoe UI Emoji"; background: var(--bg); color: var(--text); line-height: 1.6; }
    .wrap { max-width: 720px; margin: 6rem auto; padding: 0 1.25rem; }
    .card { background: linear-gradient(180deg, rgba(255,255,255,0.04), rgba(255,255,255,0.02)); border: 1px solid rgba(255,255,255,0.08); border-radius: 16px; padding: 2rem; box-shadow: 0 10px 30px rgba(0,0,0,0.2); }
    h1 { font-size: clamp(1.75rem, 2.2vw, 2.25rem); letter-spacing: 0.2px; margin: 0 0 0.75rem; }
    h2 { font-size: 1.05rem; text-transform: uppercase; letter-spacing: 0.12em; color: var(--muted); margin: 2rem 0 0.5rem; }
    p { margin: 0.25rem 0; }
    a { color: var(--accent); text-decoration: none; }
    a:focus, a:hover { text-decoration: underline; }
    .muted { color: var(--muted); }
    .row { display: grid; grid-template-columns: 1fr; gap: 0.25rem; }
    .footer { margin-top: 2rem; font-size: .875rem; color: var(--muted); }
    .addr-img { display:block; margin: .5rem 0; max-width: 100%; height:auto; border-radius: 8px; border:1px dashed rgba(255,255,255,0.12); padding:.5rem; }
    .chip { display:inline-block; font-size:.8rem; padding:.25rem .5rem; border:1px solid rgba(255,255,255,0.14); border-radius:999px; color:var(--muted); }
    .sr-only { position:absolute; width:1px; height:1px; padding:0; margin:-1px; overflow:hidden; clip:rect(0,0,0,0); border:0; }
  </style>
</head>
<body>
  <div class="wrap">
    <main class="card" role="main">
      <div class="chip" aria-hidden="true">Angaben gemäß § 5 TMG</div>
      <h1>Impressum</h1>

      <section aria-labelledby="inhaber">
        <h2 id="inhaber">Diensteanbieter</h2>
        <div class="row">
          <p><strong>Heros Hajetschek</strong></p>

          <p class="addr-text">Hauptstr. 100<br>76327 Pfinztal</p>

          <p class="sr-only">Adresse: Hauptsr. 100, 76327 Pfinztal</p>
        </div>
      </section>

      <section aria-labelledby="kontakt">
        <h2 id="kontakt">Kontakt</h2>
        <p>E-Mail: <a href="mailto:heros5k.business@gmail.com">heros5k.business@gmail.com</a></p>
      </section>

      <section aria-labelledby="ust">
      </section>

      <section aria-labelledby="verantwortlich">
        <h2 id="verantwortlich">Verantwortlich für den Inhalt (§ 55 Abs. 2 RStV / MStV)</h2>
        <p>Heros Hajetschek, Hauptstr. 100, 76327 Pfinztal</p>
      </section>

      <section aria-labelledby="haftung">
        <h2 id="haftung">Haftungsausschluss</h2>
        <p>
          Die Inhalte dieser Seite wurden mit größter Sorgfalt erstellt. Für die Richtigkeit, Vollständigkeit und Aktualität der Inhalte übernehme ich keine Gewähr. 
          Als Diensteanbieter bin ich gemäß § 7 Abs. 1 TMG für eigene Inhalte auf diesen Seiten nach den allgemeinen Gesetzen verantwortlich. Nach §§ 8 bis 10 TMG 
          bin ich jedoch nicht verpflichtet, übermittelte oder gespeicherte fremde Informationen zu überwachen oder nach Umständen zu forschen, die auf eine 
          rechtswidrige Tätigkeit hinweisen. Verpflichtungen zur Entfernung oder Sperrung der Nutzung von Informationen nach den allgemeinen Gesetzen bleiben 
          hiervon unberührt. Eine diesbezügliche Haftung ist jedoch erst ab dem Zeitpunkt der Kenntnis einer konkreten Rechtsverletzung möglich. Bei Bekanntwerden 
          von entsprechenden Rechtsverletzungen werde ich diese Inhalte umgehend entfernen.
        </p>
      </section>

      <p class="footer">Letzte Aktualisierung: <time datetime="2025-08-14">14.08.2025</time></p>
    </main>

    <!-- Strukturierte Daten (optional – suchmaschinenfreundlich). Platzhalter ersetzen oder Block entfernen. -->
    <script type="application/ld+json">
      {
        "@context": "https://schema.org",
        "@type": "Person",
        "name": "[Dein vollständiger Name]",
        "address": {
          "@type": "PostalAddress",
          "streetAddress": "[Straße und Hausnummer]",
          "postalCode": "[PLZ]",
          "addressLocality": "[Ort]",
          "addressCountry": "DE"
        },
        "email": "mailto:[deine-email@domain.de]"
      }
    </script>
  </div>
</body>
</html>
