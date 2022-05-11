# pacman-project-AI-final-project
This is group 2's code for our final project in CSE-6633/4633 Artificial Intelligence.
To run this project in the way intended for our project, follow these steps:
download zip file
extract contents
open command line (bash)
navigate to the folder with the .py files
type the following commands into the terminal:

  python pacman.py -l openMaze -p SearchAgent -a fn=dfs

  python pacman.py -l openMaze -p SearchAgent -a fn=bfs

  python pacman.py -l openMaze -p SearchAgent -a fn=ucs

  python pacman.py -l openMaze -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic

  python pacman.py -l openMaze -p ClosestDotSearchAgent
  
after each of these commands the game will run by itself and show the results of the game in the terminal once the game has finished
additionally, you can run the following command:

python pacman.py -p ClosestDotSearchAgent

to run the more classic pacman game with a custom layout. This uses greedy search (called ClosestDotSearchAgent here) to find and eat all the dots.
It has a success rate of about ~15%.
