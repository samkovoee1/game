<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Herní Svět</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #1b1b1b;
      color: #f0f0f0;
    }

    header {
      background-color: #111;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: #00ffcc;
    }

    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 10px;
    }

    nav a {
      color: #ffffff;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #00ffcc;
    }

    main {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    section {
      margin-bottom: 60px;
    }

    h2 {
      border-bottom: 2px solid #00ffcc;
      padding-bottom: 5px;
      margin-bottom: 20px;
    }

    .game-card {
      background-color: #2a2a2a;
      border-radius: 10px;
      overflow: hidden;
      margin-bottom: 20px;
      display: flex;
      flex-direction: column;
      box-shadow: 0 0 10px #000;
    }

    .game-card img {
      width: 100%;
      height: auto;
    }

    .game-content {
      padding: 15px;
    }

    .game-content h3 {
      margin-top: 0;
      color: #00ffcc;
    }

    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 15px;
      background-color: #00ffcc;
      color: #000;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
      transition: background-color 0.3s;
    }

    .btn:hover {
      background-color: #00bfa6;
    }

    footer {
      background-color: #111;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
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
        <li><a href="#novinky">Novinky</a></li>
        <li><a href="#recenze">Recenze</a></li>
        <li><a href="#top-hry">Top Hry</a></li>
        <li><a href="#kontakt">Kontakt</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="novinky">
      <h2>Novinky</h2>
      <div class="game-list">
        <div class="game-card">
          <img src="https://cdn.cloudflare.steamstatic.com/steam/apps/1091500/header.jpg" alt="Cyberpunk 2077">
          <div class="game-content">
            <h3>Cyberpunk 2077: Phantom Liberty</h3>
            <p>CD Projekt RED vydává nové rozšíření plné napětí, temné atmosféry a slavného Idrise Elby.</p>
            <a href="#" class="btn">Více informací</a>
          </div>
        </div>
        <div class="game-card">
          <img src="https://cdn.cloudflare.steamstatic.com/steam/apps/1245620/header.jpg" alt="Elden Ring">
          <div class="game-content">
            <h3>Elden Ring</h3>
            <p>Nový fantasy svět od FromSoftware, vytvořený ve spolupráci s G. R. R. Martinem. Těžká, ale spravedlivá výzva.</p>
            <a href="#" class="btn">Více informací</a>
          </div>
        </div>
      </div>
    </section>

    <section id="recenze">
      <h2>Recenze</h2>
      <div class="game-card">
        <div class="game-content">
          <h3>The Witcher 3: Divoký hon</h3>
          <p>Legendární RPG, které i po letech nabízí výborný příběh, atmosféru a skvělý svět. <strong>Hodnocení: 10/10</strong></p>
          <a href="#" class="btn">Celá recenze</a>
        </div>
      </div>
      <div class="game-card">
        <div class="game-content">
          <h3>Stalker 2: Heart of Chornobyl</h3>
          <p>Postapokalyptická zóna ožívá. Atmosféra, přežití a výborná grafika slibují nezapomenutelný zážitek. <strong>Hodnocení: 9/10</strong></p>
          <a href="#" class="btn">Celá recenze</a>
        </div>
      </div>
    </section>

    <section id="top-hry">
      <h2>Top Hry</h2>
      <ul>
        <li>1. Elden Ring</li>
        <li>2. Cyberpunk 2077</li>
        <li>3. Baldur's Gate 3</li>
        <li>4. The Witcher 3</li>
        <li>5. Hogwarts Legacy</li>
      </ul>
    </section>

    <section id="kontakt">
      <h2>Kontakt</h2>
      <p>Chceš nám něco napsat? Máš tip nebo vlastní recenzi? Ozvi se na:  
        <a href="mailto:info@hernisvet.cz">info@hernisvet.cz</a>
      </p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Herní Svět. Všechna práva vyhrazena.</p>
  </footer>
</body>
</html>
