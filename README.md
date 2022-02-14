# Implementation of search algorithms in Pacman

## About the project
This work aims to implement various search algorithms using the Berkely Pacman framework. Nowadays, the ability to implement an algorithm from a paper is essential to solve modern problems. It will help to improve the ability with contemporary techniques.

It relates to the tasks at https://inst.eecs.berkeley.edu/~cs188/fa18/project1.html.
To find other fun tasks, click the link.

<br>

## Implemented search algorithms
1. Enforced Hill Climbing algorithm (heuristic = Manhattan Distance)(part1) [1] <br>
  `def enforcedHillClimbing` in `SearchAgent.py`
  
2. Iterative Deepening A* algorithm (part2) [2]<br>
  `def idaStarSearch` in `SearchAgent.py`
  
3. Deceptive path-planning from a research paper [3]<br>
    (part3a) πd2 strategy <br>
      `class DeceptiveSearchAgentpi2` in `Search.py`<br>
    (part3b) πd3 strategy (α = 2) <br>
      `class DeceptiveSearchAgentpi3` in `Search.py`<br>

<!-- 
<br>

## How to run

For part1:<br>
`python pacman.py -l mediumMaze -p SearchAgent -a fn=ehc` 

For part2: <br>
`python pacman.py -l mediumMaze2 -p SearchAgent -a fn=ida`

For part3a:<br>
`python pacman.py --layout testDeceptive2 --pacman DeceptiveSearchAgentpid2`

For part3b:<br>
`python pacman.py --layout testDeceptive2 --pacman DeceptiveSearchAgentpid3`

-->
<br>
    
## References

[1] <a href="https://www.cs.cmu.edu/afs/cs/project/jair/pub/volume28/coles07a-html/node5.html#:~:text=EHC%20is%20based%20on%20the,present%20in%20the%20immediate%20neighbourhood">click</a>

[2] <a href="https://en.wikipedia.org/wiki/Iterative_deepening_A*">click</a>

[3] Masters, P., and Sardina, S. Deceptive path-planning. pp. 4368-4375.

----

This project is part of individual projects from COMP90054 AI Planning for Autonomy in School of Computing and Information Systems, The University of Melbourne. 


