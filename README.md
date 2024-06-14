Meta Q-Learning Pac-Man Game 🎮👾
This project implements a Pac-Man game using Pygame, enhanced with a Meta Q-Learning algorithm for dynamic and adaptive gameplay. The game features a complex maze with a start and end point, and includes two ghosts that move around the maze. The game aims to find the fastest route for Pac-Man to reach the end point while avoiding ghosts and collecting rewards. The project includes continuous learning with hyperparameter adjustments to improve the performance over multiple episodes.

Features ✨
Complex Maze 🌀: The game includes a complex maze with a defined start (S) and end (E) point.
Dynamic Ghosts 👻👻: Two ghosts move within the maze, adding a level of difficulty to the game.
Q-Learning and Meta Q-Learning 📚🤖: Implements Q-Learning for Pac-Man's movements, enhanced with Meta Q-Learning for continuous improvement.
Hyperparameter Tuning 🔧📈: Continuously adjusts learning rate, exploration rate, and discount factor to optimize performance.
Reward and Penalty System 🍒⚡: Rewards for collecting food and power pellets, penalties for colliding with ghosts and looping back to previously visited states.
GIF Recording 📹: Captures gameplay and saves the 10 fastest episodes as GIFs.
Completion Message 🏆: Displays a "Game Completed!" message upon successfully reaching the end point.
Initialization 🚀
Initializes Pygame and sets up the game window.
Defines constants for colors, screen size, and grid size.
Loads the maze and converts it to a NumPy array.
Q-Learning and Meta Q-Learning Setup 📊
Initializes Q-tables and sets hyperparameters (alpha, meta_alpha, gamma, epsilon).
Defines actions for Pac-Man's movements.
Game Logic 🕹️
Main game loop handles the game state, rendering, and updating Q-values.
Ghost movements are dynamically adjusted to stay within maze boundaries.
Pac-Man's movements are guided by Q-Learning, with Meta Q-Learning for continuous improvement.
Rewards and Penalties 🎯
Defines rewards for collecting items and reaching the end.
Implements penalties for colliding with ghosts and revisiting previous states.
GIF Recording 🎥
Captures each frame of the game and saves the fastest episodes as GIFs.
