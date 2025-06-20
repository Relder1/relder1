<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Pretty Telegram Link</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      background: #222;
      color: #eee;
      font-family: 'Segoe UI', Arial, sans-serif;
      display: flex;
      height: 100vh;
      justify-content: center;
      align-items: center;
      margin: 0;
    }
    .telegram-link {
      display: flex;
      align-items: center;
      background: #2aabee;
      border-radius: 12px;
      padding: 20px 30px;
      text-decoration: none;
      box-shadow: 0 4px 24px #0005;
      transition: background 0.2s;
    }
    .telegram-link:hover {
      background: #229ed9;
    }
    .telegram-link img {
      width: 64px;
      height: 64px;
      border-radius: 50%;
      object-fit: cover;
      margin-right: 20px;
      border: 3px solid #fff;
      box-shadow: 0 2px 12px #0003;
    }
    .telegram-link .label {
      font-size: 1.5em;
      font-weight: bold;
      color: #fff;
    }
  </style>
</head>
<body>
  <a class="telegram-link" href="https://t.me/yourusername" target="_blank">
    <img src="https://telegram.org/img/t_logo.png" alt="Telegram">
    <span class="label">Contact me on Telegram</span>
  </a>
  <script>
  </script>
</body>
</html>
