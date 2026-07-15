<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Скоро тут будет магия</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background: linear-gradient(135deg, #fdfcfb 0%, #e2d1c3 100%);
        }
        .card {
            background: rgba(255, 255, 255, 0.7);
            backdrop-filter: blur(10px);
            padding: 60px 80px;
            border-radius: 40px;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
            text-align: center;
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: scale(1.02);
        }
        .emoji-big {
            font-size: 64px;
            display: block;
            margin-bottom: 20px;
        }
        h1 {
            font-size: 32px;
            font-weight: 700;
            color: #1a1a1a;
            margin: 0 0 10px;
        }
        .highlight {
            background: #ffd700;
            padding: 0 12px;
            color: #1a1a1a;
            border-radius: 20px;
        }
        p {
            font-size: 18px;
            color: #555;
            margin-top: 15px;
            letter-spacing: 1px;
        }
        .spinner {
            display: inline-block;
            animation: spin 4s linear infinite;
            font-size: 20px;
            margin-left: 5px;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body>
    <div class="card">
        <span class="emoji-big">🚀</span>
        <h1>Сайт <span class="highlight">новенький</span></h1>
        <p style="font-size: 26px; font-weight: 300; margin-top: 5px;">
            Пока ничего нет <span style="color: #ff6b6b;">♥</span>
        </p>
        <p>
            Но скоро здесь будет <strong>волшебство</strong> 
            <span class="spinner">✨</span>
        </p>
        <div style="margin-top: 30px; height: 3px; width: 80px; background: #ddd; border-radius: 10px; margin-left: auto; margin-right: auto;"></div>
        <p style="font-size: 14px; color: #aaa; margin-top: 20px;">Осталось совсем чуть-чуть</p>
    </div>
</body>
</html>
