# A* Pathfinding in C

Recreation of my A* pathfinding algorithm except this time in C! Instead of a graphics interface this is meant to run on the command line and analyze a maze given by a .txt file. '#' characters are walls, 'O' characters are open, 'S' is the start and 'G' is the end. You can make any maze which is rectangular and this program will create a new file in the same directory called "nameSolution.txt". I included two test mazes named "maze.txt" and "sampleMaze2.txt".

How to run:
- open command line
- go to directory of executable (cd)
- Make sure the maze file is in the same directory as the executable
- type "c-pathfinding maze.txt" to run and analyze "maze.txt" file
- you may analyze any file by typing name of executable SPACE name of mazefile.txt (or directory + name)

Note: If you try to run executable without command line, it will close automatically because no file argument is given