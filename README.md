<!DOCTYPE html>
<html>
<head>
    <title>Crypto Earn Mini App</title>
    <style>
        body { text-align: center; background: #121212; color: white; font-family: sans-serif; padding-top: 50px; }
        #coin { font-size: 80px; cursor: pointer; margin: 20px; }
        #score { font-size: 30px; color: #00ffcc; }
    </style>
</head>
<body>
    <h1>Tap to Earn Mini Coin!</h1>
    <div id="score">0</div>
    <div id="coin">🪙</div>

    <script>
        let score = 0;
        document.getElementById('coin').onclick = function() {
            score += 1;
            document.getElementById('score').innerText = score;
        };
    </script>
</body>
</html>
