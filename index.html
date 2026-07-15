<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Лёгкий кликер — Тёмная тема</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: #0d1117;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            font-family: 'Segoe UI', 'Inter', system-ui, -apple-system, sans-serif;
            -webkit-tap-highlight-color: transparent;
            user-select: none;
            padding: 16px;
        }

        .container {
            background: #161b22;
            border-radius: 24px;
            padding: 28px 24px 32px;
            width: 100%;
            max-width: 420px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.5), 0 0 0 1px rgba(255, 255, 255, 0.04);
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
        }

        h1 {
            font-size: 2.2rem;
            font-weight: 700;
            color: #f0e6d2;
            letter-spacing: -0.5px;
            margin-bottom: -4px;
        }

        .score-wrapper {
            background: #0d1117;
            border-radius: 16px;
            padding: 14px 20px;
            width: 100%;
            box-shadow: inset 0 2px 6px rgba(0, 0, 0, 0.6);
            border: 1px solid #30363d;
        }

        .score-label {
            font-size: 0.8rem;
            text-transform: uppercase;
            letter-spacing: 0.08em;
            color: #8b949e;
            margin-bottom: 4px;
        }

        .score {
            font-size: 2rem;
            font-weight: 700;
            color: #ffd966;
            word-break: break-all;
            line-height: 1.2;
            font-variant-numeric: tabular-nums;
            font-family: 'JetBrains Mono', 'Fira Code', 'Consolas', monospace;
        }

        .per-click {
            font-size: 0.9rem;
            color: #8b949e;
            margin-top: -6px;
            display: flex;
            align-items: center;
            gap: 6px;
            justify-content: center;
        }
        .per-click span {
            color: #7ee787;
            font-weight: 600;
            font-size: 1rem;
        }

        .click-btn {
            width: 130px;
            height: 130px;
            border-radius: 50%;
            border: none;
            background: radial-gradient(circle at 40% 35%, #f5c842, #d4940b);
            box-shadow: 0 12px 32px rgba(212, 148, 11, 0.45), 0 0 0 4px rgba(255, 215, 0, 0.2);
            font-size: 1.2rem;
            font-weight: 700;
            color: #1a1300;
            cursor: pointer;
            transition: transform 0.08s ease, box-shadow 0.08s ease;
            letter-spacing: 0.5px;
            text-shadow: 0 1px 0 rgba(255, 255, 255, 0.3);
            position: relative;
            outline: none;
            -webkit-tap-highlight-color: transparent;
        }

        .click-btn:active {
            transform: scale(0.9);
            box-shadow: 0 4px 16px rgba(212, 148, 11, 0.7), 0 0 0 6px rgba(255, 215, 0, 0.35);
            background: radial-gradient(circle at 40% 35%, #e6b830, #b87a08);
        }

        .click-btn:hover {
            box-shadow: 0 14px 38px rgba(212, 148, 11, 0.55), 0 0 0 5px rgba(255, 215, 0, 0.25);
        }

        .upgrades {
            display: flex;
            flex-direction: column;
            gap: 12px;
            width: 100%;
        }

        .upgrade {
            background: #1c2128;
            border-radius: 16px;
            padding: 14px 16px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            border: 1px solid #30363d;
            transition: border-color 0.2s, background 0.2s;
            gap: 10px;
            flex-wrap: wrap;
        }

        .upgrade:hover {
            border-color: #58a6ff55;
            background: #1e2430;
        }

        .upgrade-info {
            display: flex;
            flex-direction: column;
            gap: 3px;
            text-align: left;
            min-width: 120px;
            flex: 1;
        }

        .upgrade-name {
            font-weight: 700;
            font-size: 1rem;
            color: #e6edf3;
            letter-spacing: -0.2px;
        }

        .upgrade-desc {
            font-size: 0.78rem;
            color: #8b949e;
            line-height: 1.3;
        }

        .buy-btn {
            background: #238636;
            border: 1px solid #3fb950;
            color: #fff;
            font-weight: 600;
            font-size: 0.85rem;
            padding: 10px 16px;
            border-radius: 20px;
            cursor: pointer;
            white-space: nowrap;
            transition: all 0.15s ease;
            letter-spacing: 0.2px;
            min-width: 110px;
            text-align: center;
            outline: none;
            -webkit-tap-highlight-color: transparent;
        }

        .buy-btn:hover:not(:disabled) {
            background: #2ea043;
            border-color: #3fb950;
            box-shadow: 0 0 12px rgba(63, 185, 80, 0.3);
            transform: translateY(-1px);
        }

        .buy-btn:active:not(:disabled) {
            transform: scale(0.95);
            background: #1f6f32;
        }

        .buy-btn:disabled {
            background: #21262d;
            border-color: #30363d;
            color: #484f58;
            cursor: not-allowed;
            box-shadow: none;
            transform: none;
        }

        .buy-btn.purchased {
            background: #1b3a22;
            border-color: #2d5a38;
            color: #7ee787;
            cursor: default;
            pointer-events: none;
        }

        .auto-badge {
            display: inline-block;
            background: #1f6f32;
            color: #7ee787;
            font-size: 0.7rem;
            padding: 3px 10px;
            border-radius: 20px;
            font-weight: 600;
            letter-spacing: 0.3px;
            margin-left: 6px;
            vertical-align: middle;
        }

        @media (max-width: 380px) {
            .container {
                padding: 20px 14px 24px;
            }
            .score {
                font-size: 1.4rem;
            }
            .click-btn {
                width: 100px;
                height: 100px;
                font-size: 1rem;
            }
            .buy-btn {
                padding: 8px 12px;
                min-width: 90px;
                font-size: 0.75rem;
            }
            .upgrade {
                padding: 10px 12px;
                gap: 6px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>💰 Кликер</h1>

        <div class="score-wrapper">
            <div class="score-label">Баланс</div>
            <div class="score" id="scoreDisplay">0</div>
        </div>

        <button class="click-btn" id="clickBtn" title="Кликни меня!">
            КЛИК
        </button>

        <div class="per-click">
            За клик: <span id="perClickDisplay">1</span>
            <span id="speedBadge" style="display:none;" class="auto-badge">x2</span>
        </div>

        <div class="upgrades">
            <!-- Улучшение 1: Мега-клик -->
            <div class="upgrade" id="upgrade1Card">
                <div class="upgrade-info">
                    <div class="upgrade-name">🖱️ Мега-клик</div>
                    <div class="upgrade-desc">+1 000 за клик</div>
                </div>
                <button class="buy-btn" id="buyUpgrade1">Купить за 1</button>
            </div>

            <!-- Улучшение 2: Автокликер -->
            <div class="upgrade" id="upgrade2Card">
                <div class="upgrade-info">
                    <div class="upgrade-name">⚡ Автокликер</div>
                    <div class="upgrade-desc" id="autoClickerDesc">10 кликов/сек</div>
                </div>
                <button class="buy-btn" id="buyUpgrade2">Купить за 100</button>
            </div>

            <!-- Улучшение 3: Ускорение x2 -->
            <div class="upgrade" id="upgrade3Card">
                <div class="upgrade-info">
                    <div class="upgrade-name">🚀 Ускорение x2</div>
                    <div class="upgrade-desc" id="speedDesc">Всё в 2 раза быстрее!</div>
                </div>
                <button class="buy-btn" id="buyUpgrade3">Купить за 10 000</button>
            </div>
        </div>
    </div>

    <script>
        (function() {
            // --- Состояние игры ---
            const game = {
                clicks: 0,
                clicksPerClick: 1,
                autoClickerActive: false,
                autoClickerBaseDelay: 100, // мс → 10 кликов/сек
                autoClickerIntervalId: null,
                speedMultiplier: 1, // глобальный множитель скорости (влияет на автокликер и клики)
                upgrade1Count: 0,
                upgrade1Price: 1,
                upgrade2Purchased: false,
                upgrade2Price: 100,
                upgrade3Count: 0,
                upgrade3Price: 10000,
            };

            // --- DOM элементы ---
            const scoreDisplay = document.getElementById('scoreDisplay');
            const perClickDisplay = document.getElementById('perClickDisplay');
            const clickBtn = document.getElementById('clickBtn');
            const buyUpgrade1Btn = document.getElementById('buyUpgrade1');
            const buyUpgrade2Btn = document.getElementById('buyUpgrade2');
            const buyUpgrade3Btn = document.getElementById('buyUpgrade3');
            const autoClickerDesc = document.getElementById('autoClickerDesc');
            const speedDesc = document.getElementById('speedDesc');
            const speedBadge = document.getElementById('speedBadge');

            // --- Форматирование чисел: все разряды, без сокращений ---
            function formatNumber(num) {
                // Округляем вниз, так как клики — целые
                const intNum = Math.floor(num);
                // Используем toLocaleString с русским стилем (пробелы как разделители тысяч)
                return intNum.toLocaleString('ru-RU');
            }

            // --- Запуск / перезапуск автокликера ---
            function getAutoClickerDelay() {
                return game.autoClickerBaseDelay / game.speedMultiplier;
            }

            function stopAutoClicker() {
                if (game.autoClickerIntervalId !== null) {
                    clearInterval(game.autoClickerIntervalId);
                    game.autoClickerIntervalId = null;
                }
                game.autoClickerActive = false;
            }

            function startAutoClicker() {
                if (game.autoClickerActive) {
                    stopAutoClicker();
                }
                const delay = getAutoClickerDelay();
                game.autoClickerIntervalId = setInterval(() => {
                    game.clicks += game.clicksPerClick;
                    updateUI();
                }, delay);
                game.autoClickerActive = true;
            }

            function restartAutoClicker() {
                if (game.autoClickerActive) {
                    startAutoClicker();
                }
            }

            // --- Обновление интерфейса ---
            function updateUI() {
                // Счетчик
                scoreDisplay.textContent = formatNumber(game.clicks);

                // За клик
                perClickDisplay.textContent = formatNumber(game.clicksPerClick);

                // Бейдж скорости
                if (game.speedMultiplier > 1) {
                    speedBadge.style.display = 'inline-block';
                    speedBadge.textContent = 'x' + game.speedMultiplier;
                } else {
                    speedBadge.style.display = 'none';
                }

                // --- Кнопка Улучшения 1 ---
                if (game.upgrade1Count === 0) {
                    buyUpgrade1Btn.textContent = 'Купить за ' + formatNumber(game.upgrade1Price);
                    buyUpgrade1Btn.disabled = game.clicks < game.upgrade1Price;
                    buyUpgrade1Btn.classList.remove('purchased');
                } else {
                    // Уже куплено хотя бы раз — разрешаем докупать по новой цене
                    buyUpgrade1Btn.textContent = 'Купить за ' + formatNumber(game.upgrade1Price);
                    buyUpgrade1Btn.disabled = game.clicks < game.upgrade1Price;
                    buyUpgrade1Btn.classList.remove('purchased');
                    // Если цена стала нереально большой, можно просто показать "Куплено", но оставим возможность
                    // Для лёгкого кликера оставим докупку
                }

                // --- Кнопка Улучшения 2 (Автокликер) ---
                if (game.upgrade2Purchased) {
                    buyUpgrade2Btn.textContent = 'Активен';
                    buyUpgrade2Btn.disabled = true;
                    buyUpgrade2Btn.classList.add('purchased');
                    const currentDelay = getAutoClickerDelay();
                    const clicksPerSec = (1000 / currentDelay).toFixed(1);
                    autoClickerDesc.textContent = clicksPerSec + ' кликов/сек';
                } else {
                    buyUpgrade2Btn.textContent = 'Купить за ' + formatNumber(game.upgrade2Price);
                    buyUpgrade2Btn.disabled = game.clicks < game.upgrade2Price;
                    buyUpgrade2Btn.classList.remove('purchased');
                    autoClickerDesc.textContent = '10 кликов/сек';
                }

                // --- Кнопка Улучшения 3 (Ускорение x2) ---
                buyUpgrade3Btn.textContent = 'Купить за ' + formatNumber(game.upgrade3Price);
                buyUpgrade3Btn.disabled = game.clicks < game.upgrade3Price;
                if (game.upgrade3Count > 0) {
                    speedDesc.textContent = 'Множитель скорости: x' + game.speedMultiplier +
                        ' (клики и автоклик)';
                } else {
                    speedDesc.textContent = 'Всё в 2 раза быстрее!';
                }
                buyUpgrade3Btn.classList.remove('purchased');
                // Не блокируем множественные покупки
            }

            // --- Обработчики ---
            clickBtn.addEventListener('click', () => {
                game.clicks += game.clicksPerClick;
                updateUI();
            });

            // Улучшение 1: Мега-клик
            buyUpgrade1Btn.addEventListener('click', () => {
                if (game.clicks >= game.upgrade1Price) {
                    game.clicks -= game.upgrade1Price;
                    game.clicksPerClick += 1000;
                    game.upgrade1Count++;
                    // Цена растёт: умножаем на 10 для следующей покупки
                    game.upgrade1Price *= 10;
                    updateUI();
                }
            });

            // Улучшение 2: Автокликер
            buyUpgrade2Btn.addEventListener('click', () => {
                if (!game.upgrade2Purchased && game.clicks >= game.upgrade2Price) {
                    game.clicks -= game.upgrade2Price;
                    game.upgrade2Purchased = true;
                    startAutoClicker();
                    updateUI();
                }
            });

            // Улучшение 3: Ускорение x2
            buyUpgrade3Btn.addEventListener('click', () => {
                if (game.clicks >= game.upgrade3Price) {
                    game.clicks -= game.upgrade3Price;
                    game.speedMultiplier *= 2;
                    game.clicksPerClick *= 2;
                    game.upgrade3Count++;
                    game.upgrade3Price *= 2; // цена удваивается
                    restartAutoClicker();
                    updateUI();
                }
            });

            // --- Инициализация ---
            updateUI();

            // Обработка touch-событий для мобильных (убирает возможные задержки)
            clickBtn.addEventListener('touchstart', (e) => {
                e.preventDefault();
                game.clicks += game.clicksPerClick;
                updateUI();
            });

            console.log('🎮 Лёгкий кликер готов! Темный дизайн, 3 улучшения, числа без сокращений.');
            console.log('   Улучшение 1: +1000 за клик (начальная цена 1)');
            console.log('   Улучшение 2: Автокликер 10/сек (цена 100)');
            console.log('   Улучшение 3: Ускорение x2 всего (цена 10 000)');
        })();
    </script>
</body>
</html>
