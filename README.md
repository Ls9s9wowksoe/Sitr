<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lucas Santana - Cartão Digital</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: "Helvetica Neue", Arial, sans-serif;
            background-color: #fff;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .card {
            text-align: center;
            background: #ffffff;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            width: 90%;
            max-width: 400px;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 50%;
            margin-bottom: 15px;
            border: 3px solid #eee;
        }

        h1 {
            font-size: 1.8em;
            margin: 10px 0 5px;
        }

        p {
            font-size: 1em;
            color: #777;
            margin-bottom: 20px;
        }

        .btn {
            display: block;
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            background-color: #25D366;
            color: white;
            font-size: 1.1em;
            text-decoration: none;
            border-radius: 8px;
            transition: background 0.3s;
        }

        .btn:hover {
            background-color: #1ebd5b;
        }

        .socials {
            margin-top: 15px;
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        .socials a {
            text-decoration: none;
            color: #333;
            font-size: 1.5em;
            transition: color 0.3s;
        }

        .socials a:hover {
            color: #000;
        }
    </style>
</head>
<body>
    <div class="card">
        <img src="foto.jpg" alt="Lucas Santana" class="profile-img">
        <h1>Lucas Santana</h1>
        <p>Criador de conteúdo</p>
        <a class="btn" href="https://wa.me/5538999626811?text=oi%20seja%20bem-vindo" target="_blank">Falar no WhatsApp</a>
        <div class="socials">
            <a href="https://www.instagram.com/l.s.a.n.t.a.n.a" target="_blank">📷</a>
            <a href="https://youtube.com/@santana8408" target="_blank">▶</a>
        </div>
    </div>
</body>
</html>
