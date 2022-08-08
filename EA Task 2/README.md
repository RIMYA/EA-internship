# pacman
My own copy of a classic Pacman game made with the help of C++ and Qt Framework.
As in an original game the goal is to eat all white balls that are situated on the map.
The game includes for ghost, that are constantly chasing a player.
The player can eat energizers that makes the ghosts frightnened and they are running away in the different corners, it is called a frightened mode, but if one of the ghosts reachs their corner, they start chasing you again. In the frightened mode the player can eat ghosts and get some additional scores.
For the path search Lee algorithm (wave form search) was used.
Blinky (red ghost) : takes the location of the pacman and goes to it using the shortest path.
Pinky (pink ghost) : takes the location of the pacman, then its direction and as a destination point uses the cell that is on the four cells further from a pacman considering its direction.
Inky (blue ghost) : takes the position of a Blinky and two cells further due to the direction of a pacman, makes a vector, then doubles it and the final point is its destination.
Clyde (orange ghost) : it takes a pacman position as a destination point, but in the case if a distance between pacman and a Clyde is less than eight cells, if not he is staying in the down left corner;


