# website-gunting-batu-kertas
web
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scal">
    <title>Rock Paper Scissor Game</title>
    <link rel="stylesheet" href="css/style.css">
</head>

<body>
    <!-- papan score -->
    <div class="papan-score">
        <div class="papan-player">
            <div class="nama-player">Player</div>
            <div id="score-player" class="score-player">0</div>
        </div>
        <div class="papan-computer">
            <div class="nama-computer">Computer</div>
            <div id="score-computer" class="score-computer">0</div>
        </div>
    </div>

    <!-- papan permainan-->
    <div class="papan-permainan">
        <div class="image-player">
            <img id="img-player" src="images/paper-player.jpg" alt="" width="100%">
        </div>
        <div class="image-computer">
            <img id="img-computer" src="images/paper-computer.jpg" alt="" width="100%">
        </div>
    </div>

    <!-- papan button -->
    <div class="papan-button">
        <button class="play-btn" onclick="play('rock')">Rock</button>
        <button class="play-btn" onclick="play('paper')">Paper</button>
        <button class="play-btn" onclick="play('scissor')">Scissor</button>
    </div>

    <script src="js/main.js"></script>
</body>

</html>
