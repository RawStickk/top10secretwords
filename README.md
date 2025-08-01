<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ТОП-10 СУПЕРСЕКРЕТНЫХ СЛОВ</title>
    <style>
        body {
            font-family: 'Courier New', monospace;
            background: #000;
            color: #0f0;
            text-align: center;
            padding: 20px;
        }
        h1 {
            text-shadow: 0 0 5px #0f0;
        }
        .word {
            border: 1px dashed #0f0;
            margin: 10px;
            padding: 10px;
            cursor: pointer;
        }
        .word:hover {
            background: #111;
        }
        .secret {
            display: none;
            color: #ff0;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <h1>🔐 ТОП-10 СУПЕРСЕКРЕТНЫХ СЛОВ</h1>

    <div class="word" onclick="toggleSecret(1)">1. Ветер 🌬️</div>

    <div class="word" onclick="toggleSecret(2)">2. ДИКИЙ ОГУРЕЦ 🥒🌿</div>

    <div class="word" onclick="toggleSecret(3)">3. Трава 🌱</div>

    <div class="word" onclick="toggleSecret(4)">4. Жираф 🦒</div>

    <div class="word" onclick="toggleSecret(5)">5. Одуванчик 🌼</div>

    <div class="word" onclick="toggleSecret(6)">6. ПЫЛЕСОС 🔊	</div>

    <div class="word" onclick="toggleSecret(7)">7. ДИКИЙ ОГУРЕЦ 🥒🌿</div>

    <div class="word" onclick="toggleSecret(8)">8. Грейпфрут 🍊</div>

    <div class="word" onclick="toggleSecret(9)">9. Радуга 🌈</div>

    <div class="word" onclick="toggleSecret(10)">10. ДИКИЙ ОГУРЕЦ 🥒🌿</div>

    <script>
        function toggleSecret(num) {
            const secret = document.getElementById(`secret${num}`);
            secret.style.display = secret.style.display === 'block' ? 'none' : 'block';
        }
    </script>
</body>
</html>
