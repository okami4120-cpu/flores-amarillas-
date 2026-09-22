<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ten tu flor 🌼</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background-color: #fef08a;
      color: #1c1917;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }

    .card {
      background: #ffffff;
      border: 4px solid #1c1917;
      border-radius: 20px;
      padding: 30px 20px;
      width: 100%;
      max-width: 380px;
      box-shadow: 8px 8px 0px #1c1917;
      text-align: center;
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 15px;
    }

    .flower-emoji {
      font-size: 80px;
      animation: bounce 1.5s infinite alternate ease-in-out;
    }

    @keyframes bounce {
      from { transform: translateY(0) scale(1); }
      to { transform: translateY(-15px) scale(1.1); }
    }

    h1 {
      font-size: 1.5rem;
      font-weight: 900;
      text-transform: uppercase;
      line-height: 1.2;
      color: #000000;
    }

    p {
      font-size: 1.05rem;
      line-height: 1.5;
      color: #44403c;
      font-weight: 500;
    }

    .btn {
      background: #facc15;
      color: #1c1917;
      font-weight: 800;
      font-size: 0.95rem;
      border: 3px solid #1c1917;
      padding: 12px 20px;
      border-radius: 12px;
      cursor: pointer;
      box-shadow: 4px 4px 0px #1c1917;
      transition: all 0.1s ease;
      margin-top: 10px;
      width: 100%;
    }

    .btn:active {
      transform: translate(2px, 2px);
      box-shadow: 2px 2px 0px #1c1917;
    }

    .footer {
      font-size: 0.75rem;
      color: #78716c;
      margin-top: 5px;
    }
  </style>
</head>
<body>

  <div class="card">
    <div class="flower-emoji">🌻</div>
    <h1>Ten tu pinche flor amarilla 🌼</h1>
    <p>Para que no andes diciendo que nadie te dio nada y puedas ir a presumirla a tus historias.</p>
    
    <button class="btn" onclick="celebrar()">¡Ya la presumí! 😎</button>

    <div class="footer">De nada, por cierto.</div>
  </div>

  <script>
    function celebrar() {
      alert("¡Eso es todo! Cumplido el deber social del día. ⚡");
    }
  </script>

</body>
</html>
