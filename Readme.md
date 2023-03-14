## Description
- Check the feasibility of all inputs/outputs (if user gives start and goal nodes that are in the obstacle
space they should be informed by a message and they should try again).
- Implement Dijkstra’s Algorithm to find a path between start and end point on a given map for a
point robot (radius = 0; clearance = 5 mm).
- The code outputs an animation of optimal path generation between start and goal point on
the map. It shows both the node exploration as well as the optimal path generated.

## Running Instructions 
```
git clone git@github.com:nvnmangla/Dijkstra.git
cd Dijkstra/
python3 solution.py

```

## Results 
The results are generated with 

Start - (10,10)

End - (200,150) 
<p align="center">
  <img width="230" src="https://github.com/nvnmangla/Dijkstra/blob/8af297daae174352b766e6e3627a4ba3474e7703/project.gif">
</p>
