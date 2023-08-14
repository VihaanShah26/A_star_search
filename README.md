# A* Search

## Goal 
Use A* search to find the minimum number of actions required to solve a given sliding tile puzzle.

<img width="454" alt="image" src="https://github.com/VihaanShah26/A_star_search/assets/79374408/d20e00fa-35fe-49fc-908f-18617e517bca">


## Program 
The sliding tile puzzle is provided as a 9 element list. It is populated by numbers 0-8 where the number 0 represents the blank tile and numbers 1-8 represent the numbers itself. The indices of the list span the board from left to right and then top to bottom i.e. the list in the goal state would be [1,2,3,4,5,6,7,8,0]. 

<img width="173" alt="image" src="https://github.com/VihaanShah26/A_star_search/assets/79374408/d815aeb6-6199-4b36-ab6a-21cf2d1a737e">

Possible actions for moving the blank tile: 

0 - Up 

1 - Right 

2 - Down 

3 - Left 

The sum of Manhattan Distances for all the tiles from its current position to its goal position is used as the heuristic. 
