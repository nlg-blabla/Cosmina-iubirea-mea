# Cosmina-iubirea-mea
pentru scumpa mea fatiță!
<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8" />
  <title>Cosmina 💖</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
      max-width: 400px;
      width: 90%;
    }

    h1 {
      color: #e91e63;
      margin-bottom: 10px;
    }

    p {
      font-size: 18px;
      margin-bottom: 25px;
    }

    button {
      font-size: 18px;
      padding: 12px 25px;
      border-radius: 30px;
      border: none;
      cursor: pointer;
      margin: 10px;
    }

    #yes {
      background: #4CAF50;
      color: white;
    }

    #no {
      background: #f44336;
      color: white;
      position: relative;
    }

    #question {
      font-weight: bold;
      color: #333;
      min-height: 40px;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Cosmina 💕</h1>
    <p>Vrei să fii iubita mea?</p>

    <div id="question"></div>

    <button id="yes">DA 💖</button>
    <button id="no">NU 🙄</button>
  </div>

  <script>
    const questions = [
      "Ești absolut sigură?",
      "Mai gândește-te puțin…",
      "Sigur nu vrei să mai încerci?",
      "Chiar vrei să apeși NU?",
      "Gândește-te cât de drăguț sunt 😌",
      "Poate ai apăsat greșit?",
      "Mai dăm o șansă?",
      "E ultimul tău răspuns?",
      "Ai consultat inima?",
      "Inima ce zice?",
      "Creierul e sigur?",
      "Dar sufletul?",
      "O să regreți, știi asta, nu?",
      "Toată lumea ar zice DA 😏",
      "Cosmina, chiar NU?",
      "Respiră adânc… și acum?",
      "Mai stăm puțin pe gânduri?",
      "Te-ai gândit bine-bine?",
      "E un NU… sau un DA ascuns?",
      "Ultima întrebare: sigur sigur sigur?"
    ];

    let index = 0;
    const questionDiv = document.getElementById("question");
    const noBtn = document.getElementById("no");
    const yesBtn = document.getElementById("yes");

    noBtn.addEventListener("mouseover", () => {
      const x = Math.random() * 200 - 100;
      const y = Math.random() * 200 - 100;
      noBtn.style.transform = `translate(${x}px, ${y}px)`;

      if (index < questions.length) {
        questionDiv.textContent = questions[index];
        index++;
      }
    });

    yesBtn.addEventListener("click", () => {
      document.body.innerHTML = `
        <div style="
          height:100vh;
          display:flex;
          align-items:center;
          justify-content:center;
          text-align:center;
          background:linear-gradient(135deg,#ff9a9e,#fad0c4);
          font-family:Arial;">
          <h1>Știam eu 😍💖<br>Suntem oficial împreună!</h1>
        </div>
      `;
    });
  </script>
</body>
</html>

<!-- Pătrățel cu videoclip YouTube -->
<div class="video-box" style="width:320px; height:180px; margin:20px auto; border:3px solid #ff69b4; border-radius:12px; overflow:hidden;">
  <iframe 
    src="https://www.youtube.com/embed/R_sITjl1G2U" 
    title="YouTube video player" frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

<p style="text-align:center; color:#ff1493;">Apasă play în pătrățel pentru a asculta muzica lui Costel Biju!</p>
