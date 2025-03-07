<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>シンプルクリックゲーム</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #d1f7d1; /* 薄緑の背景 */
        }
        h1 {
            color: #44c259; /* 濃い緑の文字色 */
        }
        #score {
            font-size: 2em;
            margin: 20px;
            color: #1e3a5f; /* スコアの文字色を濃い青に変更 */
        }
        #clickButton {
            font-size: 1.5em;
            padding: 10px 20px;
            cursor: pointer;
            position: absolute; /* ボタンをランダムに動かすために絶対位置を使います */
        }
        #countdown {
            position: absolute;
            top: 20px;
            right: 20px;
            font-size: 1.5em;
            color: red; /* 赤色のタイマー */
        }
        #playAgainButton {
            font-size: 1.5em;
            padding: 10px 20px;
            cursor: pointer;
            display: none; /* ゲームが終わったら表示 */
            margin-top: 20px;
        }
        .emoji {
            font-size: 2em;
            position: absolute;
            animation: fall 2s ease-out forwards;
        }

        /* 絵文字が上から下にシューティングするアニメーション */
        @keyframes fall {
            0% {
                opacity: 1;
                transform: translateY(0) translateX(0);
            }
            100% {
                opacity: 0;
                transform: translateY(200px) translateX(100px); /* 上から下、左右に動く */
            }
        }
    </style>
</head>
<body>
    <h1>クリックでスコアを増やそう！！！！</h1>
    <p id="score"> score: 0</p>
    <p id="countdown">timer: 15</p>
    <button id="clickButton">Click！</button>
    <button id="playAgainButton">もう一度プレイ</button>

    <script>
        let score = 0;
        const scoreDisplay = document.getElementById("score");
        const clickButton = document.getElementById("clickButton");
        const countdownDisplay = document.getElementById("countdown");
        const playAgainButton = document.getElementById("playAgainButton");

        let timer = 15; // 15秒のカウントダウン
        let countdownInterval;

        function moveButton() {
            // ボタンのランダムな位置
            const randomX = Math.random() * (window.innerWidth - 150); // ボタンの幅を考慮
            const randomY = Math.random() * (window.innerHeight - 50); // ボタンの高さを考慮
            clickButton.style.left = randomX + 'px';
            clickButton.style.top = randomY + 'px';
        }

        function startCountdown() {
            countdownInterval = setInterval(() => {
                timer--;
                countdownDisplay.textContent = `タイマー: ${timer}`;
                if (timer <= 0) {
                    clearInterval(countdownInterval);
                    countdownDisplay.textContent = 'タイムアウト！';
                    clickButton.disabled = true; // タイムアウト後にボタンを無効化
                    playAgainButton.style.display = 'inline-block'; // プレイボタンを表示
                }
            }, 1000);
        }

        // クリック時の処理
        clickButton.addEventListener("click", () => {
            if (timer > 0) {
                score++;
                scoreDisplay.textContent = "スコア: " + score;

                // 絵文字を表示
                const emoji = document.createElement('span');
                emoji.textContent = '🎉'; // 絵文字の設定
                emoji.classList.add('emoji');

                // ランダムな位置に絵文字を配置
                const randomX = Math.random() * window.innerWidth;
                const randomY = Math.random() * 200; // 初期位置のランダム調整

                emoji.style.left = randomX + 'px';
                emoji.style.top = randomY + 'px';

                document.body.appendChild(emoji);

                // 絵文字を削除（アニメーションが終わったら）
                setTimeout(() => {
                    emoji.remove();
                }, 2000); // アニメーション終了後に絵文字を削除

                moveButton(); // ボタンを新しい場所に移動
            }
        });

        // ゲーム開始とカウントダウンの開始
        startCountdown();

        // もう一度プレイボタンを押したときの処理
        playAgainButton.addEventListener("click", () => {
            score = 0;
            timer = 15;
            scoreDisplay.textContent = "スコア: " + score;
            countdownDisplay.textContent = `タイマー: ${timer}`;
            playAgainButton.style.display = 'none'; // プレイボタンを非表示
            clickButton.disabled = false; // ボタンを有効化
            startCountdown(); // カウントダウンを再スタート
            moveButton(); // 初回のボタン移動
        });
    </script>
</body>
</html>


