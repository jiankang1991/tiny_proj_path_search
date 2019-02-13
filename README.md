# Optimal path search based on A/A* and dynamic programming

---

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

## A* search (with heuristic function)
By the guidance of predefined heuristic function, such as Euclidean distance to the goal, the optimal path search algorithm can be more efficient. Note the heuristic function $f$ should underestimate the actual cost to the goal, for function $f=0$ (without heuristic information), the A* search turns into the above search algorithm.



## Dynamic programming
Given the goal position, dynamic programming can provide the optimal costs for individual positions to the goal. It does not necessarily need the initialization point, starting from any point can lead to the goal position. 

$f(x,y)=\min_{x',y'}f(x',y')+1$, where $f(x',y')$ is the optimal neighbor and 1 is the update cost of each step.

