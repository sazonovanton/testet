# Flask Snake Game

This is a simple implementation of the classic Snake game using Flask and HTML5 Canvas. The game is containerized using Docker for easy deployment and consistent runtime environment.

## Features

- Classic Snake gameplay
- Responsive controls using arrow keys
- Food generation and snake growth mechanics
- Collision detection with walls and self
- Game reset functionality

## Prerequisites

- Docker
- Docker Compose

## Setup and Running

1. Clone this repository:
   ```
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Build and run the Docker container:
   ```
   docker-compose up --build
   ```

3. Open your web browser and navigate to `http://localhost:5000` to play the game.

## How to Play

- Use the arrow keys (↑, ↓, ←, →) to control the direction of the snake.
- Eat the red food squares to grow the snake.
- Avoid colliding with the walls or the snake's own body.
- The game resets if you collide with the walls or the snake's body.

## Project Structure

- `app.py`: The main Flask application file
- `templates/index.html`: The HTML template containing the game logic
- `Dockerfile`: Instructions for building the Docker image
- `docker-compose.yml`: Docker Compose configuration file
- `requirements.txt`: Python dependencies

## Future Improvements

- Add a score display
- Implement increasing difficulty as the snake grows
- Create multiple levels or add obstacles
- Develop a high score leaderboard

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.