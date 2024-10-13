<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Клуб Столовки — Вкусная Еда</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h1 {
            color: #2c3e50;
            font-size: 1.8em;
            text-align: center;
            margin-bottom: 20px;
        }
        section {
            background-color: #fff;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            margin-bottom: 40px;
            max-width: 600px;
            margin: 0 auto; /* Центрирование на экране */
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin-bottom: 10px;
            font-size: 1.2em;
        }
        .highlight {
            font-weight: bold;
            color: #e74c3c;
        }
        .strong {
            font-weight: bold;
        }
        /* Медиа-запросы для мобильных устройств */
        @media (max-width: 600px) {
            body {
                padding: 10px;
            }
            h1 {
                font-size: 1.5em;
            }
            section {
                padding: 15px;
            }
            li {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>

    <section>
        <h1>Правила Вкусной Еды</h1>
        <p>Иногда еда может быть признана вкусной, если за это проголосует лидер. Чтобы еда считалась вкусной, менее 80% участников должны проголосовать за то, что еда была обычной или невкусной.</p>

        <p>Эффекты вкусной еды:</p>
        <ul>
            <li><span class="highlight">+5 репутации</span> — за съедение вкусной еды.</li>
            <li><span class="highlight">+15 репутации</span> — за съедение добавки вкусной еды.</li>
            <li><span class="highlight">-20 репутации</span> — за выбрасывание вкусной еды.</li>
        </ul>

        <p>Такой ивент может происходить максимум раз в три дня.</p>
        <p class="strong">! Соки, смузи и прочие плюшки не будут являться едой.</p>
    </section>

</body>
</html>
