# TronBattle 

## Game Demo

- [my Game](https://www.codingame.com/replay/237997260)

### Overview

- LONGEST PATH FINDING ALGORITHM
- MINIMAX – CHOOSING THE BEST MOVE
- FLOODFILL - EVALUATION

### LONGEST PATH FINDING ALGORITHM

- This algorithum was implemented using graphs (Adjecancy List).
- Initial board state was parsed into graph and graph was updated on each move made by player.
- Based on the highest height value, the neighbor node was selected from the current node.

### MINIMAX – CHOOSING THE BEST MOVE

- Constructing all the possible states from the initial state and building the states till depth 3 for all 4 players.
- Terminal nodes are valued based on the flood fill algorithm

### Alpha beta Pruning 

- Improves the performance of minimax by pruning the unwanted nodes. 

### FLOOD FILL - EVALUATION

- After alternative BFS from each tron starting node this is how the flood fill looks like and eventually the overlapping cells will form a wall.

![flood-fill](https://github.com/mohanmb91/TronBattle/blob/master/floodfill.png)
