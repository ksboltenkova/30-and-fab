<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RSVP please</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: url('background.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
            text-align: center;
        }
        .container {
            padding: 20px;
            background: rgba(0, 0, 0, 0.5);
            margin: 20px auto;
            max-width: 600px;
            border-radius: 10px;
        }
        h1 {
            font-size: 3em;
        }
        h2 {
            font-size: 2em;
            margin-top: 20px;
        }
        p {
            font-size: 1.2em;
        }
        .rsvp-form, .dress-code, .wishlist {
            margin-top: 20px;
        }
        .rsvp-form input, .wishlist input {
            padding: 10px;
            margin: 10px 0;
            width: 100%;
            max-width: 300px;
        }
        .rsvp-form button, .wishlist button {
            padding: 10px 20px;
            font-size: 1.2em;
            background-color: #ff4081;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .rsvp-form button:hover, .wishlist button:hover {
            background-color: #e73370;
        }
        .wishlist ul {
            list-style: none;
            padding: 0;
        }
        .wishlist li {
            margin: 10px 0;
        }
        .wishlist a {
            color: #ff4081;
            text-decoration: none;
        }
        .wishlist a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Приглашаю тебя присоединиться к моему празднику!</h1>
        <p>Дата: 10 августа 2024</p>
        <p>Время: 18:00</p>
        <p>Место: г. Санкт-Петербург, ул. Большая Конюшенная, д. 27</p>

        <div class="rsvp-form">
            <h2>Очень надеюсь, мы увидимся на празднике!</h2>
            <form>
                <input type="text" name="name" placeholder="Ваше имя" required>
                <input type="email" name="email" placeholder="Ваш email" required>
                <button type="submit">Отправить</button>
            </form>
        </div>

        <div class="dress-code">
            <h2>Дресс-код</h2>
            <p>Если будет желание поддержать общий стиль вечеринки - дресскод: Банты и жемчуг</p>
            <p>Будет очень красиво, если девушки и молодые люди вдохновятся моей подборкой нарядов!</p>
        </div>

        <div class="wishlist">
            <h2>Вишлист</h2>
            <p>Если захочется сделать подарок, вот несколько идей:</p>
            <ul>
                <li><a href="https://example.com/item1" target="_blank">Подарок 1</a></li>
                <li><a href="https://example.com/item2" target="_blank">Подарок 2</a></li>
                <li><a href="https://example.com/item3" target="_blank">Подарок 3</a></li>
            </ul>
            <form>
                <input type="text" name="gift" placeholder="Название подарка" required>
                <input type="url" name="gift-link" placeholder="Ссылка на подарок" required>
                <button type="submit">Добавить подарок</button>
            </form>
        </div>
    </div>
</body>
</html>
