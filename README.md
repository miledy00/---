<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Гүлдер дүкені</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Гүлдер дүкені</h1>
        <nav>
            <a href="#about">Біз туралы</a>
<a href="#catalog">Каталог</a>
            <a href="#contact">Байланыс</a>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>Біз туралы</h2>
            <p>«Гүлдер» интернет-дүкені – кез келген жағдайға арналған әдемі гүлдер сататын орын!</p>
        </section>
        <section id="catalog">
            <h2>Гүлдер Каталогы</h2>
            <div class="product" id="rose">
                <img src="rose.jpg" alt="Роза">
                <h3>Роза</h3>
  <p>Бағасы: 5000 тг</p>
                <button onclick="addToCart('Роза')">Себетке қосу</button>
            </div>
            <div class="product" id="tulip">
                <img src="tulip.jpg" alt="Тюльпан">
  <h3>Тюльпан</h3>
                <p>Бағасы: 3000 тг</p>
                <button onclick="addToCart('Тюльпан')">Себетке қосу</button>
            </div>
        </section>
        <section id="contact">
            <h2>Байланыс</h2>
            <p>Телефон: +7 777 123 4567</p>
            <p>Email: info@gulder.kz</p>
        </section>
    </main>
    <footer>
        <p>© 2024 Гүлдер дүкені</p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>

2. CSS (Файл: styles.css)

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  box-sizing: border-box;
}

header {
    background-color: #8BC34A;
   color: white;
    padding: 20px;
    text-align: center;
}

nav a {
    margin: 0 15px;
    color: white;
    text-decoration: none;
}

nav a:hover {
    text-decoration: underline;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 40px;
}

.product {
 display: inline-block;
    margin: 15px;
    border: 1px solid #ddd;
    padding: 10px;
    text-align: center;
width: 200px;
}

.product img {
    width: 100%;
    height: auto;
}

button {
    background-color: #8BC34A;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
}

button:hover {
    background-color: #6AA034;
}
