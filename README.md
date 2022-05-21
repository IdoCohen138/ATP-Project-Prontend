# Maze-Game-Prontend
> This part contains the GUI of Game in JavaFX.


## project structure
> in src/main java folder you can find all the directory of the project.

#### client
This folder contains the Client side.

#### IO
This folder contains two types of comppresion simple and My compressor.

#### Server
This file contains the Server side.
* ServerStrategyGenerateMaze - The server receives from the client an [] int array of size 2 only when the first holds the number of rows in the maze, the second the number of columns. 
The server generates a maze according to the parameters, compresses it using MyCompressorOutputStream and sends it back to the client [] by displaying the requested one.
* ServerStrategySolveSearchProblem - The server receives from the client a Maze object that displays a maze. Solves it and returns to the customer a solution that holds the solution of the maze.

#### algoritham
This file contains the algoritham to build and solved the maze.
  
#### test

you can find the test to this part, whice check build the maze(empty, simple, myMaze) and solved it.
* empty: build empty maze.
* Simple: build randomly maze with randomly walls.
* myMaze: build the maze with "Randomized depth-first search" algoritham.
