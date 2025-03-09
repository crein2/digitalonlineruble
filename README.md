<html lang="ru">
<head>
    <!-- Основные метатеги -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Цифровой рубль 2025: официальный гайд, технологии, интеграция</title>
    <meta name="description" content="Полное руководство по цифровому рублю: блокчейн ЦБ РФ, преимущества для бизнеса и граждан, этапы внедрения до 2025 года. Официальная информация и сравнение с криптовалютами.">
    <meta name="keywords" content="цифровой рубль, ЦБ РФ, блокчейн, смарт-контракты, цифровая валюта, финтех, 2025, IoT, платежные системы">

    <!-- Социальные метатеги -->
    <meta property="og:title" content="Цифровой рубль 2025: будущее финансов">
    <meta property="og:description" content="Узнайте о новой форме национальной валюты: технологии, законы, преимущества.">
    <meta property="og:type" content="website">
    <meta property="og:image" content="https://example.com/digital-ruble-banner.jpg">
    <meta property="og:url" content="https://example.com/digital-ruble">

    <!-- Подключение ресурсов -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
    <style>
        :root {
            --primary: #2962ff;
            --secondary: #4a148c;
            --accent: #ff6d00;
            --surface: #ffffff;
            --background: #f5f5f5;
        }

        body {
            font-family: 'Inter', sans-serif;
            margin: 0;
            padding: 0;
            background: var(--background);
            color: #2c3e50;
            line-height: 1.7;
        }

        /* Хедер с фоновым изображением */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
                        url('https://example.com/digital-ruble-bg.jpg') center/cover;
            color: white;
            padding: 120px 20px;
            text-align: center;
            position: relative;
        }

        .hero-logo {
            position: absolute;
            top: 20px;
            right: 20px;
            width: 120px;
            height: auto;
        }

        .hero h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        .cta-buttons {
            margin-top: 40px;
        }

        .cta-button {
            padding: 15px 40px;
            border-radius: 40px;
            text-decoration: none;
            font-weight: 700;
            transition: 0.3s;
            margin: 10px;
            display: inline-block;
        }

        /* Секция с преимуществами */
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            padding: 60px 20px;
        }

        .feature-card {
            background: white;
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
            transition: 0.3s;
            text-align: center;
        }

        .feature-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 12px 30px rgba(0,0,0,0.2);
        }

        .feature-icon {
            width: 80px;
            height: 80px;
            margin: 0 auto 25px;
            background: var(--primary);
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2em;
        }

        /* Дорожная карта */
        .timeline {
            background: var(--surface);
            border-radius: 20px;
            padding: 60px 20px;
            margin: 60px 0;
        }

        .timeline-item {
            display: flex;
            gap: 30px;
            margin-bottom: 50px;
            align-items: center;
        }

        .timeline-icon {
            flex: 0 0 60px;
            text-align: center;
        }

        .timeline-icon img {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            background: var(--primary);
            padding: 10px;
        }

        /* Сравнительная таблица */
        .compare-section {
            padding: 60px 20px;
        }

        .compare-container {
            max-width: 1200px;
            margin: 0 auto;
            overflow-x: auto;
        }

        .compare-table {
            width: 100%;
            border-collapse: collapse;
            min-width: 800px;
        }

        .compare-table th {
            background: var(--primary);
            color: white;
            padding: 20px;
            white-space: nowrap;
        }

        .compare-table td {
            padding: 15px;
            border-bottom: 1px solid #eee;
        }

        /* Футер */
        .footer {
            background: var(--primary);
            color: white;
            text-align: center;
            padding: 40px;
        }

        .footer-logo {
            width: 150px;
            margin-bottom: 20px;
        }

        /* Адаптивность */
        @media (max-width: 768px) {
            .hero {
                padding: 80px 20px;
            }
            
            .timeline-item {
                flex-direction: column;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <!-- Хедер с фоном и логотипом -->
    <section class="hero">
        <img src="https://example.com/cbr-logo.png" 
             alt="Центральный Банк РФ" 
             class="hero-logo">
        <h1>Цифровой рубль 2025</h1>
        <p>Новая эра финансовых технологий - безопасность, скорость, инновации</p>
        <div class="cta-buttons">
            <a href="#technology" class="cta-button" style="background: var(--primary); color: white;">Технологии</a>
            <a href="https://www.cbr.ru/" target="_blank" class="cta-button" style="background: var(--accent); color: white;">ЦБ РФ</a>
        </div>
    </section>

    <!-- Технологии -->
    <section id="technology">
        <div class="features-grid">
            <div class="feature-card">
                <div class="feature-icon">🔗</div>
                <h3>Блокчейн</h3>
                <p>Гибридная система с поддержкой смарт-контрактов</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">💳</div>
                <h3>Кошельки</h3>
                <p>Мобильные приложения и смарт-карты с NFC</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">📜</div>
                <h3>Законодательство</h3>
                <p>ФЗ № 259-ФЗ и другие правовые акты</p>
            </div>
        </div>
    </section>

    <!-- Дорожная карта -->
    <section class="timeline">
        <h2 style="color: var(--secondary); text-align: center;">Планы внедрения</h2>
        <div class="timeline-item">
            <div class="timeline-icon">
                <img src="https://example.com/2022-icon.png" alt="2022">
            </div>
            <div>
                <h3>2022: Начало</h3>
                <p>Создание прототипа, первые тесты</p>
            </div>
        </div>
        <div class="timeline-item">
            <div class="timeline-icon">
                <img src="https://example.com/2023-icon.png" alt="2023">
            </div>
            <div>
                <h3>2023: Эксперименты</h3>
                <p>Транзакции между физлицами</p>
            </div>
        </div>
        <div class="timeline-item">
            <div class="timeline-icon">
                <img src="https://example.com/2024-icon.png" alt="2024">
            </div>
            <div>
                <h3>2024: Расширение</h3>
                <p>Подключение малого бизнеса</p>
            </div>
        </div>
        <div class="timeline-item">
            <div class="timeline-icon">
                <img src="https://example.com/2025-icon.png" alt="2025">
            </div>
            <div>
                <h3>2025: Массовое использование</h3>
                <p>Интеграция с госуслугами</p>
            </div>
        </div>
    </section>

    <!-- Сравнение -->
    <section class="compare-section">
        <h2 style="color: var(--secondary); text-align: center;">Сравнение систем</h2>
        <div class="compare-container">
            <table class="compare-table">
                <tr>
                    <th>Критерий</th>
                    <th>
                        <img src="https://example.com/digital-ruble-icon.png" 
                             alt="Цифровой рубль" 
                             style="width:40px; vertical-align: middle;">
                        Цифровой рубль
                    </th>
                    <th>
                        <img src="https://example.com/crypto-icon.png" 
                             alt="Криптовалюты" 
                             style="width:40px; vertical-align: middle;">
                        Криптовалюты
                    </th>
                    <th>
                        <img src="https://example.com/paypal-icon.png" 
                             alt="PayPal" 
                             style="width:40px; vertical-align: middle;">
                        PayPal
                    </th>
                </tr>
                <tr>
                    <td>Регулирование</td>
                    <td>Центральный Банк РФ</td>
                    <td>Децентрализовано</td>
                    <td>Международные нормы</td>
                </tr>
                <tr>
                    <td>Комиссии</td>
                    <td>0.1%</td>
                    <td>5-15%</td>
                    <td>3-5% + конвертация</td>
                </tr>
            </table>
        </div>
    </section>

    <!-- Футер -->
    <footer class="footer">
        <img src="https://example.com/cbr-logo-footer.png" 
             alt="Логотип ЦБ РФ" 
             class="footer-logo">
        <p>© 2024-2025 Цифровая экономика. Все права защищены</p>
        <p>
            <a href="https://www.cbr.ru/" target="_blank" style="color: white; text-decoration: underline;">
                Официальный сайт ЦБ РФ
            </a>
        </p>
    </footer>
</body>
</html>
