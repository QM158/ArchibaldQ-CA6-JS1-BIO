<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Bear Ninja Hunter Game</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f4f8;
      padding: 20px;
      color: #222;
    }

    h1 {
      text-align: center;
      color: #3a3a3a;
    }

    #demo {
      margin-top: 30px;
      padding: 20px;
      background-color: #ffffff;
      border: 2px solid #ccc;
      border-radius: 8px;
      font-size: 1.2rem;
    }
  </style>
</head>
<body>

  <h1>Bear Ninja Hunter</h1>
  <p id="demo">Replace this content with the calculated sum</p>

  <script>
    // Prompt for player's name and store it
    let userName = prompt("Welcome to Bear Ninja Hunter. Please enter your name:");

    // Create a personalized greeting and alert it
    alert("Welcome, " + userName + "! Let's begin the game!");

    // Prompt user for their game choice
    let userChoice = prompt("Choose your fighter: Bear 🐻, Ninja 🥷, or Hunter 🧑‍🌾");

    // Hard-coded computer choice
    let computerChoice = "Bear";

    // Construct game result message
    let resultMessage = "Hello " + userName + "! You chose: " + userChoice + 
                        ". The computer chose: " + computerChoice + ".";

    // Print result to HTML
    document.getElementById("demo").innerHTML = resultMessage;

    // Also log the result to the console
    console.log(resultMessage);
  </script>

</body>
</html>
