<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Главная страница</title>
</head>
<body>
  <header>
    <h1>Добро пожаловать на главную страницу</h1>
  </header>
  <nav>
    <ul>
      <li><a href="index.html">Главная</a></li>
      <li><a href="about.html">О нас</a></li>
    </ul>
  </nav>
  <main>
    <p>Привет, это содержимое главной страницы.</p>
  </main>
  <footer>
    <p>&copy; 2022 Мой сайт</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>О нас</title>
</head>
<body>
  <header>
    <h1>О нас</h1>
  </header>
  <nav>
    <ul>
      <li><a href="index.html">Главная</a></li>
      <li><a href="about.html">О нас</a></li>
    </ul>
  </nav>
  <main>
    <p>Здесь мы расскажем о нашей компании или проекте.</p>
  </main>
  <footer>
    <p>&copy; 2022 Мой сайт</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header, nav, main, footer {
  padding: 20px;
}

header {
  background-color: #f2f2f2;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  position: absolute;
  bottom: 0;
  width: 100%;
}
