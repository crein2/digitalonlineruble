<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Цифровой рубль: технологии, интеграция, перспективы до 2025</title>
    <meta name="description" content="Полное руководство по цифровому рублю: как работает блокчейн ЦБ РФ, преимущества для граждан и бизнеса, этапы внедрения до 2025 года, сравнение с криптовалютами и PayPal.">
    <meta name="keywords" content="цифровой рубль, ЦБ РФ, блокчейн, смарт-контракты, цифровая валюта, финтех, 2025, IoT, криптовалюта">
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

        .hero {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 60px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .cta-buttons {
            margin-top: 30px;
        }

        .cta-button {
            display: inline-block;
            padding: 12px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            transition: 0.3s;
            margin: 10px;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            padding: 40px 20px;
        }

        .feature-card {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.15);
        }

        .timeline {
            background: white;
            border-radius: 15px;
            padding: 40px 20px;
            margin: 40px 0;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        .timeline-item {
            position: relative;
            padding-left: 40px;
            margin-bottom: 30px;
        }

        .timeline-icon {
            position: absolute;
            left: 0;
            top: 0;
            background: var(--primary);
            width: 30px;
            height: 30px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
        }

        .compare-section {
            padding: 40px 20px;
        }

        .compare-container {
            max-width: 1000px;
            margin: 0 auto;
            overflow-x: auto;
        }

        .compare-table {
            width: 100%;
            border-collapse: collapse;
            min-width: 600px;
        }

        .compare-table th, .compare-table td {
            padding: 15px;
            text-align: left;
            border-bottom: 1px solid #eee;
        }

        .compare-table th {
            background: var(--primary);
            color: white;
        }

        .footer {
            background: var(--primary);
            color: white;
            text-align: center;
            padding: 30px;
            border-radius: 15px;
            margin-top: 40px;
        }

        .footer a {
            color: white;
            text-decoration: underline;
            margin: 0 10px;
            transition: 0.3s;
        }

        .footer a:hover {
            color: #e6e6e6;
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2em;
            }
        }
    </style>
