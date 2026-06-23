<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Студия звукозаписи</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: Arial, sans-serif;
            background: #F0E8F5;
            color: #333;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 40px 20px;
        }
        .container {
            max-width: 900px;
            width: 100%;
            background: white;
            border-radius: 24px;
            padding: 40px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.1);
        }
        .apps {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 24px;
            margin: 30px 0;
        }
        .app-card {
            background: #F8F4FC;
            border-radius: 16px;
            padding: 24px;
            text-align: center;
            border: 2px solid #E8DDF0;
            transition: 0.3s;
        }
        .app-card:hover {
            border-color: #6A3D8A;
            transform: translateY(-4px);
        }
        .app-card .icon { font-size: 48px; margin-bottom: 12px; }
        .app-card h3 { font-size: 20px; color: #6A3D8A; margin-bottom: 8px; }
        .app-card p { color: #666; font-size: 14px; margin-bottom: 16px; }
        .btn {
            display: inline-block;
            padding: 12px 32px;
            background: #8B5EAA;
            color: white;
            text-decoration: none;
            border-radius: 10px;
            font-weight: bold;
            transition: 0.3s;
        }
        .btn:hover { background: #6A3D8A; transform: scale(1.02); }
        .footer {
            text-align: center;
            margin-top: 30px;
            color: #aaa;
            font-size: 14px;
            border-top: 1px solid #eee;
            padding-top: 20px;
        }
        @media (max-width: 600px) {
            .apps { grid-template-columns: 1fr; }
            .container { padding: 20px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="apps">
            <!-- APK -->
            <div class="app-card">
                <div class="icon">📱</div>
                <h3>Мобильное приложение</h3>
                <p>Android — APK</p>
                <p>Мобильное приложение для записи в студию,<br>выбора даты/времени и проверки статуса заявок.<br>Версия 1.0</p>
                <a href="https://drive.google.com/uc?export=download&id=1VB1HTp_Nz2GNy-vQKbgLRiscAA5NC6CO" class="btn" download>
                    ⬇️ Скачать APK
                </a>
            </div>
            <!-- EXE -->
            <div class="app-card">
                <div class="icon">💻</div>
                <h3>Desktop приложение</h3>
                <p>Windows — EXE</p>
                <p>Десктопное приложение для записи в студию<br>и проверки статуса заявок.<br>Не требует установки Python.</p>
                <a href="https://drive.google.com/uc?export=download&id=1m-goCT8kp5Jk9E2Q1eksxbOaStY_qs0Z" class="btn" download>
                    ⬇️ Скачать EXE
                </a>
            </div>
        </div>

        <div class="footer">
            © 2026 — Авторский лендинг, Якимюк Карина Руслановна, ИС-151
        </div>
    </div>
</body>
</html>
