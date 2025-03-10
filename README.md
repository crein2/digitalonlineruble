<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Цифровой рубль 2025: перспективы и исследования</title>
    <meta name="description" content="Исследовательский проект о цифровом рубле: история развития, актуальность, план внедрения и результаты опроса.">
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
            color: #2c3e50;
            line-height: 1.7;
            background: var(--background);
        }

        /* Хедер с первым изображением */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
                        url('https://avatars.mds.yandex.net/i?id=d8abf913df627bbaaef0c4fd6b44ec46_l-3979407-images-thumbs&n=13') center/cover;
            color: white;
            padding: 150px 20px;
            text-align: center;
        }

        /* Секция с теоретической частью */
        .theory-section {
            background: var(--surface);
            border-radius: 20px;
            padding: 60px 20px;
            margin: 40px 0;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        /* Секция с исследованиями */
        .research-section {
            background: linear-gradient(rgba(255,255,255,0.9), rgba(255,255,255,0.9)),
                        url('https://avatars.mds.yandex.net/i?id=3fe87a1d30d12a848df0c7f7e0e01817_l-11042380-images-thumbs&n=13') center/cover;
            border-radius: 20px;
            padding: 60px 20px;
            margin: 40px 0;
        }

        /* Секция с планом */
        .roadmap-section {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
                        url('https://avatars.mds.yandex.net/i?id=a89830aadfe8aa74d11e675bfc2b08f8_l-10452644-images-thumbs&n=13') center/cover;
            color: white;
            padding: 60px 20px;
            border-radius: 20px;
            margin: 40px 0;
        }

        /* Карточки */
        .card-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .card {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.2);
        }

        /* Стили для минусов */
        .negative {
            color: #ff5252;
            margin-top: 15px;
        }

        /* Футер */
        .footer {
            background: white;
            color: #2c3e50;
            text-align: center;
            padding: 40px 20px;
            border-top: 1px solid #eee;
        }
    </style>
</head>
<body>
    <!-- Хедер -->
    <section class="hero">
        <h1>Цифровой рубль 2025</h1>
        <p>Исследовательский проект учащегося 10А класса</p>
    </section>

    <!-- Теоретическая часть -->
    <section class="theory-section">
        <h2 style="color: var(--secondary); text-align: center;">История цифровых валют</h2>
        <div class="card-grid">
            <div class="card">
                <h3>1983: Электронные деньги</h3>
                <p>Дэвид Шумейкер предложил концепцию</p>
            </div>
            <div class="card">
                <h3>1998: b-money</h3>
                <p>Вей Дай разработал идею децентрализации</p>
            </div>
            <div class="card">
                <h3>2008: Биткоин</h3>
                <p>Сатоши Накамото создал первую криптовалюту</p>
            </div>
            <div class="card">
                <h3>2011-2017: Альткойны</h3>
                <p>Появление Litecoin, Ethereum, Ripple</p>
            </div>
            <div class="card">
                <h3>2020: Закон о ЦФА</h3>
                <p>Россия начала регулирование криптовалют</p>
            </div>
            <div class="card">
                <h3>2025: Цифровой рубль</h3>
                <p>Планируемый массовый запуск</p>
            </div>
        </div>
    </section>

    <!-- Практическая часть -->
    <section class="research-section">
        <h2 style="color: var(--secondary); text-align: center;">Результаты опроса</h2>
        <div class="card-grid">
            <div class="card">
                <h3>Участники</h3>
                <p>25 человек: 15 мужчин (60%), 10 женщин (40%)</p>
            </div>
            <div class="card">
                <h3>Актуальность</h3>
                <p>68% считают цифровой рубль важным для экономики</p>
            </div>
            <div class="card">
                <h3>Безопасность</h3>
                <p>72% верят в повышение безопасности платежей</p>
            </div>
        </div>
    </section>

    <!-- План внедрения -->
    <section class="roadmap-section">
        <h2 style="color: var(--accent); text-align: center;">План внедрения 2025</h2>
        <div class="card-grid">
            <div class="card" style="background: rgba(0,0,0,0.7); color: white;">
                <h3>Этап 1</h3>
                <p>Тестирование в 12 регионах</p>
            </div>
            <div class="card" style="background: rgba(0,0,0,0.7); color: white;">
                <h3>Этап 2</h3>
                <p>Интеграция с Госуслугами</p>
            </div>
            <div class="card" style="background: rgba(0,0,0,0.7); color: white;">
                <h3>Этап 3</h3>
                <p>Массовый запуск для граждан</p>
            </div>
        </div>
    </section>

    <!-- Плюсы и минусы -->
    <section class="theory-section">
        <h2 style="color: var(--secondary); text-align: center;">Влияние на общество</h2>
        <div class="card-grid">
            <div class="card">
                <h3>Граждане</h3>
                <p><strong>Плюсы:</strong></p>
                <ul>
                    <li>Мгновенные платежи</li>
                    <li>Контроль расходов</li>
                    <li>Снижение комиссий</li>
                </ul>
                <p class="negative"><strong>Минусы:</strong></p>
                <ul>
                    <li>Цифровая зависимость</li>
                    <li>Риски утечек данных</li>
                </ul>
            </div>
            <div class="card">
                <h3>Бизнес</h3>
                <p><strong>Плюсы:</strong></p>
                <ul>
                    <li>Автоматизация расчетов</li>
                    <li>Новые возможности</li>
                </ul>
                <p class="negative"><strong>Минусы:</strong></p>
                <ul>
                    <li>Кибератаки</li>
                    <li>Необходимость адаптации</li>
                </ul>
            </div>
            <div class="card">
                <h3>Государство</h3>
                <p><strong>Плюсы:</strong></p>
                <ul>
                    <li>Контроль экономики</li>
                    <li>Снижение коррупции</li>
                </ul>
                <p class="negative"><strong>Минусы:</strong></p>
                <ul>
                    <li>Затраты на разработку</li>
                    <li>Кибербезопасность</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Футер -->
    <footer class="footer">
        <p>МОУ "Средняя школа №99" • Ярославль 2025</p>
        <p>Руководитель: Белов В.Н. • Учитель обществознания</p>
        <p>
            <a href="https://www.cbr.ru/" target="_blank" style="color: var(--primary); text-decoration: underline;">
                Официальный сайт ЦБ РФ
            </a>
        </p>
    </footer>
</body>
</html>
