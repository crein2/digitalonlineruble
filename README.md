<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Цифровой рубль 2025: ключевые этапы</title>
    <meta name="description" content="Главные вехи цифровых валют: от Bitcoin до российского CBDC. Актуальность цифрового рубля в 2025 году.">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #2962ff;
            --secondary: #4a148c;
            --accent: #ff6d00;
            --surface: #ffffff;
            --background: url('https://avatars.mds.yandex.net/i?id=772ad1980d57c8d4bdf022e00242756593afad1b-10231558-images-thumbs&n=13') center/cover fixed;
        }

        body {
            font-family: 'Inter', sans-serif;
            margin: 0;
            padding: 0;
            background: var(--background);
            color: #2c3e50;
            line-height: 1.7;
        }

        /* Хедер */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
                        url('https://avatars.mds.yandex.net/i?id=d8abf913df627bbaaef0c4fd6b44ec46_l-3979407-images-thumbs&n=13') center/cover;
            color: white;
            padding: 150px 20px;
            text-align: center;
        }

        .cta-button {
            padding: 18px 45px;
            border-radius: 50px;
            background: var(--primary);
            color: white;
            text-decoration: none;
            font-weight: 700;
            margin: 15px;
            display: inline-block;
            transition: 0.3s;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }

        /* Укороченная история */
        .history-section {
            background: var(--surface);
            border-radius: 20px;
            padding: 40px 20px;
            margin: 40px 0;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        .history-card {
            display: flex;
            gap: 30px;
            margin-bottom: 30px;
            align-items: center;
        }

        .history-icon {
            flex: 0 0 60px;
        }

        .history-icon img {
            width: 45px;
            height: 45px;
            border-radius: 50%;
            border: 2px solid var(--primary);
        }

        /* Актуальность */
        .relevance-section {
            background: linear-gradient(rgba(255,255,255,0.9), rgba(255,255,255,0.9)),
                        url('https://avatars.mds.yandex.net/i?id=a89830aadfe8aa74d11e675bfc2b08f8_l-10452644-images-thumbs&n=13') center/cover;
            border-radius: 20px;
            padding: 40px 20px;
            margin: 60px 0;
        }

        .relevance-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
        }

        .relevance-card {
            background: rgba(255,255,255,0.95);
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .relevance-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 30px rgba(0,0,0,0.15);
        }

        /* Футер */
        .footer {
            background: var(--primary);
            color: white;
            text-align: center;
            padding: 40px 20px;
        }

        .footer-logo {
            width: 100%;
            height: 600px;
            object-fit: cover;
            margin-bottom: 25px;
        }

        @media (max-width: 768px) {
            .footer-logo {
                height: 400px;
            }
        }
    </style>
</head>
<body>
    <!-- Хедер -->
    <section class="hero">
        <h1>Цифровой рубль 2025</h1>
        <p>Новая эра финансовых операций</p>
        <div class="cta-buttons">
            <a href="#history" class="cta-button">История</a>
            <a href="#relevance" class="cta-button">Актуальность</a>
            <a href="https://www.cbr.ru/" target="_blank" class="cta-button" style="background: var(--accent);">ЦБ РФ</a>
        </div>
    </section>

    <!-- Сокращенная история -->
    <section id="history" class="history-section">
        <h2 style="color: var(--secondary); text-align: center;">Краткая история CBDC</h2>
        
        <div class="history-card">
            <div class="history-icon">
                <img src="https://avatars.mds.yandex.net/i?id=3fe87a1d30d12a848df0c7f7e0e01817_l-11042380-images-thumbs&n=13" alt="Bitcoin">
            </div>
            <div>
                <h3>2009</h3>
                <p>Bitcoin — первый шаг к цифровым валютам</p>
            </div>
        </div>
        
        <div class="history-card">
            <div class="history-icon">
                <img src="https://avatars.mds.yandex.net/i?id=3fe87a1d30d12a848df0c7f7e0e01817_l-11042380-images-thumbs&n=13" alt="Китай">
            </div>
            <div>
                <h3>2014</h3>
                <p>Китай запускает цифровой юань</p>
            </div>
        </div>
        
        <div class="history-card">
            <div class="history-icon">
                <img src="https://avatars.mds.yandex.net/i?id=3fe87a1d30d12a848df0c7f7e0e01817_l-11042380-images-thumbs&n=13" alt="Россия">
            </div>
            <div>
                <h3>2017</h3>
                <p>ЦБ РФ начинает исследования CBDC</p>
            </div>
        </div>
    </section>

    <!-- Актуальность -->
    <section id="relevance" class="relevance-section">
        <h2 style="color: var(--secondary); text-align: center;">Зачем нужен цифровой рубль?</h2>
        
        <div class="relevance-grid">
            <div class="relevance-card">
                <h3>Безопасность</h3>
                <p>Снижение теневых операций на 70%</p>
            </div>
            
            <div class="relevance-card">
                <h3>Технологии</h3>
                <p>Блокчейн с квантовой защитой</p>
            </div>
            
            <div class="relevance-card">
                <h3>Глобальность</h3>
                <p>Поддержка 20+ валют в SWIFT</p>
            </div>
        </div>
    </section>

    <!-- Футер -->
    <footer class="footer">
        <img src="https://dpru.obs.ru-moscow-1.hc.sbercloud.ru/images/article/2023/07/19/ad4afa0f-d3e4-44cc-b3d6-3fbdb4972355.jpg" 
             alt="Цифровой рубль 2025"
             class="footer-logo">
        <p>© 2025 Цифровая экономика. Все права защищены</p>
        <p>
            <a href="https://www.cbr.ru/" target="_blank" style="color: white; text-decoration: underline;">
                Официальный сайт ЦБ РФ
            </a>
        </p>
    </footer>
</body>
</html>
