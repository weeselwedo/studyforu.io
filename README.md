# studyforu.io
study here now
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>StudyForU.io - Game Collection</title>
  <style>
    /* Global dark theme style */
    body {
      background-color: #121212;
      color: #ffffff;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      padding: 20px;
      text-align: center;
      background-color: #1e1e1e;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      margin-top: 10px;
      font-size: 1.2em;
    }
    .game-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .game-card {
      background-color: #1e1e1e;
      border: 1px solid #333;
      border-radius: 8px;
      overflow: hidden;
      text-align: center;
    }
    .game-card h2 {
      margin: 10px;
      font-size: 1.5em;
    }
    .game-card iframe {
      width: 100%;
      height: 400px;
      border: none;
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #1e1e1e;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>StudyForU.io</h1>
    <p>Your collection of browser-based games</p>
  </header>
  <main>
    <div class="game-grid">
      <!-- Game Card 1: Run -->
      <div class="game-card">
        <h2>Run</h2>
        <!-- Replace the src URL with the actual URL of the Run game -->
        <iframe src="https://example.com/run-game"></iframe>
      </div>
      <!-- Game Card 2: Papa's Pizzeria -->
      <div class="game-card">
        <h2>Papa's Pizzeria</h2>
        <!-- Replace the src URL with the actual URL of the Papa's Pizzeria game -->
        <iframe src="https://example.com/papas-pizzeria-game"></iframe>
      </div>
      <!-- Add more game cards as needed -->
    </div>
  </main>
  <footer>
    <p>&copy; 2025 StudyForU.io. All rights reserved.</p>
  </footer>
</body>
</html>
