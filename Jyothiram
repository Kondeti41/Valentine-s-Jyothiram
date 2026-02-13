<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Husband Jyothiram ❤️</title>

<style>
body {
    margin: 0;
    padding: 0;
    height: 100vh;
    font-family: 'Segoe UI', sans-serif;
    background: black;
    overflow: hidden;
    color: white;
    text-align: center;
}

/* Password Screen */
#passwordScreen {
    position: absolute;
    width: 100%;
    height: 100%;
    background: radial-gradient(circle, #4b0f2f, #1a0015, black);
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

input {
    padding: 10px;
    border-radius: 20px;
    border: none;
    text-align: center;
    font-size: 16px;
}

button {
    margin-top: 15px;
    padding: 10px 25px;
    border: none;
    border-radius: 25px;
    background: #ff4d6d;
    color: white;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background: #ff1e4d;
}

/* Main Content */
#mainContent {
    display: none;
    height: 100vh;
    background: radial-gradient(circle at top, #4b0f2f, #1a0015, black);
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

h1 {
    font-size: 3em;
    text-shadow: 0 0 20px #ff4d6d;
}

img {
    width: 300px;
    border-radius: 20px;
    margin-top: 20px;
    box-shadow: 0 0 40px #ff4d6d;
}

.letter {
    display: none;
    margin-top: 20px;
    max-width: 420px;
    font-size: 1.2em;
    line-height: 1.6;
}

/* Floating Hearts */
.heart {
    position: absolute;
    bottom: -50px;
    color: #ff4d6d;
    animation: floatUp 8s linear infinite;
}

@keyframes floatUp {
    0% { transform: translateY(0); opacity: 1; }
    100% { transform: translateY(-100vh); opacity: 0; }
}

/* Glowing 6-month Anniversary Text */
.anniversary {
    margin-top: 10px;
    font-size: 1.5em;
    color: #ffccff;
    text-shadow: 0 0 10px #ff4d6d, 0 0 20px #ff1e4d, 0 0 30px #ff4d6d;
    animation: glow 2s ease-in-out infinite alternate;
}

@keyframes glow {
    0% { text-shadow: 0 0 5px #ff4d6d, 0 0 10px #ff1e4d; }
    100% { text-shadow: 0 0 20px #ff4d6d, 0 0 30px #ff1e4d; }
}
</style>
</head>

<body>

<!-- Password Screen -->
<div id="passwordScreen">
    <h2>🔐 Private Message For Jyothiram</h2>
    <input type="password" id="passwordInput" placeholder="Enter our secret">
    <button onclick="checkPassword()">Unlock ❤️</button>
    <p id="error" style="color:red;"></p>
</div>

<!-- Main Content -->
<div id="mainContent">
    <h1>Happy Valentine Jyothiram ❤️</h1>
    <div class="anniversary">6 Months Together – Feb 14 💍</div>

    <img src="https://img.freepik.com/free-vector/cute-boy-cheek-pinching-his-girlfriend-happy-valentine-cartoon-character-illustration_56104-367.jpg?semt=ais_hybrid&w=740&q=80"
    alt="Valentine Image">

    <button onclick="openLetter()">💌 Open My Heart</button>

    <div class="letter" id="loveLetter">
        My Dearest Jyothiram ❤️<br><br>

        Today, February 14, we celebrate 6 beautiful months of marriage together 💍✨  

        These six months with you have been the most precious time of my life.  
        Every laugh, every hug, every moment with you has made my world brighter.  

        Marrying you was the best decision I have ever made.  
        You are my husband, my best friend, and my forever love.  

        I promise to stand by you, support you,  
        and love you more with each passing day.  

        Happy 6 Months Anniversary My Love ❤️  
        Forever Yours, <br><strong>Nikitha 💕</strong>
    </div>
</div>

<!-- Background Music -->
<audio id="bgMusic" loop>
    <source src="love.mp3" type="audio/mpeg">
</audio>

<script>
const correctPassword = "jyothiram"; // Your secret password

function checkPassword() {
    const input = document.getElementById("passwordInput").value;
    if (input === correctPassword) {
        document.getElementById("passwordScreen").style.display = "none";
        document.getElementById("mainContent").style.display = "flex";
        document.getElementById("bgMusic").play();
        startHearts();
    } else {
        document.getElementById("error").innerText = "Wrong Password 💔";
    }
}

function openLetter() {
    document.getElementById("loveLetter").style.display = "block";
}

/* Floating Hearts */
function createHeart() {
    const heart = document.createElement("div");
    heart.classList.add("heart");
    heart.innerHTML = "❤";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.fontSize = Math.random() * 20 + 15 + "px";
    heart.style.animationDuration = Math.random() * 3 + 5 + "s";
    document.body.appendChild(heart);
    setTimeout(() => heart.remove(), 8000);
}

function startHearts() {
    setInterval(createHeart, 500);
}
</script>

</body>
</html>
