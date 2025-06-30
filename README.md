<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <title>Herní Svět</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #1b1b1b;
      color: #f0f0f0;
    }

    header {
      background: #111;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      color: #00ffcc;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 25px;
      padding: 10px;
      margin: 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #00ffcc;
    }

    main {
      padding: 30px 20px;
      max-width: 1000px;
      margin: auto;
    }

    section {
      margin-bottom: 60px;
    }

    h2 {
      color: #00ffcc;
      border-bottom: 2px solid #00ffcc;
      padding-bottom: 5px;
    }

    .game-card {
      background: #2a2a2a;
      border-radius: 10px;
      margin-bottom: 20px;
      overflow: hidden;
      box-shadow: 0 0 10px black;
    }

    .game-card img {
      width: 100%;
      height: auto;
    }

    .game-content {
      padding: 15px;
    }

    .btn {
      display: inline-block;
      margin-top: 10px;
      background: #00ffcc;
      color: black;
      padding: 8px 14px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
    }

    .btn:hover {
      background: #00c0a8;
    }

    footer {
      background: #111;
      text-align: center;
      padding: 20px;
      color: #aaa;
    }

    @media (min-width: 700px) {
      .game-list {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 20px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Herní Svět</h1>
    <nav>
      <ul>
        <li><a href="#domu">Domů</a></li>
        <li><a href="#recenze">Recenze</a></li>
        <li><a href="#top">Top Hry</a></li>
        <li><a href="#kontakt">Kontakt</a></li>
      </ul>
    </nav>
  </header>

  <main>

    <!-- Domů -->
    <section id="domu">
      <h2>Novinky</h2>
      <div class="game-list">
        <div class="game-card">
          <img src="https://cdn.cloudflare.steamstatic.com/steam/apps/1091500/header.jpg" alt="Cyberpunk">
          <div class="game-content">
            <h3>Cyberpunk 2077: Phantom Liberty</h3>
            <p>Nové DLC s Idrisem Elbou a temným příběhem v Night City.</p>
            <a href="#" class="btn">Více informací</a>
          </div>
        </div>
        <div class="game-card">
          <img src="https://cdn.cloudflare.steamstatic.com/steam/apps/1245620/header.jpg" alt="Elden Ring">
          <div class="game-content">
            <h3>Elden Ring</h3>
            <p>Nový fantasy svět od tvůrců Dark Souls a George R. R. Martina.</p>
            <a href="#" class="btn">Více informací</a>
          </div>
        </div>
      </div>
    </section>

    <!-- Recenze -->
    <section id="recenze">
      <h2>Recenze</h2>
      <div class="game-card">
        <div class="game-content">
          <h3>The Witcher 3: Divoký hon</h3>
          <p>Epické RPG s příběhem, který tě chytne a nepustí. <strong>Hodnocení: 10/10</strong></p>
          <a href="#" class="btn">Celá recenze</a>
        </div>
      </div>
      <div class="game-card">
        <div class="game-content">
          <h3>Stalker 2: Heart of Chornobyl</h3>
          <p>Postapo atmosféra, realistický survival a výborná grafika. <strong>Hodnocení: 9/10</strong></p>
          <a href="#" class="btn">Celá recenze</a>
        </div>
      </div>
    </section>

    <!-- Top hry -->
    <section id="top">
      <h2>Top Hry</h2>
      <ol>
        <li>Elden Ring</li>
        <li>The Witcher 3</li>
        <li>Baldur's Gate 3</li>
        <li>Cyberpunk 2077</li>
        <li>Hogwarts Legacy</li>
      </ol>
    </section>

    <!-- Kontakt -->
    <section id="kontakt">
      <h2>Kontakt</h2>
      <p>Máš tip, nápad nebo chceš přispět svou recenzí?</p>
      <p>Napiš nám na: <a href="mailto:info@hernisvet.cz">info@hernisvet.cz</a></p>
    </section>

  </main>

  <footer>
    <p>&copy; 2025 Herní Svět. Všechna práva vyhrazena.</p>
  </footer>

</body>
</html>
