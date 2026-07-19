# 🎵 LunexChat

<!DOCTYPE html>
<html lang="fi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LunexChat</title>
    <style>
        body {
            background: linear-gradient(135deg, #0f0c1b 0%, #16122c 50%, #050409 100%);
            color: #f1f1f7;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: block;
        }

        .main-wrapper {
            max-width: 900px;
            margin: 40px auto;
            background: rgba(25, 20, 45, 0.65);
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 24px;
            padding: 30px;
            box-shadow: 0 20px 50px rgba(0, 0, 0, 0.5);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
        }

        .nav-bar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            padding-bottom: 20px;
            margin-bottom: 40px;
        }

        .logo {
            font-size: 1.6rem;
            font-weight: 800;
            background: linear-gradient(45deg, #00ff87 0%, #60efff 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .nav-links {
            display: flex;
            gap: 25px;
        }

        .nav-link {
            font-weight: 600;
            font-size: 1rem;
            color: rgba(255, 255, 255, 0.7);
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            position: relative;
            padding: 5px 0;
        }

        .nav-link:hover {
            color: #60efff;
        }

        .hero-section {
            text-align: center;
            padding: 60px 20px;
        }

        .hero-title {
            font-size: 3.2rem;
            font-weight: 800;
            margin-bottom: 15px;
            background: linear-gradient(180deg, #ffffff 0%, #b5b5c8 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero-subtitle {
            font-size: 1.3rem;
            color: #a09cb1;
            max-width: 600px;
            margin: 0 auto 40px auto;
            line-height: 1.6;
        }

        .divider {
            border: 0;
            height: 1px;
            background: linear-gradient(90deg, rgba(255,255,255,0) 0%, rgba(255,255,255,0.15) 50%, rgba(255,255,255,0) 100%);
            margin: 25px auto;
            width: 80%;
        }

        .cta-button {
            background: linear-gradient(135deg, #00cd52 0%, #00ff68 100%);
            color: #050409;
            border: none;
            padding: 16px 45px;
            font-size: 1.2rem;
            font-weight: 700;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 8px 25px rgba(0, 205, 82, 0.3);
            transition: all 0.3s ease;
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 12px 30px rgba(0, 205, 82, 0.5);
        }

        .info-panel {
            margin-top: 60px;
            padding: 30px;
            background: rgba(255, 255, 255, 0.03);
            border-radius: 16px;
            border: 1px solid rgba(255, 255, 255, 0.05);
        }

        .info-title {
            font-size: 1.4rem;
            color: #ffffff;
            margin-bottom: 15px;
        }

        .info-text {
            color: #a09cb1;
            font-size: 1rem;
            line-height: 1.6;
        }
    </style>
</head>
<body>

<div class="main-wrapper">
    
    <div class="nav-bar">
        <div class="logo">🎵 LunexChat</div>
        <div class="nav-links">
            <span class="nav-link">Musiikki</span>
            <span class="nav-link">Chat</span>
            <span class="nav-link">Profiili</span>
        </div>
    </div>

    <div class="hero-section">
        <h1 class="hero-title">Tervetuloa LunexChatiin</h1>
        <div class="divider"></div>
        <p class="hero-subtitle">Kuuntele parhaita biisejä ja keskustele ystäviesi kanssa samanaikaisesti – täysin uudessa, salamannopeassa ympäristössä.</p>
        
        <button class="cta-button">Aloita</button>
    </div>

    <div class="info-panel">
        <div class="info-title">✨ Tietoa Alustasta</div>
        <p class="info-text">LunexChat on moderni ja itsenäinen mediasovellus. Se toimii suoraan selaimesi sisällä hyödyntäen edistyksellistä LocalStorage-teknologiaa viestien tallentamiseen ilman ulkopuolisia palvelimia tai seurantaa. Julkaistu turvallisesti GitHub Pagesin kautta.</p>
    </div>

</div>

</body>
</html>
