StarPath Graph Game
---------------------------
you will need to install dependancies before running main class!
have fun!

Overview
The Shortest Path Game is an interactive, space-themed puzzle game where the goal is to correctly guess the shortest path between two randomly selected nodes on a graph. Players navigate through five levels, each presenting a randomly generated connected graph.

Game Objective
The aim of the game is to correctly guess the shortest path between two randomly generated nodes across five levels. Each level contains 12 randomly generated connected nodes. Players must enter their guess and submit it. Incorrect guesses result in a penalty, and exhausting all 10 guesses will send the player back a level. The challenge is to complete all levels in the shortest possible time.

Features
5 Levels of Difficulty: Each level presents a randomly generated graph of 12 nodes.
Timer and Attempts: Players must guess within 10 attempts; incorrect guesses add time penalties.
Graph Visualization: The graph is visually represented using a space theme, with nodes shown as stars.
Pathfinding Algorithm: Dijkstra’s algorithm is used to calculate the shortest path between nodes.
Win/Loss Conditions: Players win by completing all 5 levels and lose if they fail to guess the correct path on level one.

Installation
Clone the repository:
git clone https://github.com/yourusername/shortest-path-game.git
Navigate to the project directory:
cd shortest-path-game
Install dependencies:
Ensure you have the required libraries installed, including Swing and Graphstream for Java (or ensure they are included in your project configuration).
Run the game: Compile and run the Main class, which acts as the entry point for the game.

Gameplay
Start Screen:
The player is greeted with a space explorer-themed start page that includes instructions for the game.

Game Screen:
The player is presented with the current level, attempts remaining, and a timer. The graph is displayed with nodes and weighted edges. The player can enter their guess for the shortest path between two highlighted nodes in a text input box.

Incorrect Guesses:
Each incorrect guess adds 10 seconds to the timer. Players are given 10 attempts before being sent back one level.

Win/Loss Screens:
Win Screen: Displayed when the player successfully completes all 5 levels, showing their final score (time taken) and an option to restart or exit the game.
Lose Screen: Shown when the player runs out of attempts on level one, revealing the correct path and providing an option to exit the game.
