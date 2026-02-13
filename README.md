<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Happy Valentine’s Day ❤️</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <style>
    * {
      box-sizing: border-box;
      font-family: "Arial", sans-serif;
    }

    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      text-align: center;
    }

    .card {
      background: rgba(255, 255, 255, 0.15);
      padding: 40px 30px;
      border-radius: 20px;
      max-width: 400px;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.2);
      backdrop-filter: blur(10px);
    }

    h1 {
      font-size: 2.2rem;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 30px;
    }

    .heart {
      font-size: 80px;
      animation: pulse 1.5s infinite;
      cursor: pointer;
    }

    button {
      background: #ff4d6d;
      border: none;
      padding: 12px 24px;
      font-size: 1rem;
      border-radius: 30px;
      color: #fff;
      cursor: pointer;
      transition: transform 0.2s, background 0.2s;
    }

    button:hover {
      background: #ff3355;
      transform: scale(1.05);
    }

    @keyframes pulse {
      0% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.2);
      }
      100% {
        transform: scale(1);
      }
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="heart">❤️</div>
    <h1>Happy Valentine’s Day</h1>
    <p>You make my world brighter every single day.</p>
    <button onclick="showLove()">Click for a surprise</button>
  </div>

  <script>
    function showLove() {
      alert("💖 You are loved more than words can say 💖");
    }
  </script>
</body>
</html>
