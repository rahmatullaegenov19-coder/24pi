<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PI 24 -  IT Группа</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: #0a0a0a;
      color: #fff;
    }
    header {
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://picsum.photos/1600/600?tech') center/cover no-repeat;
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #0ff;
    }
    header h1 {
      font-size: 4em;
      text-shadow: 0 0 10px #0ff;
      margin-bottom: 20px;
    }
    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #0ff;
      text-shadow: 0 0 5px #0ff;
    }
    .music iframe {
      width: 100%;
      height: 400px;
      border: none;
      border-radius: 10px;
    }
    .contacts a, .events a, .funds a {
      color: #0ff;
      margin: 0 10px;
      text-decoration: none;
      font-size: 1.2em;
    }
    .card {
      background: #111;
      padding: 20px;
      margin: 20px 0;
      border-radius: 10px;
      box-shadow: 0 0 10px #0ff;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      color: #0ff;
    }
    /* Личный кабинет */
    .profile {
      background: #111;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px #0ff;
    }
    .profile input, .profile textarea {
      width: 100%;
      margin: 10px 0;
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #0ff;
      background: #000;
      color: #0ff;
    }
    button {
      background: #0ff;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
      color: #000;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>PI 24</h1>
    <p>С IT Группа</p>
  </header>

  <section id="about">
    <h2>О нас</h2>
    <p>Мы — IT-техно-группа, создающая современную музыку и видеоконтент. Здесь можно рассказать о стиле, истории и участниках.</p>
  </section>

  <section class="music">
    <h2>Музыка и Видео</h2>
    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" allowfullscreen></iframe>
  </section>

  <section class="profile">
    <h2>Личный кабинет (макет)</h2>
    <input type="text" placeholder="Ваше имя">
    <input type="file" placeholder="Загрузить фото">
    <textarea placeholder="Ваши заметки"></textarea>
    <button>Сохранить</button>
  </section>

  <section class="funds">
    <h2>Сборы для нуждающихся</h2>
    <div class="card">
      <h3>Сбор на проект X</h3>
      <p>Собрано: 500$ из 1000$</p>
      <a href="#">Поддержать</a>
    </div>
    <div class="card">
      <h3>Сбор на проект Y</h3>
      <p>Собрано: 300$ из 800$</p>
      <a href="#">Поддержать</a>
    </div>
  </section>

  <section class="events">
    <h2>Мероприятия</h2>
    <div class="card">
      <h3>Концерт 15 сентября</h3>
      <p>Место проведения: Центральный клуб</p>
      <a href="#">Присоединиться</a>
    </div>
    <div class="card">
      <h3>Вебинар по музыке</h3>
      <p>Дата: 25 сентября</p>
      <a href="#">Присоединиться</a>
    </div>
  </section>

  <footer>
    <p>© 2025 PI 24. Все права защищены.</p>
  </footer>
</body>
</html>
