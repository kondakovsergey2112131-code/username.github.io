<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой сайт</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Arial, sans-serif;
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            color: white;
            text-align: center;
            overflow-x: hidden;
        }
        header {
            padding: 50px 20px;
            animation: fadeInDown 1.2s ease;
        }
        h1 {
            font-size: 2.5rem;
            margin: 0;
        }
        p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 25px;
            background: white;
            color: #2575fc;
            font-weight: bold;
            border-radius: 30px;
            text-decoration: none;
            transition: all 0.3s ease;
        }
        .btn:hover {
            background: #ffdd57;
            color: #333;
            transform: scale(1.05);
        }
        main {
            padding: 40px 20px;
            animation: fadeInUp 1.2s ease;
        }
        img {
            max-width: 300px;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
            transition: transform 0.3s ease;
        }
        img:hover {
            transform: rotate(2deg) scale(1.05);
        }
        footer {
            background: rgba(0,0,0,0.2);
            padding: 15px;
            font-size: 0.9rem;
        }
        @keyframes fadeInDown {
            from {opacity: 0; transform: translateY(-30px);}
            to {opacity: 1; transform: translateY(0);}
        }
        @keyframes fadeInUp {
            from {opacity: 0; transform: translateY(30px);}
            to {opacity: 1; transform: translateY(0);}
        }
    </style>
</head>
<body>
    <header>
        <h1>Привет! ХОЛОД ПИДОРАС</h1>
        <p>Сделан за 10 минут — но выглядит круто 😎</p>
        <a class="btn" href="#about">Узнать больше</a>
    </header>

    <main id="about">
        <h2>Обо мне</h2>
        <p>Я сделал этот сайт с нуля, без платформ и конструкторов.</p>
        <img src="https://placebear.com/400/300" alt="Милый медвежонок">
    </main>

    <footer>
        <p>© 2025 Мой сайт | Сделано с ❤️ и HTML</p>
    </footer>
</body>
</html>
