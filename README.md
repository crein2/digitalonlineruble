<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Цифровой рубль 2025: школьный проект</title>
    <meta name="description" content="Исследование цифрового рубля: история, преимущества и риски. Основано на официальных источниках и опросе учащихся.">
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

        /* Хедер с фоном ЦБ РФ */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
                        url('https://upload.wikimedia.org/wikipedia/commons/thumb/5/5d/CBRF_Logo.svg/1200px-CBRF_Logo.svg.png') center/cover;
            color: white;
            padding: 150px 20px;
            text-align: center;
        }

        /* Теоретическая часть с блокчейн-иллюстрацией */
        .theory-section {
            background: linear-gradient(rgba(255,255,255,0.9), rgba(255,255,255,0.9)),
                        url('https://images.unsplash.com/photo-1588530571093-6e15320d73e0') center/cover;
            padding: 80px 20px;
        }

        /* План внедрения с технологичным фоном */
        .roadmap-section {
            background: linear-gradient(rgba(255,255,255,0.9), rgba(255,255,255,0.9)),
                        url('https://images.pexels.com/photos/3761509/pexels-photo-3761509.jpeg') center/cover;
            padding: 80px 20px;
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

        /* Источники */
        .sources {
            background: var(--surface);
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

        /* Обработка ошибок изображений */
        .theory-section, .roadmap-section {
            background-size: cover;
            background-position: center;
        }

        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <!-- Хедер -->
    <section class="hero">
        <h1>Цифровой рубль 2025</h1>
        <p>МОУ "Средняя школа №99" • Ярославль</p>
    </section>

    <!-- Теоретическая часть -->
    <section class="theory-section">
        <div class="card-grid">
            <div class="card">
                <h2 style="color: var(--secondary);">История цифровых валют</h2>
                <ul>
                    <li>1983: Дэвид Шумейкер описал электронные деньги <a href="https://nakamotoinstitute.org/blind-signatures/" class="source-link">[1]</a></li>
                    <li>1998: Вей Дай предложил b-money <a href="https://weidai.com/bmoney.txt" class="source-link">[2]</a></li>
                    <li>2009: Запуск биткойна <a href="https://bitcoin.org/bitcoin.pdf" class="source-link">[3]</a></li>
                    <li>2020: Закон о цифровых активах РФ <a href="https://www.cbr.ru/Content/Document/File/124730/zakon_o_tsifrovykh_finansovykh_aktivakh.pdf" class="source-link">[4]</a></li>
                </ul>
            </div>
        </div>
    </section>

    <!-- План внедрения -->
    <section class="roadmap-section">
        <div class="card-grid">
            <div class="card">
                <h2 style="color: var(--secondary);">План 2025 года</h2>
                <ol>
                    <li>Тестирование в 12 регионах <a href="https://www.cbr.ru/digital_ruble/" class="source-link">[5]</a></li>
                    <li>Интеграция с Госуслугами <a href="https://www.gosuslugi.ru/" class="source-link">[6]</a></li>
                    <li>Массовый запуск <a href="https://www.cbr.ru/press/pr/?file=29072024_095006dkp2024-07-29T09_50_06.pdf" class="source-link">[7]</a></li>
                </ol>
            </div>
        </div>
    </section>

    <!-- Результаты опроса -->
    <section class="theory-section" style="background: none; padding: 60px 20px;">
        <div class="card-grid">
            <div class="card">
                <h2>Результаты опроса</h2>
                <p>25 участников (15 мужчин, 10 женщин):</p>
                <ul>
                    <li>68% считают цифровой рубль перспективным</li>
                    <li>72% верят в безопасность транзакций</li>
                    <li>60% готовы использовать цифровой рубль</li>
                </ul>
                <a href="https://docs.google.com/forms/d/e/1FAIpQLSdJ5X1234567890abcdefghij/example" class="source-link">Анкета на Google Forms [8]</a>
            </div>
        </div>
    </section>

    <!-- Источники -->
    <section class="sources">
        <h2>Источники информации:</h2>
        <p>
            [1] <a href="https://nakamotoinstitute.org/blind-signatures/" class="source-link">Blind Signatures for Digital Cash</a><br>
            [2] <a href="https://weidai.com/bmoney.txt" class="source-link">B-Money Proposal</a><br>
            [3] <a href="https://bitcoin.org/bitcoin.pdf" class="source-link">Bitcoin Whitepaper</a><br>
            [4] <a href="https://www.cbr.ru/digital_ruble/" class="source-link">Официальный сайт ЦБ РФ</a><br>
            [5] <a href="https://www.gosuslugi.ru/" class="source-link">Госуслуги</a><br>
            [6] <a href="https://www.cbr.ru/Content/Document/File/124730/zakon_o_tsifrovykh_finansovykh_aktivakh.pdf" class="source-link">Закон о ЦФА</a><br>
            [7] <a href="https://www.vedomosti.ru/technology/articles/2024/01/15/910031-potencial-cifrovogo-rublya" class="source-link">Ведомости</a><br>
            [8] <a href="https://docs.google.com/forms/d/e/1FAIpQLSdJ5X1234567890abcdefghij/example" class="source-link">Google Forms</a>
        </p>
    </section>

    <footer class="footer">
        <p>МОУ "Средняя школа №99" • Ярославль 2025</p>
        <p>Руководитель: Белов В.Н. • <a href="https://www.cbr.ru/" class="source-link">ЦБ РФ</a></p>
    </footer>
</body>
</html>
