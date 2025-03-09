<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Цифровой рубль 2025: технологии будущего</title>
    <meta name="description" content="Цифровой рубль в 2025 году: безопасные платежи, инновации, государственные гарантии. Официальная информация ЦБ РФ.">
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

        /* Хедер с одним фоновым изображением */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)),
                        url('https://avatars.mds.yandex.net/i?id=2585af27b413c5cc46352da6b565ed8b_l-5086925-images-thumbs&n=13') center/cover;
            color: white;
            padding: 150px 20px;
            text-align: center;
            position: relative;
            animation: pulse 2s infinite;
        }

        /* Удаляем отдельный логотип */
        .hero-logo {
            display: none;
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

        .cta-button:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.3);
        }

        /* Историческая секция */
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
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
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

        /* Дорожная карта */
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
            animation: float 3s ease-in-out infinite;
        }

        /* Сравнительная таблица */
        .compare-table {
            width: 100%;
            border-collapse: collapse;
            min-width: 800px;
            margin: 40px 0;
        }

        .compare-table th {
            background: var(--primary);
            color: white;
            padding: 20px;
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
            padding: 50px 20px;
        }

        .footer-logo {
            width: 240px;
            margin-bottom: 25px;
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
    <!-- Хедер с ОДНИМ изображением -->
    <section class="hero">
        <h1>Цифровой рубль 2025</h1>
        <p>Безопасные платежи, инновации, государственные гарантии</p>
        <div class="cta-buttons">
            <a href="#roadmap" class="cta-button">План 2025</a>
            <a href="https://www.cbr.ru/" target="_blank" class="cta-button" style="background: var(--accent);">ЦБ РФ</a>
        </div>
    </section>

    <!-- Остальные секции остаются без изменений -->
    <!-- История создания -->
    <section id="history" class="history-section">
        <h2 style="color: var(--secondary); text-align: center;">Эволюция цифрового рубля</h2>
        <div class="history-card">
            <div class="history-icon">
                <img src="https://avatars.mds.yandex.net/i?id=2585af27b413c5cc46352da6b565ed8b_l-5086925-images-thumbs&n=13" alt="Глобальный тренд">
            </div>
            <div>
                <h3>Всемирный опыт</h3>
                <p>К 2025 году 93% стран имеют национальные CBDC. Россия адаптирует лучшие практики с учетом локальных особенностей.</p>
            </div>
        </div>
        <!-- ... (остальные history-card) ... -->
    </section>

    <!-- Технологии -->
    <section class="tech-section">
        <h2 style="color: var(--secondary); text-align: center;">Технологии будущего</h2>
        <div class="tech-grid">
            <!-- ... (tech-card остаются без изменений) ... -->
        </div>
    </section>

    <!-- Дорожная карта -->
    <section class="timeline">
        <h2 style="color: var(--secondary); text-align: center;">План 2025 года</h2>
        <div class="timeline-item">
            <div class="timeline-icon">
                <img src="https://avatars.mds.yandex.net/i?id=2585af27b413c5cc46352da6b565ed8b_l-5086925-images-thumbs&n=13" alt="2025">
            </div>
            <div>
                <h3>Стратегические цели</h3>
                <ul>
                    <li>50 млн пользователей</li>
                    <li>Интеграция с 200+ госуслугами</li>
                    <li>Офлайн-режим до 72 часов</li>
                    <li>Комиссии от 0.03%</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Футер -->
    <footer class="footer">
        <img src="https://avatars.mds.yandex.net/i?id=2585af27b413c5cc46352da6b565ed8b_l-5086925-images-thumbs&n=13" 
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
