<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ЛОР дәрігерінің Қабылдауынан Кейінгі Анкета</title>
    <style>
        body {
            background-image: url(WhatsApp\ Image\ 2024-12-16\ at\ 01.38.00.jpeg);
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            width: 100%;
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            text-align: center;
        }
        h1, h2 {
            text-align: center;
            color: #007BFF;
        }
        label {
            font-weight: bold;
            display: block;
            margin-top: 15px;
        }
        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin: 8px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type="checkbox"], input[type="radio"] {
            width: auto;
            margin-right: 10px;
        }
        button {
            background-color: #007BFF;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            display: block;
            margin: 20px auto;
            font-size: 16px;
        }
        button:hover {
            background-color: #0056b3;
        }
        .section {
            margin-bottom: 20px;
        }
        .img {
            background-image: url(WhatsApp\ Image\ 2024-12-16\ at\ 01.38.00.jpeg);
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <meta name="google-site-verification" content="Ta1hS4t0tqcBBQunw0KpbPyQoh9651UgIZJgMx2687o" />
    <div class="container">
        <h1>DR.Konisbaev ЛОР дәрігерінің қабылдауынан өткен пациенттерге арналған анкета</h1>
        <p>Құрметті пациент! Сіздің пікіріңіз біз үшін өте маңызды. Анкетаны толтыру арқылы біздің қызметімізді жақсартуға көмектесіңіз.</p>
        <form action="#" method="post">
            <!-- Қабылдау мәліметтері -->
            <div class="section">
                <label for="date">Қабылдау күні:</label>
                <input type="date" id="date" name="date" required>

                <label for="name">Пациенттің аты-жөні:</label>
                <input type="text" id="name" name="name" placeholder="Аты-жөніңізді жазыңыз" required>

                <label for="age">Жасыңыз:</label>
                <input type="number" id="age" name="age" min="0" max="120" placeholder="Жасыңыз">
                
                <label for="city">Қалаңыз:</label>
                <select name="city" id="city" required>
                    <option value="">Қалаңызды таңдаңыз</option>
                    <option value="Алматы">Алматы</option>
                    <option value="Шымкент">Шымкент</option>
                    <option value="Ақтау">Ақтау</option>
                    <option value="Қызылорда">Қызылорда</option>
                </select>
            </div>

            <div class="img"></div>

            <!-- Қабылдауға келген себебіңіз -->
            <div class="section">
                <label>Қабылдауға келген себебіңіз:</label>
                <label><input type="checkbox" name="reason" value="Тамақ ауруы"> Тамақ ауруы</label>
                <label><input type="checkbox" name="reason" value="Мұрынмен тыныс алу қиындықтары"> Мұрынмен тыныс алу қиындықтары</label>
                <label><input type="checkbox" name="reason" value="Құлақ аурулары"> Құлақ аурулары</label>
                <label><input type="checkbox" name="reason" value="Ұйқыдағы храп"> Ұйқыдағы храп</label>
                <label><input type="checkbox" name="reason" value="Бас ауруы"> Бас ауруы</label>
                <label><input type="checkbox" name="reason" value="Қалтырау"> Қалтырау</label>
                <label><input type="checkbox" name="reason" value="Құлақтағы залалдану немесе қысым"> Құлақтағы залалдану немесе қысым сезімі</label>
                <label><input type="checkbox" name="reason" value="Басқа"> Басқа:</label>
                <input type="text" name="other_reason" placeholder="Көрсетіңіз">
            </div>

            <!-- Дәрігердің қызметін бағалау -->
            <div class="section">
                <label>1. Дәрігердің түсіндірмелерінің айқындығы мен қолжетімділігі:</label>
                <select name="explanation">
                    <option>Өте жақсы</option>
                    <option>Жақсы</option>
                    <option>Қанағаттанарлық</option>
                    <option>Қанағаттанбадым</option>
                </select>

                <label>2. Дәрігердің сіздің шағымдарыңызға назар аударуы:</label>
                <select name="attention">
                    <option>Өте жақсы</option>
                    <option>Жақсы</option>
                    <option>Қанағаттанарлық</option>
                    <option>Қанағаттанбадым</option>
                </select>

                <label>3. Диагностиканың сапасы:</label>
                <select name="diagnosis_quality">
                    <option>Өте жақсы</option>
                    <option>Жақсы</option>
                    <option>Қанағаттанарлық</option>
                    <option>Нашар</option>
                </select>

                <label>4. Емдеу немесе ұсынылған кеңестердің сапасы:</label>
                <select name="treatment_quality">
                    <option>Өте жақсы</option>
                    <option>Жақсы</option>
                    <option>Қанағаттанарлық</option>
                    <option>Нашар</option>
                </select>
            </div>

            <!-- Қосымша сұрақтар -->
            <div class="section">
                <label>Қосымша зерттеулер жүргізілді ме?</label>
                <label><input type="radio" name="additional_tests" value="Иә"> Иә</label>
                <label><input type="radio" name="additional_tests" value="Жоқ"> Жоқ</label>
                <label>Егер иә болса, қандай зерттеулер жүргізілді?</label>
                <input type="text" name="tests_details">

                <label>Сізге диагнозыңыз және ұсынылған емдеу туралы жеткілікті ақпарат берілді ме?</label>
                <label><input type="radio" name="information" value="Иә"> Иә</label>
                <label><input type="radio" name="information" value="Жоқ"> Жоқ</label>
                <label><input type="radio" name="information" value="Ішінара"> Ішінара</label>

                <label>Консультациядан және емдеуден кейін жақсару сезінесіз бе?</label>
                <label><input type="radio" name="improvement" value="Иә"> Иә</label>
                <label><input type="radio" name="improvement" value="Жоқ"> Жоқ</label>
                <label><input type="radio" name="improvement" value="Жақсару жоқ, бірақ үміттемін"> Жақсару жоқ, бірақ үміттемін</label>

                <label for="improvements">Консультация немесе қызмет көрсету барысында не нәрсені жақсартуды қалайсыз?</label>
                <input type="text" id="improvements" name="improvements">
            </div>

            <!-- Жалпы қанағаттану -->
            <div class="section">
                <label>Сіз біздің ЛОР дәрігерімізді достарыңыз бен туыстарыңызға ұсынар ма едіңіз?</label>
                <label><input type="radio" name="recommend" value="Иә"> Иә</label>
                <label><input type="radio" name="recommend" value="Жоқ"> Жоқ</label>
                <label><input type="radio" name="recommend" value="Мүмкін"> Мүмкін</label>

                <label for="comments">Қосымша пікірлер мен ұсыныстар:</label>
                <textarea id="comments" name="comments" rows="4" placeholder="Пікіріңізді қалдырыңыз"></textarea>
            </div>

            <button type="submit">Жіберу</button>
            <a href="https://www.example.com/lor_anketa.html" target="_blank">Перейти к анкете ЛОР врача</a>
        </form>
    </div>
</body>
</html>