</head>
<body>
    <section class="hero">
        <h1>Цифровой рубль: будущее уже здесь</h1>
        <p>Узнайте, как цифровая валюта ЦБ РФ изменит финансовый мир к 2025 году</p>
        <div class="cta-buttons">
            <a href="#how" class="cta-button" style="background: var(--primary); color: white;">Как это работает?</a>
            <a href="https://www.cbr.ru/" target="_blank" class="cta-button" style="background: var(--accent); color: white;">Сайт ЦБ РФ</a>
        </div>
    </section>

    <section id="how">
        <div class="features-grid">
            <div class="feature-card">
                <h3>Блокчейн-инфраструктура</h3>
                <ul>
                    <li>Гибридный блокчейн с поддержкой смарт-контрактов</li>
                    <li>Криптография уровня банковских систем</li>
                    <li>Резервные узлы в 15 регионах РФ</li>
                </ul>
                <p>Технология обеспечивает:</p>
                <ul>
                    <li>Мгновенную синхронизацию платежей</li>
                    <li>Защиту от двойного расходования средств</li>
                    <li>Полную прозрачность для регуляторов</li>
                </ul>
            </div>
            <div class="feature-card">
                <h3>Цифровые кошельки</h3>
                <ul>
                    <li>Мобильное приложение ЦБ РФ</li>
                    <li>Банковские приложения-партнеры</li>
                    <li>Смарт-карты с NFC</li>
                </ul>
                <p>Функции кошелька:</p>
                <ul>
                    <li>Автономная работа до 72 часов</li>
                    <li>Биометрическая аутентификация</li>
                    <li>Интеграция с Госуслугами</li>
                </ul>
            </div>
            <div class="feature-card">
                <h3>Юридическая база</h3>
                <ul>
                    <li>ФЗ № 259-ФЗ от 24.07.2023</li>
                    <li>Постановление Правительства № 1581</li>
                    <li>Положение ЦБ РФ № 642-П</li>
                </ul>
                <p>Гарантии:</p>
                <ul>
                    <li>Страхование вкладов до 10 млн ₽</li>
                    <li>Судебная защита операций</li>
                    <li>Контроль Росфинмониторинга</li>
                </ul>
            </div>
        </div>
    </section>

    <section class="timeline">
        <h2 style="text-align: center; color: var(--secondary);">Дорожная карта до 2025 года</h2>
        <div class="timeline-item">
            <div class="timeline-icon">1</div>
            <div class="timeline-content">
                <h3>2022 - Исследовательская фаза</h3>
                <p>Создание прототипа платформы, тестирование на закрытых полигонах</p>
            </div>
        </div>
        <div class="timeline-item">
            <div class="timeline-icon">2</div>
            <div class="timeline-content">
                <h3>2023 - Пилотный запуск</h3>
                <p>Первые транзакции между физическими лицами, интеграция с 12 банками</p>
            </div>
        </div>
        <div class="timeline-item">
            <div class="timeline-icon">3</div>
            <div class="timeline-content">
                <h3>2024 - Массовое тестирование</h3>
                <p>Подключение 500+ предприятий, офлайн-платежи, пилот международных расчетов</p>
            </div>
        </div>
        <div class="timeline-item">
            <div class="timeline-icon">4</div>
            <div class="timeline-content">
                <h3>2025 - Полное внедрение</h3>
                <p>Запуск смарт-контрактов, интеграция с IoT-устройствами, кросс-валютные операции</p>
            </div>
        </div>
    </section>

    <section class="compare-section">
        <h2 style="text-align: center; color: var(--secondary);">Сравнение платежных систем</h2>
        <div class="compare-container">
            <table class="compare-table">
                <tr>
                    <th>Критерий</th>
                    <th>Цифровой рубль</th>
                    <th>Криптовалюты</th>
                    <th>PayPal</th>
                </tr>
                <tr>
                    <td>Регулирование</td>
                    <td>Центральный Банк РФ</td>
                    <td>Децентрализовано</td>
                    <td>Международные регуляторы</td>
                </tr>
                <tr>
                    <td>Комиссии</td>
                    <td>0.1% (максимум)</td>
                    <td>5-15% (в зависимости от сети)</td>
                    <td>3-5% + конвертация</td>
                </tr>
                <tr>
                    <td>Скорость</td>
                    <td>3 секунды (мгновенно)</td>
                    <td>10-60 минут (зависит от блокчейна)</td>
                    <td>Мгновенно (с задержкой зачисления)</td>
                </tr>
                <tr>
                    <td>Анонимность</td>
                    <td>Частичная (для малых сумм)</td>
                    <td>Полная (для большинства криптовалют)</td>
                    <td>Нет (полная идентификация)</td>
                </tr>
                <tr>
                    <td>Гарантии</td>
                    <td>Государственные (ФЗ № 259)</td>
                    <td>Отсутствуют</td>
                    <td>Корпоративные (PayPal Inc.)</td>
                </tr>
                <tr>
                    <td>Поддержка</td>
                    <td>24/7 через ЦБ РФ</td>
                    <td>Сообщества и форумы</td>
                    <td>Чат-боты и колл-центр</td>
                </tr>
            </table>
        </div>
    </section>

    <section class="features-grid" style="padding: 40px 20px;">
        <div class="feature-card">
            <h3>Для граждан</h3>
            <ul>
                <li>Переводы до 100 000 ₽ без комиссии</li>
                <li>Оплата ЖКХ через Госуслуги</li>
                <li>Контроль расходов в реальном времени</li>
            </ul>
        </div>
        <div class="feature-card">
            <h3>Для бизнеса</h3>
            <ul>
                <li>Автоматизация расчетов с поставщиками</li>
                <li>Снижение налоговой нагрузки на 15%</li>
                <li>Интеграция с 1С и ERP-системами</li>
            </ul>
        </div>
        <div class="feature-card">
            <h3>Для государства</h3>
            <ul>
                <li>Снижение наличного оборота на 40%</li>
                <li>Контроль за теневыми операциями</li>
                <li>Упрощение налогового администрирования</li>
            </ul>
        </div>
    </section>

    <footer class="footer">
        <p>© 2024-2025 Цифровая экономика. Все права защищены</p>
        <p>
            Официальный источник: 
            <a href="https://www.cbr.ru/" target="_blank" title="Центральный Банк Российской Федерации">
                ЦБ РФ
            </a>
        </p>
    </footer>
</body>
</html>
