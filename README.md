# Snake Reinforcement Learning

## Overview

This project implements a self-learning Snake game using reinforcement learning techniques. The snake AI learns to play the game autonomously, improving its performance over time.

## Features

- Classic Snake game implementation
- Reinforcement learning algorithm for autonomous play
- Visualized gameplay using Pygame
- Customizable learning parameters
- Performance tracking and statistics

## Technologies Used

- Python 3.8+
- Pygame 2.1.2
- NumPy 1.21.0

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/Gaurav23V/AI_snake_game.git
   ```

2. Navigate to the project directory:
   ```
   cd AI_snake_game
   ```

## Usage

Run the main script to start the learning process:

```
python main.py
```

You can adjust the learning parameters in the `config.py` file.

## How It Works

1. **Environment**: The Snake game serves as the environment for the reinforcement learning algorithm.
2. **State**: The current game state includes the snake's position, food location, and obstacles.
3. **Actions**: The snake can move in four directions: up, down, left, or right.
4. **Reward System**: The snake receives positive rewards for eating food and negative rewards for collisions.
5. **Learning Algorithm**: A Q-learning algorithm is implemented to learn the optimal policy for playing the game.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Pygame Documentation](https://www.pygame.org/docs/)
- [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/the-book-2nd.html) by Richard S. Sutton and Andrew G. Barto
