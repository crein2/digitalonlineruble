<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Цифровой рубль 2025: визуальная эволюция</title>
    <meta name="description" content="История цифровых валют и преимущества цифрового рубля в 2025 году. Графическая визуализация этапов развития.">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #2962ff;
            --secondary: #4a148c;
            --accent: #ff6d00;
            --surface: #ffffff;
        }

        body {
            font-family: 'Inter', sans-serif;
            margin: 0;
            padding: 0;
            color: #2c3e50;
            line-height: 1.7;
        }

        /* Хедер с ПЕРВЫМ изображением */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)),
                        url('https://avatars.mds.yandex.net/i?id=d8abf913df627bbaaef0c4fd6b44ec46_l-3979407-images-thumbs&n=13') center/cover;
            color: white;
            padding: 150px 20px;
            text-align: center;
        }

        /* История с ВТОРЫМ изображением */
        .history-section {
            background: var(--surface);
            border-radius: 20px;
            padding: 60px 20px;
            margin: 40px 0;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        .history-card {
            display: flex;
            gap: 30px;
            margin-bottom: 40px;
            align-items: center;
        }

        .history-icon {
            flex: 0 0 80px;
        }

        .history-icon img {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            border: 3px solid var(--primary);
        }

        /* Актуальность с ТРЕТЬИМ изображением */
        .relevance-section {
            background: linear-gradient(rgba(255,255,255,0.9), rgba(255,255,255,0.9)),
                        url('https://avatars.mds.yandex.net/i?id=a89830aadfe8aa74d11e675bfc2b08f8_l-10452644-images-thumbs&n=13') center/cover;
            border-radius: 20px;
            padding: 60px 20px;
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
            padding: 40px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
        }

        /* Футер с ЧЕТВЕРТЫМ изображением */
        .footer {
            background: url('https://dpru.obs.ru-moscow-1.hc.sbercloud.ru/images/article/2023/07/19/ad4afa0f-d3e4-44cc-b3d6-3fbdb4972355.jpg') center/cover;
            color: white;
            text-align: center;
            padding: 120px 20px;
        }

        .footer-logo {
            width: 200px;
            margin: 0 auto 25px;
            display: block;
        }
    </style>
</head>
<body>
    <!-- Хедер с ПЕРВЫМ изображением -->
    <section class="hero">
        <h1>Цифровой рубль 2025</h1>
        <p>Новая реальность финансовых операций</p>
        <div class="cta-buttons">
            <a href="#history" class="cta-button">История</a>
            <a href="#relevance" class="cta-button">Актуальность</a>
            <a href="https://www.cbr.ru/" target="_blank" class="cta-button" style="background: var(--accent);">ЦБ РФ</a>
        </div>
    </section>

    <!-- История с ВТОРЫМ изображением -->
    <section id="history" class="history-section">
        <h2 style="color: var(--secondary); text-align: center;">История цифровых денег</h2>
        
        <div class="history-card">
            <div class="history-icon">
                <img src="https://avatars.mds.yandex.net/i?id=3fe87a1d30d12a848df0c7f7e0e01817_l-11042380-images-thumbs&n=13" alt="Древние деньги">
            </div>
            <div>
                <h3>3000 г. до н.э.</h3>
                <p>Первые металлические монеты</p>
            </div>
        </div>
        
        <div class="history-card">
            <div class="history-icon">
                <img src="https://avatars.mds.yandex.net/i?id=3fe87a1d30d12a848df0c7f7e0e01817_l-11042380-images-thumbs&n=13" alt="Bitcoin">
            </div>
            <div>
                <h3>2009 г.</h3>
                <p>Bitcoin - отправная точка CBDC</p>
            </div>
        </div>
        
        <div class="history-card">
            <div class="history-icon">
                <img src="https://avatars.mds.yandex.net/i?id=3fe87a1d30d12a848df0c7f7e0e01817_l-11042380-images-thumbs&n=13" alt="Китай">
            </div>
            <div>
                <h3>2014 г.</h3>
                <p>Запуск цифрового юаня</p>
            </div>
        </div>
    </section>

    <!-- Актуальность с ТРЕТЬИМ изображением -->
    <section id="relevance" class="relevance-section">
        <h2 style="color: var(--secondary); text-align: center;">Зачем нужен цифровой рубль?</h2>
        
        <div class="relevance-grid">
            <div class="relevance-card">
                <h3>Безопасность</h3>
                <p>Криптографическая защита уровня ЦБ</p>
            </div>
            
            <div class="relevance-card">
                <h3>Госинтеграция</h3>
                <p>Связь с 50+ государственными сервисами</p>
            </div>
            
            <div class="relevance-card">
                <h3>Международность</h3>
                <p>Поддержка 20+ валют в SWIFT</p>
            </div>
        </div>
    </section>

    <!-- Футер с ЧЕТВЕРТЫМ изображением -->
    <footer class="footer">
        <img src="https://avatars.mds.yandex.net/i?id=d8abf913df627bbaaef0c4fd6b44ec46_l-3979407-images-thumbs&n=13" 
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
