<!DOCTYPE html>
<html>
<head>
  <title>Snake Game</title>
  <style>
    #game-board {
      width: 300px;
      height: 300px;
      border: 1px solid black;
    }
  </style>
</head>
<body>
  <h1>Snake Game</h1>
  <canvas id="game-board"></canvas>
  <script>
    const canvas = document.getElementById("game-board");
    const ctx = canvas.getContext("2d");

    const gridSize = 20;
    const snakeColor = "green";
    const foodColor = "red";

    let snake = [{ x: 5, y: 5 }];
    let food = { x: 10, y: 10 };
    let dx = 1;
    let dy = 0;

    function drawSnake() {
      ctx.fillStyle = snakeColor;
      snake.forEach(segment => {
        ctx.fillRect(segment.x * gridSize, segment.y * gridSize, gridSize, gridSize);
      });
    }

    function drawFood() {
      ctx.fillStyle = foodColor;
      ctx.fillRect(food.x * gridSize, food.y * gridSize, gridSize, gridSize);
    }

    function moveSnake() {
      const head = { x: snake[0].x + dx, y: snake[0].y + dy };
      snake.unshift(head);

      if (head.x === food.x && head.y === food.y) {
        // Snake ate the food
        food = { x: Math.floor(Math.random() * (canvas.width / gridSize)), y: Math.floor(Math.random() * (canvas.height / gridSize)) };
      } else {
        // Remove the tail
        snake.pop();
      }
    }

    function checkCollision() {
      const head = snake[0];
      if (
        head.x < 0 ||
        head.x >= canvas.width / gridSize ||
        head.y < 0 ||
        head.y >= canvas.height / gridSize
      ) {
        clearInterval(gameLoop);
        alert("Game over!");
      }

      for (let i = 1; i < snake.length; i++) {
        if (snake[i].x === head.x && snake[i].y === head.y) {
          clearInterval(gameLoop);
          alert("Game over!");
        }
      }
    }

    function gameLoop() {
      ctx.clearRect(0, 0, canvas.width, canvas.height);
      drawSnake();
      drawFood();
      moveSnake();
      checkCollision();
    }

    document.addEventListener("keydown", (event) => {
      switch (event.key) {
        case "ArrowUp":
          if (dy !== 1) {
            dx = 0;
            dy = -1;
          }
          break;
        case "ArrowDown":
          if (dy !== -1) {
            dx = 0;
            dy = 1;
          }
          break;
        case "ArrowLeft":
          if (dx !== 1) {
            dx = -1;
            dy = 0;
          }
          break;
        case "ArrowRight":
          if (dx !== -1) {
            dx = 1;
            dy = 0;
          }
          break;
      }
    });

    setInterval(gameLoop, 100);
  </script>
</body>
</html>
