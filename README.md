<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RDKS Service | Sensoren Auslesen & Programmieren fehler auslessen und löschen mit Diagnosegeräht </title>
    <style>
        :root {
            --primary: #2c3e50;
            --accent: #e74c3c;
            --light: #f4f4f4;
            --dark: #333;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            line-height: 1.6;
            color: var(--dark);
        }

        header {
            background: white(--primary);
            color: white;
            padding: 2rem 0;
            text-align: center;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 2rem 0;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            border-top: 5px solid var(--accent);
        }

        .hero {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                        url('https://images.unsplash.com/photo-1544133782-454508216892?auto=format&fit=crop&w=1200&q=80');
            background-size: cover;
            color: white;
            padding: 100px 0;
            text-align: center;
        }

        h2 { color: var(--primary); }

        .btn {
            display: inline-block;
            background: var(--accent);
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }

        footer {
            background: var(--primary);
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

<header>
    <h1>RDKS & TPMS Profi-Service Cosimo & Giuseppe</h1>
    <p>Sicherheit und Präzision für Ihre Reifen</p>
</header>

<section class="hero">
    <div class="container">
        <h2>Reifendrucksensoren defekt oder neue Räder?</h2>
        <p>Wir lesen Ihre Sensoren aus, programmieren neue IDs oder klonen Ihre vorhandenen Sensoren für den Winterradsatz.</p>
        <a href="#kontakt" class="btn">Jetzt Termin vereinbaren</a>
    </div>
</section>

<div class="container">
    <div class="grid">
        <div class="card">
            <h3>🔍 Sensoren auslesen</h3>
            <p>Wir prüfen den Batteriestatus, die Temperatur und den aktuellen Druck Ihrer Sensoren, ohne den Reifen zu demontieren.</p>
            <ul>
                <li>Fehlerdiagnose bei Warnleuchte</li>
                <li>Batteriezustand prüfen</li>
                <li>ID-Identifikation</li>
            </ul>
        </div>

        <div class="card">
            <h3>💻 Programmierung</h3>
            <p>Neue Universalsensoren müssen auf Ihr Fahrzeug angelernt werden. Wir beherrschen alle gängigen Protokolle.</p>
            <ul>
                <li>Anlernen neuer Sensoren</li>
                <li>Klonen von Original-IDs</li>
                <li>Einstellung von Sollwerten</li>
            </ul>
        </div>
    </div>
</div>

<section id="kontakt" style="background: var(--light); padding: 3rem 0;">
    <div class="container">
        <h2 style="text-align:center;">Kontaktanfrage</h2>
        <form style="max-width: 600px; margin: auto; display: flex; flex-direction: column; gap: 10px;">
            <input type="text" placeholder="Name" style="padding: 10px;">
            <input type="text" placeholder="Fahrzeugmodell & Baujahr" style="padding: 10px;">
            <textarea placeholder="Ihre Nachricht (z.B. Neue Winterräder)" style="padding: 10px; height: 100px;"></textarea>
            <button type="submit" class="btn" style="border:none; cursor:pointer;">Anfrage senden</button>
        </form>
    </div>
</section>

<footer>
    <p>&copy; 2026 RDKS Service Meisterbetrieb | Ihr Partner für Reifensicherheit</p>
</footer>

</body>
</html>
