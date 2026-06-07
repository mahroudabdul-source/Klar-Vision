<!DOCTYPE html>  
<html lang="de">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Klar Vision – Fensterreinigung & Gartenpflege</title>  
  <meta name="description" content="Klar Vision – Fensterreinigung innen & außen sowie Gartenpflege in Wendelstein & Nürnberg.">  
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">  
  
  <style>  
    body {  
      margin: 0;  
      font-family: "Poppins", sans-serif;  
      background: #050816;  
      color: #f5f5f5;  
      line-height: 1.6;  
    }  
  
    a { color: inherit; text-decoration: none; }  
  
    /* Navigation */  
    nav {  
      position: sticky;  
      top: 0;  
      background: rgba(5, 8, 22, 0.9);  
      backdrop-filter: blur(10px);  
      padding: 1rem 2rem;  
      display: flex;  
      justify-content: space-between;  
      border-bottom: 1px solid rgba(255,255,255,0.1);  
      z-index: 10;  
    }  
  
    nav .logo {  
      font-weight: 700;  
      font-size: 1.1rem;  
      letter-spacing: 1px;  
    }  
  
    nav .links a {  
      margin-left: 1.5rem;  
      font-size: 0.9rem;  
      opacity: 0.85;  
    }  
  
    nav .links a:hover {  
      opacity: 1;  
    }  
  
    /* Hero */  
    .hero {  
      padding: 5rem 2rem;  
      text-align: center;  
      background: radial-gradient(circle at top, #1f2937, #050816);  
    }  
  
    .hero h1 {  
      font-size: 3rem;  
      margin-bottom: 0.5rem;  
    }  
  
    .hero p {  
      max-width: 650px;  
      margin: 0.5rem auto 1.5rem;  
      color: #d1d5db;  
    }  
  
    .btn {  
      display: inline-block;  
      padding: 0.8rem 1.4rem;  
      border-radius: 50px;  
      font-weight: 600;  
      margin: 0.3rem;  
      transition: 0.2s;  
    }  
  
    .btn-primary {  
      background: linear-gradient(135deg, #22c55e, #16a34a);  
      color: #022c22;  
      box-shadow: 0 10px 25px rgba(34,197,94,0.4);  
    }  
  
    .btn-primary:hover {  
      transform: translateY(-3px);  
    }  
  
    .btn-outline {  
      border: 1px solid #38bdf8;  
      color: #38bdf8;  
    }  
  
    .btn-outline:hover {  
      background: rgba(56,189,248,0.1);  
    }  
  
    /* Sektionen */  
    section {  
      padding: 4rem 2rem;  
      max-width: 1100px;  
      margin: auto;  
    }  
  
    h2 {  
      font-size: 2rem;  
      margin-bottom: 1rem;  
      text-align: center;  
    }  
  
    .section-text {  
      text-align: center;  
      max-width: 650px;  
      margin: 0 auto 2rem;  
      color: #9ca3af;  
    }  
  
    /* Cards */  
    .grid {  
      display: grid;  
      gap: 1.5rem;  
    }  
  
    @media(min-width: 800px) {  
      .grid-3 { grid-template-columns: repeat(3, 1fr); }  
      .grid-2 { grid-template-columns: repeat(2, 1fr); }  
    }  
  
    .card {  
      background: #0a0f1f;  
      padding: 1.5rem;  
      border-radius: 1rem;  
      border: 1px solid rgba(255,255,255,0.05);  
      box-shadow: 0 15px 35px rgba(0,0,0,0.4);  
      transition: 0.25s;  
    }  
  
    .card:hover {  
      transform: translateY(-6px);  
      box-shadow: 0 20px 45px rgba(0,0,0,0.55);  
      border-color: #38bdf8;  
    }  
  
    .card h3 {  
      margin-top: 0;  
    }  
  
    /* Kontakt */  
    .contact-box {  
      background: #0a0f1f;  
      padding: 2rem;  
      border-radius: 1rem;  
      border: 1px solid rgba(255,255,255,0.1);  
      box-shadow: 0 15px 35px rgba(0,0,0,0.4);  
    }  
  
    .contact-box p {  
      margin: 0.4rem 0;  
    }  
  
    /* Footer */  
    footer {  
      text-align: center;  
      padding: 1.5rem;  
      color: #9ca3af;  
      border-top: 1px solid rgba(255,255,255,0.1);  
      margin-top: 3rem;  
    }  
  </style>  
</head>  
  
<body>  
  
  <!-- NAVIGATION -->  
  <nav>  
    <div class="logo">Klar Vision</div>  
    <div class="links">  
      <a href="#leistungen">Leistungen</a>  
      <a href="#preise">Preise</a>  
      <a href="#ueber">Über uns</a>  
      <a href="#kontakt">Kontakt</a>  
    </div>  
  </nav>  
  
  <!-- HERO -->  
  <header class="hero">  
    <h1>Klar Vision</h1>  
    <p>Fensterreinigung & Gartenpflege in Wendelstein und Nürnberg – wir nehmen Ihnen die Arbeit und die Rückenschmerzen ab.</p>  
  
    <a href="#kontakt" class="btn btn-primary">Jetzt anfragen</a>  
    <a href="https://wa.me/491738743203" class="btn btn-outline">WhatsApp schreiben</a>  
  </header>  
  
  <!-- LEISTUNGEN -->  
  <section id="leistungen">  
    <h2>Unsere Leistungen</h2>  
    <p class="section-text">Saubere Fenster, gepflegte Gärten – perfekt für Menschen ab 50+ oder alle, die keine Zeit haben.</p>  
  
    <div class="grid grid-3">  
      <div class="card">  
        <h3>Fensterreinigung innen & außen</h3>  
        <p>Streifenfreie Reinigung aller Fenster – gründlich, zuverlässig und ideal für Wohnungen & Häuser.</p>  
      </div>  
  
      <div class="card">  
        <h3>Schiebetüren & Balkontüren</h3>  
        <p>Große Glasflächen wie Balkontüren reinigen wir innen & außen für klare Sicht und mehr Licht.</p>  
      </div>  
  
      <div class="card">  
        <h3>Gartenpflege</h3>  
        <p>Rasenmähen & Unkraut schneiden – wir halten Ihren Garten sauber und gepflegt.</p>  
      </div>  
    </div>  
  </section>  
  
  <!-- PREISE -->  
  <section id="preise">  
    <h2>Preise</h2>  
    <p class="section-text">Transparente Preise – Sie wissen vorher, was es kostet.</p>  
  
    <div class="grid grid-2">  
      <div class="card">  
        <h3>Einzelpreise</h3>  
        <p><strong>Normales Fenster:</strong> 6 €</p>  
        <p><strong>Schiebetür / Balkontür:</strong> 8 €</p>  
      </div>  
  
      <div class="card">  
        <h3>Monatspaket</h3>  
        <p><strong>ab 44,99 € / Monat</strong></p>  
        <p>Regelmäßige Fensterreinigung – ideal für Senioren & Berufstätige.</p>  
      </div>  
    </div>  
  </section>  
  
  <!-- ÜBER UNS -->  
  <section id="ueber">  
    <h2>Über uns</h2>  
    <p class="section-text">Wir sind Abdul und Jehad Mahrous – Gründer von Klar Vision.</p>  
  
    <div class="card">  
      <p>Wir haben Klar Vision gegründet, um Menschen die körperlich anstrengende Arbeit abzunehmen – besonders denen, die Rückenprobleme haben oder keine Zeit für Fenster & Garten.</p>  
      <p>Wir arbeiten zuverlässig, freundlich und sauber – in Wendelstein, Nürnberg und Umgebung.</p>  
    </div>  
  </section>  
  
  <!-- KONTAKT -->  
  <section id="kontakt">  
    <h2>Kontakt</h2>  
    <p class="section-text">Schreiben Sie uns kurz – wir melden uns schnell zurück.</p>  
  
    <div class="contact-box">  
      <p><strong>Ansprechpartner:</strong> Abdul Mahrous</p>  
      <p><strong>Telefon / WhatsApp:</strong> <a href="tel:+491738743203">+49 173 8743203</a></p>  
      <p><strong>E-Mail:</strong> <a href="mailto:mahroudabdul@gmail.com">mahroudabdul@gmail.com</a></p>  
      <p><strong>Region:</strong> Wendelstein & Nürnberg</p>  
  
      <br>  
      <a href="https://wa.me/491738743203" class="btn btn-primary">Über WhatsApp anfragen</a>  
    </div>  
  </section>  
  
  <!-- FOOTER -->  
  <footer>  
    © <span id="year"></span> Klar Vision – Fensterreinigung & Gartenpflege    
    <br>Impressum folgt  
  </footer>  
  
  <script>  
    document.getElementById("year").textContent = new Date().getFullYear();  
  </script>  
  
</body>  
</html>  
