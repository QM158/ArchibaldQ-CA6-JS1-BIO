<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Bear Ninja Hunter Game</title>
  <style>
    /* Simple styling for display */
    body {
      font-family: Arial, sans-serif;
      background-color: #f8f8f8;
      padding: 2rem;
      color: #333;
    }

    h1 {
      text-align: center;
      color: #5e4b32;
    }

    #game-output {
      margin-top: 2rem;
      padding: 1rem;
      border: 2px solid #ccc;
      background-color: #fffce5;
      border-radius: 8px;
    }
  </style>
</head>
<body>
  <h1>Welcome to Bear Ninja Hunter!</h1>
  <div id="game-output">
    <!-- Game result will be displayed here -->
  </div>

  <script>
    // Step 1: Prompt the user for their name
    let playerName = prompt("Welcome to Bear Ninja Hunter. Please enter your name:");

    // Step 2: Alert the user with a personalized message
    alert("Welcome, " + playerName + "! Let's begin the game!");

    // Step 3: Prompt the user to make a choice
    let playerChoice = prompt("Choose your fighter: Bear 🐻, Ninja 🥷, or Hunter 🧑‍🌾");

    // Step 4: Hard-coded computer choice
    let computerChoice = "Bear";

    // Step 5: Compose personalized game result message
    let gameMessage = "Hello " + playerName + "! You chose: " + playerChoice +
                      ". The computer chose: " + computerChoice + ".";

    // Step 6: Display the result in the HTML page
    document.getElementById("game-output").innerHTML = gameMessage;

    // Step 7: Log the result to the console
    console.log(gameMessage);
  </script>
</body>
</html>
