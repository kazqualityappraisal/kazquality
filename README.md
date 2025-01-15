<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Оценка имущества</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        header img {
            max-width: 150px;
        }
        header h1 {
            margin: 10px 0 0;
            font-size: 24px;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #007BFF;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
            background: #fff;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        section h2 {
            font-size: 20px;
            margin-bottom: 10px;
        }
        footer {
            text-align: center;
            padding: 10px 20px;
            background-color: #fff;
            border-top: 1px solid #ddd;
            margin-top: 20px;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form input, .contact-form textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        .contact-form button {
            padding: 10px;
            background-color: #007BFF;
            color: #fff;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <img src="Новый точечный рисунок.jpeg" alt="Логотип">
        <h1>Оценка имущества</h1>
        <nav>
            <a href="#services">Услуги</a>
            <a href="#contact">Контакты</a>
        </nav>
    </header>

    <section id="services">
        <h2>Наши услуги</h2>
        <p>Мы предоставляем услуги профессиональной оценки:</p>
        <ul>
            <li>Недвижимости</li>
            <li>Транспортных средств</li>
            <li>Оборудования</li>
            <li>Бизнеса</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Связаться с нами</h2>
        <form class="contact-form">
            <input type="text" name="name" placeholder="Ваше имя" required>
            <input type="email" name="email" placeholder="Ваш email" required>
            <textarea name="message" rows="5" placeholder="Ваше сообщение" required></textarea>
            <button type="submit">Отправить</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Оценка имущества. Все права защищены.</p>
    </footer>
</body>
</html>
