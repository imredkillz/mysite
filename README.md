<!doctype html>
<html lang="it">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta
    name="description"
    content="Portfolio di Accanito, developer con esperienza in TypeScript, JavaScript e C++."
  >
  <title>Accanito — Developer</title>

  <style>
    :root {
      color-scheme: dark;
      --background: #101010;
      --surface: #181818;
      --text: #f3f3f3;
      --muted: #a4a4a4;
      --accent: #b7f36b;
      --border: #2b2b2b;
      --content-width: 860px;
    }

    * {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      background: var(--background);
      color: var(--text);
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
        sans-serif;
      line-height: 1.7;
    }

    a {
      color: inherit;
    }

    a:focus-visible {
      outline: 2px solid var(--accent);
      outline-offset: 4px;
    }

    .container {
      width: min(var(--content-width), calc(100% - 40px));
      margin-inline: auto;
    }

    header {
      border-bottom: 1px solid var(--border);
    }

    .topbar {
      min-height: 72px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 24px;
    }

    .brand {
      font-weight: 700;
      text-decoration: none;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    nav a {
      color: var(--muted);
      font-size: 0.94rem;
      text-decoration: none;
    }

    nav a:hover {
      color: var(--accent);
    }

    .hero {
      padding-block: 100px 84px;
    }

    .eyebrow {
      margin-bottom: 12px;
      color: var(--accent);
      font-size: 0.9rem;
      font-weight: 650;
      letter-spacing: 0.08em;
      text-transform: uppercase;
    }

    h1,
    h2,
    h3 {
      margin-top: 0;
    }

    h1 {
      margin-bottom: 12px;
      font-size: clamp(2.8rem, 8vw, 5rem);
      letter-spacing: -0.07em;
      line-height: 1.05;
    }

    .subtitle {
      margin-bottom: 20px;
      color: var(--muted);
      font-size: clamp(1.2rem, 3vw, 1.6rem);
    }

    .intro,
    .section-copy {
      max-width: 680px;
      color: var(--muted);
    }

    .intro {
      margin-bottom: 28px;
      font-size: 1.1rem;
    }

    .button {
      display: inline-block;
      padding: 10px 16px;
      border: 1px solid var(--accent);
      border-radius: 6px;
      background: var(--accent);
      color: var(--background);
      font-weight: 650;
      text-decoration: none;
    }

    .button:hover {
      background: transparent;
      color: var(--accent);
    }

    section:not(.hero) {
      padding-block: 42px;
      border-top: 1px solid var(--border);
    }

    section h2 {
      margin-bottom: 20px;
      font-size: 1.65rem;
      letter-spacing: -0.04em;
    }

    .project {
      padding: 24px;
      border: 1px solid var(--border);
      border-radius: 10px;
      background: var(--surface);
    }

    .project h3 {
      margin-bottom: 10px;
      font-size: 1.25rem;
    }

    .project p,
    .project-details {
      color: var(--muted);
    }

    .project-details {
      display: flex;
      flex-wrap: wrap;
      gap: 8px 24px;
      margin-top: 18px;
      font-size: 0.95rem;
    }

    .project-details strong {
      color: var(--text);
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      padding: 0;
      list-style: none;
    }

    .skills li {
      padding: 6px 12px;
      border: 1px solid var(--border);
      border-radius: 999px;
      background: var(--surface);
      color: var(--muted);
    }

    footer {
      padding-block: 24px;
      border-top: 1px solid var(--border);
      color: var(--muted);
      font-size: 0.9rem;
    }

    @media (max-width: 560px) {
      .topbar {
        align-items: flex-start;
        flex-direction: column;
        justify-content: center;
        padding-block: 18px;
      }

      nav {
        gap: 14px;
      }

      .hero {
        padding-block: 72px 60px;
      }

      .project {
        padding: 18px;
      }
    }

    @media (prefers-reduced-motion: reduce) {
      html {
        scroll-behavior: auto;
      }
    }
  </style>
</head>

<body>
  <header>
    <div class="container topbar">
      <a class="brand" href="#inizio">Accanito</a>

      <nav aria-label="Navigazione principale">
        <a href="#chi-sono">Chi sono</a>
        <a href="#progetti">Progetti</a>
        <a href="#competenze">Competenze</a>
        <a href="#contatti">Contatti</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero" id="inizio">
      <p class="eyebrow">Portfolio personale</p>
      <h1>Ciao, sono Accanito.</h1>
      <p class="subtitle">Developer · TypeScript · JavaScript · C++</p>
      <p class="intro">
        Programmo da 4 anni e realizzo progetti software, tra cui bot
        personalizzati per community online.
      </p>
      <a class="button" href="#progetti">Scopri i miei progetti</a>
    </section>

    <section id="chi-sono">
      <h2>Chi sono</h2>
      <p class="section-copy">
        Sono Accanito, developer con 4 anni di esperienza pratica. Lavoro con
        TypeScript, JavaScript e C++. Mi piace sviluppare progetti in autonomia
        e creare strumenti utili per le community online.
      </p>
    </section>

    <section id="progetti">
      <h2>Progetti</h2>

      <article class="project">
        <h3>HeartlessItalia</h3>
        <p>
          Community Discord con oltre 3.000 membri, supportata da un bot
          personalizzato che ho sviluppato interamente da solo. Il bot aiuta
          nella gestione del server e offre funzionalità di intrattenimento
          per la community.
        </p>

        <div class="project-details">
          <span><strong>Ruolo:</strong> sviluppo completo del bot</span>
          <span><strong>Tecnologie:</strong> TypeScript, JavaScript</span>
        </div>
      </article>
    </section>

    <section id="competenze">
      <h2>Competenze</h2>
      <ul class="skills">
        <li>TypeScript</li>
        <li>JavaScript</li>
        <li>C++</li>
        <li>Sviluppo di bot personalizzati</li>
      </ul>
    </section>

    <section id="contatti">
      <h2>Contatti</h2>
      <p class="section-copy">
        I link ai miei profili e i contatti saranno aggiunti prossimamente.
      </p>
    </section>
  </main>

  <footer>
    <div class="container">
      © <span id="anno"></span> Accanito
    </div>
  </footer>

  <script>
    document.getElementById("anno").textContent = new Date().getFullYear();
  </script>
</body>
</html>