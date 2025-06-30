# game
<!DOCTYPE html>
<html lang="sk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Herný Svet</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Herný Svet</h1>
    <nav>
      <ul>
        <li><a href="#novinky">Novinky</a></li>
        <li><a href="#recenzie">Recenzie</a></li>
        <li><a href="#top-hry">Top Hry</a></li>
        <li><a href="#kontakt">Kontakt</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="novinky">
      <h2>Novinky</h2>
      <p>Najnovšie informácie zo sveta hier. Pravidelne aktualizované články o pripravovaných tituloch.</p>
    </section>

    <section id="recenzie">
      <h2>Recenzie</h2>
      <p>Objektívne recenzie najnovších hier – od AAA titulov po indie klenoty.</p>
    </section>

    <section id="top-hry">
      <h2>Top Hry</h2>
      <ul>
        <li>Cyberpunk 2077: Phantom Liberty</li>
        <li>Elden Ring</li>
        <li>The Witcher 3: Wild Hunt</li>
        <li>Stalker 2</li>
      </ul>
    </section>

    <section id="kontakt">
      <h2>Kontakt</h2>
      <p>Napíš nám na <a href="mailto:info@hernysvet.sk">info@hernysvet.sk</a></p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Herný Svet. Všetky práva vyhradené.</p>
  </footer>
</body>

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
  justify-content: center;
  gap: 30px;
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
  max-width: 800px;
  margin: auto;
}

section {
  margin-bottom: 40px;
}

h2 {
  border-bottom: 2px solid #00ffcc;
  padding-bottom: 5px;
  margin-bottom: 15px;
}
</html>
footer {
  background-color: #111;
  text-align: center;
  padding: 20px;
  margin-top: 40px;
}
