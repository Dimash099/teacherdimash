﻿<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Сағатбек Дінмұхаммед - Информатика Мұғалімінің Веб-сайты</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #eaeaea;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
            border-bottom: 4px solid #388E3C;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            padding: 15px 25px;
            color: white;
            text-align: center;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        nav a:hover {
            background-color: #575757;
        }
        section {
            padding: 20px;
            margin: 15px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #4CAF50;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        label {
            margin-bottom: 5px;
        }
        input[type="text"], textarea {
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #388E3C;
        }
    </style>
</head>
<body>

<header>
    <h1>Сағатбек Дінмұхаммедтің Информатика Веб-сайты</h1>
    <p>Оқушыларға арналған информатика ресурстары және тапсырмалар</p>
</header>

<nav>
    <a href="#home">Басты бет</a>
    <a href="#materials">Оқу материалдары</a>
    <a href="#assignments">Тапсырмалар</a>
    <a href="#forum">Форум</a>
    <a href="#feedback">Кері байланыс</a>
</nav>

<section id="home">
    <h2>Қош келдіңіз!</h2>
    <p>Сағатбек Дінмұхаммед, информатика пәнінің мұғалімі, сіздерді осы веб-сайтта қарсы алады.</p>
    <p>Бұл сайтта сіз информатикаға қатысты оқу материалдары мен үй тапсырмаларын таба аласыз.</p>
    <p>Жаңалықтар мен хабарландырулар:</p>
    <ul>
        <li>10.10.2024 - Жаңа сабақ: Программалау негіздері</li>
        <li>12.10.2024 - Үй тапсырмасы: Python-да код жазу</li>
    </ul>
</section>

<section id="materials">
    <h2>Оқу материалдары</h2>
    <p>Тақырып бойынша оқу материалдары:</p>
    <ul>
        <li><a href="#">Информатика - Программалау негіздері</a></li>
        <li><a href="#">Информатика - Алгоритмдер және деректер құрылымдары</a></li>
    </ul>
</section>

<section id="assignments">
    <h2>Тапсырмалар</h2>
    <p>Үй тапсырмалары мен интерактивті тестілер:</p>
    <ul>
        <li><a href="#">Python: Үй тапсырмасы 1</a></li>
        <li><a href="#">HTML: Веб-бет жасау тесті</a></li>
    </ul>
</section>

<section id="forum">
    <h2>Форум</h2>
    <p>Оқушылардың сұрақтары мен мұғалімнің жауаптары.</p>
    <p>Сабақты талқылауға арналған тақырыптар:</p>
    <ul>
        <li><a href="#">Программалау сабақтары</a></li>
        <li><a href="#">Жобалар мен тапсырмалар</a></li>
    </ul>
</section>

<section id="feedback">
    <h2>Кері байланыс</h2>
    <p>Оқушылар мен ата-аналардың сұрақтары мен ұсыныстары үшін форма:</p>
    <form>
        <label for="name">Атыңыз:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="message">Хабарлама:</label>
        <textarea id="message" name="message" rows="4" cols="50" required></textarea>
        
        <input type="submit" value="Жіберу">
    </form>
</section>

<footer>
    <p>Сағатбек Дінмұхаммед - Информатика Мұғалімі &copy; 2024</p>
</footer>

</body>
</html>
