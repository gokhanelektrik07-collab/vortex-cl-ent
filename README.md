<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vortex Client | Bloxd.io Customization</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0a0a0a;
            color: white;
            text-align: center;
        }
        header {
            padding: 100px 20px;
            background: linear-gradient(180deg, #00dbde 0%, #0a0a0a 100%);
        }
        h1 { font-size: 3rem; margin: 0; text-shadow: 0 0 20px #00dbde; }
        p { color: #ccc; font-size: 1.2rem; }
        .container { padding: 50px 20px; }
        .feature-card {
            background: #151515;
            border: 1px solid #333;
            padding: 20px;
            margin: 10px;
            border-radius: 15px;
            display: inline-block;
            width: 250px;
            transition: 0.3s;
        }
        .feature-card:hover { border-color: #00dbde; transform: translateY(-5px); }
        .download-btn {
            background-color: #00dbde;
            color: black;
            padding: 15px 40px;
            font-size: 1.5rem;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            display: inline-block;
            margin-top: 30px;
            box-shadow: 0 0 15px #00dbde;
        }
        .instructions {
            background: #111;
            padding: 30px;
            margin-top: 50px;
            border-radius: 20px;
            text-align: left;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }
        code { background: #222; padding: 2px 5px; color: #ff00ff; }
    </style>
</head>
<body>

    <header>
        <h1>VORTEX CLIENT</h1>
        <p>Bloxd.io Deneyimini Kişiselleştirin</p>
        <a href="#" class="download-btn">KODU KOPYALA</a>
    </header>

    <div class="container">
        <div class="feature-card">
            <h3>Özel Arayüz</h3>
            <p>Menü renklerini ve görünümünü tamamen değiştirin.</p>
        </div>
        <div class="feature-card">
            <h3>Veller & Cape</h3>
            <p>Kendi pelerinini ve görsel efektlerini ekle.</p>
        </div>
        <div class="feature-card">
            <h3>Hızlı Erişim</h3>
            <p>"V" tuşu ile menüyü anında aç veya kapat.</p>
        </div>

        <div class="instructions">
            <h3>Nasıl Kurulur?</h3>
            <ol>
                <li>Önce Chrome Mağazası'ndan <b>Tampermonkey</b> yükleyin.</li>
                <li>Sitemizdeki <b>Kodu Kopyala</b> butonuna basın.</li>
                <li>Tampermonkey'de "Yeni Script" oluşturun ve yapıştırın.</li>
                <li>Bloxd.io'ya girin ve <b>V</b> tuşuna basın!</li>
            </ol>
        </div>
    </div>

    <footer style="margin-top: 50px; padding: 20px; color: #555;">
        Vortex Client &copy; 2026 - Herkes için Özelleştirme
    </footer>

</body>
</html>
