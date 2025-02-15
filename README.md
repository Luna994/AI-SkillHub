 <!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI SkillHub | AI-ассистенты и обучение</title>
    <style>
        /* Подключаем шрифты */
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');

        /* Общие стили */
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #0F052D, #240A64);
            color: #FFFFFF;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        /* Шапка */
        header {
            padding: 50px 20px;
            text-align: center;
        }

        .logo {
            width: 150px;
            height: auto;
            margin-bottom: 20px;
            animation: logoBounce 2s infinite alternate;
        }

        @keyframes logoBounce {
            from { transform: translateY(0px); }
            to { transform: translateY(5px); }
        }

        h1 {
            font-size: 2.8em;
            font-weight: 700;
            color: #FFFFFF;
            text-shadow: 0px 0px 15px #9A6BFF;
        }

        p {
            font-size: 1.2em;
            color: #CCCCCC;
            line-height: 1.5;
            max-width: 700px;
            margin: auto;
        }

        /* Кнопка */
        .cta-button {
            display: inline-block;
            background: #9A6BFF;
            color: #FFFFFF;
            font-size: 1.2em;
            font-weight: bold;
            padding: 14px 28px;
            border-radius: 30px;
            text-decoration: none;
            transition: 0.3s;
            margin-top: 20px;
        }

        .cta-button:hover {
            background: #A77BFF;
            box-shadow: 0px 0px 15px #A77BFF;
            transform: scale(1.05);
        }

        /* Разделы */
        .section {
            padding: 60px 20px;
        }

        .dark-section {
            background: #1A093C;
            padding: 80px 20px;
            border-radius: 20px;
        }

        .features {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
            max-width: 1000px;
            margin: auto;
        }

        .feature {
            background: #2C1068;
            padding: 20px;
            border-radius: 12px;
            width: 280px;
            font-weight: bold;
            box-shadow: 0px 4px 10px rgba(255, 255, 255, 0.1);
            transition: transform 0.3s;
        }

        .feature:hover {
            transform: translateY(-5px);
            box-shadow: 0px 0px 15px #9A6BFF;
        }

        /* Подвал */
        .footer {
            background: #6A0DAD;
            padding: 20px;
            color: white;
            font-size: 0.9em;
        }

    </style>
</head>
<body>

<header>
    <img src="logo_resized.png" alt="AI SkillHub Logo" class="logo">
    <h1>AI SkillHub</h1>
    <p>Разработка AI-ассистентов, автоматизация процессов и обучение нейросетям.</p>
    <a href="https://t.me/yourbot" class="cta-button">Записаться на мастер-класс</a>
</header>

<section class="section">
    <h2>Наши услуги</h2>
    <div class="features">
        <div class="feature">📌 Разработка AI-ассистентов</div>
        <div class="feature">🤖 Чат-боты для бизнеса</div>
        <div class="feature">🚀 Обучение и мастер-классы</div>
    </div>
</section>

<section class="section dark-section">
    <h2>Почему выбирают нас?</h2>
    <div class="features">
        <div class="feature">✔️ 100+ успешных AI-проектов</div>
        <div class="feature">✔️ Эксперты с опытом 5+ лет</div>
        <div class="feature">✔️ Поддержка и консультации</div>
    </div>
</section>

<section class="section">
    <h2>Отзывы наших клиентов</h2>
    <div class="features">
        <div class="feature">💬 «AI-ассистент сэкономил нам 40% времени!»</div>
        <div class="feature">💬 «Боты теперь делают всю рутину за нас!»</div>
        <div class="feature">💬 «Лучшее обучение по AI, всё понятно!»</div>
    </div>
</section>

<section class="section dark-section">
    <h2>Хотите внедрить AI?</h2>
    <p>Оставьте заявку, и мы свяжемся с вами в ближайшее время!</p>
    <a href="https://t.me/yourbot" class="cta-button">Оставить заявку</a>
</section>

<footer class="footer">
    <p>© 2025 AI SkillHub | Telegram: https//t.me/proverka555777_bot</p>
</footer>

</body>
</html>
