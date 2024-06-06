<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meine Webseite</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #0056b3;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        footer {
            background-color: #007BFF;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Willkommen auf meiner Webseite</h1>
    </header>
    <nav>
        <a href="#empfehlungen">Empfehlungen</a>
        <a href="#verkauf">Verkauf</a>
        <a href="#leben">Schönes Leben</a>
    </nav>
    <div class="container">
        <div id="empfehlungen" class="section">
            <h2>Produkte empfehlen</h2>
            <p>Hier teile ich meine Lieblingsprodukte mit euch, die ich wärmstens empfehlen kann.</p>
            <!-- Beispielprodukte -->
            <ul>
                <li>Produkt 1: Beschreibung des Produkts 1</li>
                <li>Produkt 2: Beschreibung des Produkts 2</li>
                <li>Produkt 3: Beschreibung des Produkts 3</li>
            </ul>
        </div>
        <div id="verkauf" class="section">
            <h2>Klamotten verkaufen</h2>
            <p>Entdecke meine exklusiven Kleidungsstücke, die ich zum Verkauf anbiete.</p>
            <!-- Beispielprodukte -->
            <ul>
                <li>Kleidungsstück 1: Beschreibung des Kleidungsstücks 1</li>
                <li>Kleidungsstück 2: Beschreibung des Kleidungsstücks 2</li>
                <li>Kleidungsstück 3: Beschreibung des Kleidungsstücks 3</li>
            </ul>
        </div>
        <div id="leben" class="section">
            <h2>Ein schönes Leben zubereiten</h2>
            <p>Tipps und Ratschläge, wie man ein glückliches und erfülltes Leben führen kann.</p>
            <!-- Beispieltipps -->
            <ul>
                <li>Tipp 1: Beschreibung des Tipps 1</li>
                <li>Tipp 2: Beschreibung des Tipps 2</li>
                <li>Tipp 3: Beschreibung des Tipps 3</li>
            </ul>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Meine Webseite. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>
