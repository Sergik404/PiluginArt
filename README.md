<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Роспись одежды на заказ</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f0f0f;
      color: #fff;
    }

    header {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      background: linear-gradient(135deg, #1a1a1a, #000);
      padding: 20px;
    }

    header h1 {
      font-size: 42px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 18px;
      color: #ccc;
      max-width: 600px;
    }

    .btn {
      margin-top: 20px;
      padding: 12px 24px;
      background: #ff3d7f;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 30px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }

    .card {
      background: #1c1c1c;
      border-radius: 12px;
      padding: 15px;
      text-align: center;
    }

    .card img {
      width: 100%;
      border-radius: 10px;
    }

    .steps {
      display: flex;
      flex-direction: column;
      gap: 10px;
      text-align: center;
    }

    .step {
      background: #1c1c1c;
      padding: 15px;
      border-radius: 10px;
    }

    .contact {
      text-align: center;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #777;
      font-size: 14px;
    }
  </style>
</head>

<body>

<header>
  <h1>Роспись одежды вручную 🎨 </h1>
  <p>Создаю уникальные кастомные рисунки на футболках, худи, куртках и другой одежде. Каждый дизайн — единственный в мире.</p>
  <a class="btn" href="https://t.me/PilukinArt">Заказать работу</a>
</header>

<section>
  <h2>Примеры работ</h2>
  <div class="grid">
    <div class="card">
      <img src="https://via.placeholder.com/300x300" alt="">
      <p>Аниме стиль</p>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x300" alt="">
      <p>Минимализм</p>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x300" alt="">
      <p>Авторский дизайн</p>
    </div>
  </div>
</section>

<section>
  <h2>Как это работает</h2>
  <div class="steps">
    <div class="step">1. Ты присылаешь идею или фото</div>
    <div class="step">2. Я согласовываю эскиз</div>
    <div class="step">3. Рисую на одежде вручную</div>
    <div class="step">4. Отправляю готовую работу</div>
  </div>
</section>

<section id="contact">
  <h2>Оформить заказ</h2>
  <div class="contact">
    <p>Напиши мне в Telegram и обсудим идею</p>
    <a class="btn" href="https://t.me/PilukinArt" target="_blank">Заказать роспись в Telegram</a>
  </div>
</section>

<footer>
  © 2026 Роспись одежды. Все права защищены.
</footer>

</body>
</html>
