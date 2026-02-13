<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Will You Be My Valentine? 💘</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <style>
    * {
      box-sizing: border-box;
      font-family: "Arial", sans-serif;
    }

    body {
      margin: 0;
      min-height: 100vh;
      background: linear-gradient(135deg, #ff758c, #ff7eb3);
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      text-align: center;
    }

    .container {
      background: rgba(255, 255, 255, 0.18);
      padding: 30px;
      border-radius: 20px;
      width: 90%;
      max-width: 420px;
      backdrop-filter: blur(10px);
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.25);
    }

    img {
      width: 100%;
      border-radius: 16px;
      margin-bottom: 20px;
      object-fit: cover;
    }

    h1 {
      font-size: 2rem;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 25px;
    }

    .buttons {
      position: relative;
      height: 120px;
    }

    button {
      padding: 12px 26px;
      font-size: 1rem;
      border-radius: 30px;
      border: none;
      cursor: pointer;
      position: absolute;
      transition: 0.2s ease;
    }

    #yesBtn {
      background: #ff4d6d;
      color: white;
      left: 50%;
      transform: translateX(-50%);
    }

    #noBtn {
      background: white;
      color: #ff4d6d;
      left: 50%;
      top: 60px;
      transform: translateX(-50%);
    }

    .task, .final {
      display: none;
    }

    input {
      padding: 10px;
      border-radius: 10px;
      border: none;
      width: 85%;
      font-size: 1rem;
      margin-top: 10px;
    }

    .yay {
      font-size: 3rem;
      animation: pop 1s infinite alternate;
    }

    @keyframes pop {
      from { transform: scale(1); }
      to { transform: scale(1.15); }
    }
  </style>
</head>

<body>
  <div class="container">
    <!-- COVER PHOTO -->
    <img id="coverPhoto" src="images/cover.jpg" alt="Us ❤️">

    <h1 id="title">Will you be my Valentine? 💘</h1>
    <p id="subtitle">Be honest… but choose wisely 😏</p>

    <div class="buttons" id="buttons">
      <button id="yesBtn">Yes 💖</button>
      <button id="noBtn">No 🙄</button>
    </div>

    <!-- TASK 1 -->
    <div class="task" id="task1">
      <img src="images/task.jpg" alt="Cute moment">
      <p>First task 😌<br>Type <strong>"I am cute"</strong></p>
      <input type="text" id="input1">
    </div>

    <!-- TASK 2 -->
    <div class="task" id="task2">
      <img src="images/task.jpg" alt="Another cute moment">
      <p>Second task 😍<br>Type <strong>"I choose you"</strong></p>
      <input type="text" id="input2">
    </div>

    <!-- FINAL -->
    <div class="final" id="final">
      <img src="images/yay.jpg" alt="Celebration ❤️">
      <div class="yay">🎉 YAY!!! 🎉</div>
      <p>You’re officially my Valentine ❤️</p>
    </div>
  </div>

  <script>
    const yesBtn = document.getElementById("yesBtn");
    const noBtn = document.getElementById("noBtn");
    const buttons = document.getElementById("buttons");

    const task1 = document.getElementById("task1");
    const task2 = document.getElementById("task2");
    const final = document.getElementById("final");

    const title = document.getElementById("title");
    const subtitle = document.getElementById("subtitle");

    let yesMoves = 0;

    yesBtn.addEventListener("mouseover", () => {
      if (yesMoves < 3) {
        const x = Math.random() * 200 - 100;
        const y = Math.random() * 80 - 40;
        yesBtn.style.transform = `translate(${x}px, ${y}px)`;
        yesMoves++;
      }
    });

    noBtn.addEventListener("click", () => {
      subtitle.textContent = "No is not an option 😌";
    });

    yesBtn.addEventListener("click", () => {
      buttons.style.display = "none";
      task1.style.display = "block";
      subtitle.textContent = "Alright… prove it 👀";
    });

    document.getElementById("input1").addEventListener("input", e => {
      if (e.target.value.toLowerCase() === "i am cute") {
        task1.style.display = "none";
        task2.style.display = "block";
      }
    });

    document.getElementById("input2").addEventListener("input", e => {
      if (e.target.value.toLowerCase() === "i choose you") {
        task2.style.display = "none";
        final.style.display = "block";
        title.textContent = "💖 It’s Official 💖";
        subtitle.textContent = "";
      }
    });
  </script>
</body>
</html>
