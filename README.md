<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>GameZone 🎮</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>🎮 GameZone</h1>
    <p>Play Free Online Games</p>
</header>

<section class="games">
    <div class="game-card">
        <h2>Chicken Run</h2>
        <button onclick="playGame()">Play Now</button>
    </div>

    <div class="game-card">
        <h2>Car Racing</h2>
        <button onclick="playGame()">Play Now</button>
    </div>

    <div class="game-card">
        <h2>Adventure Game</h2>
        <button onclick="playGame()">Play Now</button>
    </div>
</section>

<footer>
    <p>© 2026 GameZone | All Rights Reserved</p>
</footer>

<script src="script.js"></script>
</body>
</html>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0f172a;
    color: white;
    text-align: center;
}

header {
    background: #020617;
    padding: 20px;
}

.games {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin: 20px;
}

.game-card {
    background: #1e293b;
    padding: 20px;
    margin: 15px;
    width: 200px;
    border-radius: 10px;
}

.game-card button {
    padding: 10px 15px;
    background: #22c55e;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

footer {
    background: #020617;
    padding: 10px;
}
function playGame() {
    alert("Game loading... 🎮\n(You can connect real games later)");
}
