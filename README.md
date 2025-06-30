<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Herní Svět</title>
  <link rel="stylesheet" href="style.css" />
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
      <p>Nejnovější zprávy ze světa videoher. Sleduj připravované tituly, oznámení a trailery.</p>
    </section>

    <section id="recenze">
      <h2>Recenze</h2>
      <p>Upřímné a detailní recenze nejnovějších her. Poradíme, co stojí za to si zahrát.</p>
    </section>

    <section id="top-hry">
      <h2>Top Hry</h2>
      <ul>
        <li>Cyberpunk 2077: Phantom Liberty</li>
        <li>Elden Ring</li>
        <li>The Witcher 3: Divoký hon</li>
        <li>Stalker 2: Heart of Chornobyl</li>
      </ul>
    </section>

    <section id="kontakt">
      <h2>Kontakt</h2>
      <p>Napiš nám na <a href="mailto:samprediger10@gmail.com">samprediger10@gmail.com</a></p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Herní Svět. Všechna práva vyhrazena.</p>
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

footer {
  background-color: #111;
  text-align: center;
  padding: 20px;
  margin-top: 40px;
}
</html>
