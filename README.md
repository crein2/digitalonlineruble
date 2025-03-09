<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Цифровой рубль 2025: технологии и интеграция</title>
    <meta name="description" content="Цифровой рубль в 2025 году: безопасность, инновации, государственные гарантии. Подробная информация о внедрении.">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
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

        /* Хедер с ПЕРВЫМ изображением */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)),
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
            text-align: center;
        }

        .history-icon img {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            border: 3px solid var(--primary);
        }

        /* Технологии */
        .tech-section {
            padding: 60px 20px;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
        }

        .tech-card {
            background: white;
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .tech-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 30px rgba(0,0,0,0.15);
        }

        /* Дорожная карта с ТРЕТЬИМ изображением */
        .timeline {
            background: var(--surface);
            border-radius: 20px;
            padding: 60px 20px;
            margin: 60px 0;
        }

        .timeline-item {
            display: flex;
            align-items: center;
            gap: 40px;
            margin-bottom: 50px;
        }

        .timeline-icon {
            flex: 0 0 120px;
            text-align: center;
        }

        .timeline-icon img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 5px solid var(--primary);
        }

        /* Футер с ЧЕТВЕРТЫМ изображением */
        .footer {
            background: var(--primary);
            color: white;
            text-align: center;
            padding: 40px 20px;
            position: relative;
        }

        .footer-logo {
            width: 100%;
            max-width: 1200px;
            height: auto;
            margin: 0 auto 25px;
            display: block;
        }

        @media (max-width: 768px) {
            .history-card {
                flex-direction: column;
                text-align: center;
            }
            
            .timeline-item {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <!-- Хедер с ПЕРВЫМ изображением -->
    <section class="hero">
        <h1>Цифровой рубль 2025</h1>
        <p>Безопасность, инновации, государственные гарантии</p>
        <div class="cta-buttons">
            <a href="#history" class="cta-button">История</a>
            <a href="#tech" class="cta-button">Технологии</a>
            <a href="https://www.cbr.ru/" target="_blank" class="cta-button" style="background: var(--accent);">ЦБ РФ</a>
        </div>
    </section>

    <!-- История с ВТОРЫМ изображением -->
    <section id="history" class="history-section">
        <h2 style="color: var(--secondary); text-align: center;">Эволюция проекта</h2>
        <div class="history-card">
            <div class="history-icon">
                <img src="https://avatars.mds.yandex.net/i?id=3fe87a1d30d12a848df0c7f7e0e01817_l-11042380-images-thumbs&n=13" alt="Глобальный тренд">
            </div>
            <div>
                <h3>Международный опыт</h3>
                <p>Анализ CBDC 93 стран мира для создания оптимальной системы.</p>
            </div>
        </div>
        <div class="history-card">
            <div class="history-icon">
                <img src="https://avatars.mds.yandex.net/i?id=3fe87a1d30d12a848df0c7f7e0e01817_l-11042380-images-thumbs&n=13" alt="Разработка">
            </div>
            <div>
                <h3>Российская разработка</h3>
                <p>Прототип 2022 года прошел 3 этапа тестирования с 50+ банками.</p>
            </div>
        </div>
        <div class="history-card">
            <div class="history-icon">
                <img src="https://avatars.mds.yandex.net/i?id=3fe87a1d30d12a848df0c7f7e0e01817_l-11042380-images-thumbs&n=13" alt="Законодательство">
            </div>
            <div>
                <h3>Правовая база</h3>
                <p>ФЗ №259-ФЗ от 24.07.2023 легализовал цифровой рубль.</p>
            </div>
        </div>
    </section>

    <!-- Технологии -->
    <section id="tech" class="tech-section">
        <h2 style="color: var(--secondary); text-align: center;">Технологии будущего</h2>
        <div class="tech-grid">
            <div class="tech-card">
                <h3>Блокчейн 3.0</h3>
                <p>Гибридная сеть с:</p>
                <ul>
                    <li>Квантовой защитой</li>
                    <li>Самовосстановлением узлов</li>
                    <li>Энергоэффективностью</li>
                </ul>
            </div>
            <div class="tech-card">
                <h3>IoT-интеграция</h3>
                <p>Автоматические платежи через:</p>
                <ul>
                    <li>Умные счетчики ЖКХ</li>
                    <li>Автомобильные сенсоры</li>
                    <li>Городские системы</li>
                </ul>
            </div>
            <div class="tech-card">
                <h3>Международные расчеты</h3>
                <p>Поддержка:</p>
                <ul>
                    <li>15 валют через SWIFT</li>
                    <li>Кросс-граничные переводы</li>
                    <li>Торговля цифровыми активами</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Дорожная карта с ТРЕТЬИМ изображением -->
    <section class="timeline">
        <h2 style="color: var(--secondary); text-align: center;">План 2025 года</h2>
        <div class="timeline-item">
            <div class="timeline-icon">
                <img src="https://avatars.mds.yandex.net/i?id=a89830aadfe8aa74d11e675bfc2b08f8_l-10452644-images-thumbs&n=13" alt="2025">
            </div>
            <div>
                <h3>Ключевые цели</h3>
                <ul>
                    <li>50 млн пользователей</li>
                    <li>Интеграция с госуслугами</li>
                    <li>Офлайн-платежи до 72 часов</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Футер с ЧЕТВЕРТЫМ изображением -->
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
