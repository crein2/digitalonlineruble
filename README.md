<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Цифровой рубль 2025: школьный проект</title>
    <meta name="description" content="Что такое цифровой рубль? История, планы ЦБ РФ и мнение учеников. Исследование для проекта МОУ СОШ №99 Ярославль">
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

        /* Хедер с логотипом ЦБ */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
                        url('https://avatars.mds.yandex.net/i?id=d8abf913df627bbaaef0c4fd6b44ec46_l-3979407-images-thumbs&n=13') center/cover;
            color: white;
            padding: 150px 20px;
            text-align: center;
        }

        /* Определение с блокчейн-фоном */
        .definition-section {
            background: linear-gradient(rgba(255,255,255,0.9), rgba(255,255,255,0.9)),
                        url('https://avatars.mds.yandex.net/i?id=3fe87a1d30d12a848df0c7f7e0e01817_l-11042380-images-thumbs&n=13') center/cover;
            padding: 80px 20px;
        }

        /* Планы ЦБ с технологичным фоном */
        .roadmap-section {
            background: linear-gradient(rgba(255,255,255,0.9), rgba(255,255,255,0.9)),
                        url('https://avatars.mds.yandex.net/i?id=a89830aadfe8aa74d11e675bfc2b08f8_l-10452644-images-thumbs&n=13') center/cover;
            padding: 80px 20px;
        }

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

        .sources {
            background: #f5f5f5;
            padding: 40px 20px;
            text-align: center;
        }

        .footer {
            background: white;
            color: #2c3e50;
            text-align: center;
            padding: 40px 20px;
            border-top: 1px solid #eee;
        }

        a.source-link {
            color: var(--primary);
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <!-- Хедер -->
    <section class="hero">
        <h1>Цифровой рубль 2025</h1>
        <p>Цифровой рубль: Будущее уже в твоём кошельке!</p>                                          
    </section>

    <!-- Определение -->
    <section class="definition-section">
        <div class="card-grid">
            <div class="card">
                <h2 style="color: var(--secondary);">Что такое цифровой рубль?</h2>
                <p>Цифровая валюта – это деньги, которые существуют только в интернете. Их нельзя потрогать, как настоящие купюры или монеты. Все операции с ними происходят онлайн, с помощью компьютера или телефона.Не путай с криптовалютой,Цифровой рубль — это национальное денежное средство, форма национальной валюты. Выпускать цифровые рубли будет Банк России(ЦБ).</p>
                <a href="https://cbr.ru/faq/dr/" class="source-link">Подробнее в документах ЦБ</a>
            </div>
        </div>
    </section>

    <!-- История -->
    <section class="content-section">
        <h2 style="color: var(--secondary); text-align: center;">История цифровых валют</h2>
        <div class="card-grid">
            <div class="card">
                <h3>1983: Концепция</h3>
                <p>Дэвид Шумейкер описал цифровые деньги <a href="https://nakamotoinstitute.org/blind-signatures/" class="source-link">[1]</a></p>
            </div>
            <div class="card">
                <h3>2009: Bitcoin</h3>
                <p>Первая криптовалюта Сатоши Накамото <a href="https://bitcoin.org/bitcoin.pdf" class="source-link">[2]</a></p>
            </div>
            <div class="card">
                <h3>2020: Закон о ЦФА</h3>
                <p>Россия начала регулирование <a href="https://www.cbr.ru/Content/Document/File/124730/zakon_o_tsifrovykh_finansovykh_aktivakh.pdf" class="source-link">[3]</a></p>
            </div>
            <div class="card">
                <h3>2023: Пилот</h3>
                <p>Тестирование в 12 регионах <a href="https://www.cbr.ru/press/pr/?file=29072024_095006dkp2024-07-29T09_50_06.pdf" class="source-link">[4]</a></p>
            </div>
        </div>
    </section>

    <!-- Актуальность -->
    <section class="roadmap-section">
        <div class="card-grid">
            <div class="card">
                <h2 style="color: var(--secondary);">Почему это важно?</h2>
                <ul>
                    <li>Снижение зависимости от доллара</li>
                    <li>Борьба с теневой экономикой</li>
                    <li>Удобство для молодежи</li>
                    <li>Поддержка инноваций</li>
                </ul>
                <a href="https://forklog.com/cifrovoj-rubl-eto-vazhno/" class="source-link">[Мнение экспертов]</a>
            </div>
        </div>
    </section>

    <!-- Планы ЦБ -->
    <section class="content-section">
        <h2 style="color: var(--secondary); text-align: center;">Планы Центробанка</h2>
        <div class="card-grid">
            <div class="card">
                <h3>2024-2025</h3>
                <ol>
                    <li>Интеграция с Госуслугами</li>
                    <li>Поддержка 20+ банков</li>
                    <li>Офлайн-режим до 72 часов</li>
                </ol>
                <a href="https://www.cbr.ru/digital_ruble/" class="source-link">[Дорожная карта ЦБ]</a>
            </div>
        </div>
    </section>

    <!-- Результаты опроса -->
    <section class="content-section">
        <h2 style="color: var(--secondary); text-align: center;">Мнение учеников</h2>
        <div class="card-grid">
            <div class="card">
                <h3>Опрос 25 человек</h3>
                <p>Основные результаты:</p>
                <ul>
                    <li>60% мужчин, 40% женщин</li>
                    <li>68% верят в успех</li>
                    <li>72% считают безопасным</li>
                </ul>
                <a href="https://docs.google.com/forms/d/e/1FAIpQLSdJ5X1234567890abcdefghij/example" class="source-link">[Наша анкета]</a>
            </div>
        </div>
    </section>
  <!-- Источники в одну строку -->
    <section class="sources">
        <h2>Источники:</h2>
        <div class="card">
            <p style="text-align: left;">
                <a href="https://www.cbr.ru/digital_ruble/" class="source-link">ЦБ РФ</a> ,
                <a href="https://forklog.com" class="source-link">ForkLog</a> , 
                <a href="https://nakamotoinstitute.org/blind-signatures/" class="source-link">Blind Signatures</a> , 
                <a href="https://bitcoin.org/bitcoin.pdf" class="source-link">Bitcoin Whitepaper</a> ,
                <a href="https://docs.google.com/forms/d/e/1FAIpQLSdJ5X1234567890abcdefghij/example" class="source-link">Опрос</a> .
            </p>
        </div>
    </section>

    <footer class="footer">
        <p>МОУ "Средняя школа №99" • Ярославль 2025</p>
    </footer>
</body>
</html>
