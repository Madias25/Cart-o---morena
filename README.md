# Cart-o---morena<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Para minha morena</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom right, #a084ca, #cdb4db);
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
      text-align: center;
    }
    .heart {
      width: 100px;
      height: 90px;
      background: red;
      position: relative;
      transform: rotate(-45deg);
      animation: beat 1s infinite;
      margin: 20px auto;
    }
    .heart::before,
    .heart::after {
      content: "";
      width: 100px;
      height: 90px;
      background: red;
      border-radius: 50%;
      position: absolute;
    }
    .heart::before {
      top: -50px;
      left: 0;
    }
    .heart::after {
      left: 50px;
      top: 0;
    }
    @keyframes beat {
      0%, 100% {
        transform: scale(1) rotate(-45deg);
      }
      50% {
        transform: scale(1.1) rotate(-45deg);
      }
    }
    .message {
      font-size: 1.8em;
      font-weight: 500;
      margin: 20px;
    }
    .sunflowers {
      width: 150px;
      margin-top: 20px;
    }
    .button {
      margin-top: 30px;
      padding: 12px 24px;
      background-color: #fcd34d;
      border: none;
      color: #000;
      font-size: 1em;
      border-radius: 30px;
      cursor: pointer;
      text-decoration: none;
      transition: background-color 0.3s ease;
    }
    .button:hover {
      background-color: #fbbf24;
    }
  </style>
</head>
<body>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Sunflower_from_Silesia2.jpg/800px-Sunflower_from_Silesia2.jpg" alt="Girassol" class="sunflowers">
  <div class="heart"></div>
  <div class="message">Sinto sua falta, minha morena</div>
  <a class="button" href="https://www.youtube.com/watch?v=2GJhh2u5QyI" target="_blank">Ouvir "Ainda Bem"</a>
</body>
</html>
