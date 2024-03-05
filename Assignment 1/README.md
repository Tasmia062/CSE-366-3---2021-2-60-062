In this code :
1. PriotyQueue, Node, and Environment classes are unchanged

2. But, in the Agent class changes are made; to show the charging level and the position of battery recharge. Initially battery charge is 100. As the robot is moving forward to the goal, for every step charging level is decreased by 10. However, when the charging level is equal to 10 or less the robot recharges the battery and moves forward. This procedure is made in the battery_manager function.

3. To find the optimal solution path 2 algorithms : UCS and A* are used; here, the difference is in the A* search algorithm h(x) heuristic cost is added with the new cost. Also, in the heuristic function Manhattan distance is used (Euclidian distance can be used).

4. grid size is 10 X 10 and obstacle probability 20% .
