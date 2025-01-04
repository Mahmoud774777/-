<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hamster Kombat Mini App</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css">
  <style>
    body {
      background-color: #181818;
      color: #ffffff;
      font-family: Arial, sans-serif;
    }
    .header {
      text-align: center;
      padding: 20px;
      background-color: #282828;
    }
    .button {
      margin: 10px 0;
      padding: 15px;
      width: 100%;
      background-color: #007bff;
      border: none;
      color: white;
      text-align: center;
      border-radius: 5px;
    }
    .button:hover {
      background-color: #0056b3;
    }
    .stats {
      display: flex;
      justify-content: space-between;
      margin: 20px;
    }
    .stats div {
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="header">
    <h1>Hamster Kombat</h1>
    <p>Welcome to your dashboard</p>
  </div>

  <div class="stats">
    <div>
      <h2>207.61</h2>
      <p>Bitcoin</p>
    </div>
    <div>
      <h2>21.5M</h2>
      <p>Power</p>
    </div>
  </div>

  <button class="button" onclick="showMessage('Mining')">Mining</button>
  <button class="button" onclick="showMessage('Tasks')">Tasks</button>
  <button class="button" onclick="showMessage('Rewards')">Rewards</button>

  <script>
    function showMessage(action) {
      alert(`${action} button clicked!`);
    }
  </script>
</body>
</html>
