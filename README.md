<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zeste Energy - Officiel</title>
    <style>
        :root {
            --brand-green: #4caf50;
            --brand-yellow: #ffcc00;
            --dark-bg: #0b0b0b;
            --card-bg: #1a1a1a;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--dark-bg);
            color: #ffffff;
            line-height: 1.6;
        }

        /* --- EN-TÊTE --- */
        header {
            background: #000;
            padding: 30px 20px;
            text-align: center;
            border-bottom: 3px solid var(--brand-green);
        }

        .logo-img {
            max-width: 350px;
            height: auto;
            display: block;
            margin: 0 auto;
        }

        /* --- HERO SECTION --- */
        .hero {
            padding: 80px 20px;
            text-align: center;
            background: radial-gradient(circle at center, #1a3a1a 0%, #000 100%);
        }

        .promo-badge {
            background: var(--brand-yellow);
            color: #000;
            padding: 10px 25px;
            font-weight: 900;
            text-transform: uppercase;
            font-size: 1.4rem;
            display: inline-block;
            transform: skewX(-10deg);
            margin-bottom: 25px;
            box-shadow: 4px 4px 0px var(--brand-green);
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        /* --- CONTENT --- */
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin-top: 50px;
        }

        .card {
            background: var(--card-bg);
            padding: 30px;
            border-radius: 15px;
            border-left: 5px solid var(--brand-green);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-10px);
            border-left-color: var(--brand-yellow);
        }

        .card h3 {
            color: var(--brand-yellow);
            margin-top: 0;
            text-transform: uppercase;
        }

        /* --- OFFRES --- */
        .offer-section {
            background: linear-gradient(135deg, #111 0%, #222 100%);
            border: 2px dashed var(--brand-yellow);
            border-radius: 20px;
            padding: 50px;
            margin: 60px 0;
            text-align: center;
        }

        .cta-button {
            display: inline-block;
            background: var(--brand-yellow);
            color: #000;
            padding: 20px 50px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 50px;
            font-size: 1.3rem;
            margin-top: 30px;
            transition: 0.3s;
            text-transform: uppercase;
        }

        footer {
            background: #000;
            padding: 60px 20px;
            text-align: center;
            border-top: 1px solid #333;
        }

        @media (max-width: 600px) {
            .logo-img { max-width: 80% !important; }
            .hero h1 { font-size: 2rem; }
        }
    </style>
</head>
<body>

    <header>
        <img src="logo.png" alt="Logo Zeste" class="logo-img">
    </header>

    <section class="hero">
        <div class="promo-badge">promotion de lancement exclusive de la marque zeste !</div>
        <h1>Réveille tes sens , sans les casser</h1>
        <p style="font-size: 1.2rem; max-width: 700px; margin: 20px auto; color: #ccc;">
            Zeste est la boisson énergisante conçue pour booster ton énergie naturellement. 
        </p>
    </section>

    <div class="container">
        <div class="grid">
            <div class="card">
                <h3>⚡ Énergie Rapide</h3>
                <p>Un coup de boost immédiat pour vos journées intenses.</p>
            </div>
            <div class="card">
                <h3>🍃 Goût Frais</h3>
                <p>Une saveur unique qui désaltère en profondeur.</p>
            </div>
        </div>

        <div class="offer-section">
            <h2 style="color: var(--brand-yellow);">Promotions de Lancement de la boisson zeste</h2>
            <p>1 ACHETÉE = LA 2ÈME À -50%</p>
            <a href="#" class="cta-button">participez à la promotion dès maintenant</a>
        </div>
    </div>

    <footer>
        <p>Instagram: @zeste.energy | WhatsApp: +237 689 758 471</p>
        <p style="font-size: 0.8rem; color: #555;">*À consommer avec modération.</p>
    </footer>

</body>
</html>
