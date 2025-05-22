# artin-site
<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <title>ARTIN GAMES</title>
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      background-color: black;
      color: red;
      font-family: 'Press Start 2P', cursive;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }

    h1 {
      font-size: 30px;
      text-shadow: 0 0 15px red, 0 0 30px red;
      animation: pulse 1.5s infinite alternate;
    }

    p {
      font-size: 14px;
      margin-top: 20px;
    }

    button {
      background: red;
      color: black;
      border: none;
      padding: 15px 25px;
      font-size: 14px;
      cursor: pointer;
      box-shadow: 0 0 10px red;
      margin-top: 30px;
    }

    button:hover {
      background: darkred;
      box-shadow: 0 0 20px crimson;
    }

    @keyframes pulse {
      from { text-shadow: 0 0 10px red; }
      to { text-shadow: 0 0 30px red; }
    }
  </style>
</head>
<body>
  <h1>🎮 ARTIN GAMES 🎮</h1>
  <p>به دنیای بازی‌های خونین خوش اومدی!</p>
  <button onclick="alert('بازی در حال ساخت است!')">ورود به بازی</button>
</body>
</html>
