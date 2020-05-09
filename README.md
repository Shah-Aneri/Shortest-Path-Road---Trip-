# Shortest-Path-Road---Trip-


➔ This problem has been solved using DFS implemented using Priority Queue.

➔ To solve this problem, we started with the DFS algorithm to calculate the distances between the cities provided as input. 
However, the time taken was much greater and was unable to provide a solution at times within the timeframe. Next, we 
implemented it using BFS which provided a faster and optimal solution. We then came up with an idea to implement DFS
using Priority Queue which turned out to be much faster and optimal similar to the BFS. We tried using heuristics like
Manhattan and Euclidean distance but they did not provide the optimal solution, so we did not use any heuristic in the final code.

➔ The search abstractions for this problem are stated below:

◆ State Space: All possible cities mentioned in the dataset.

◆ Successor Function: Any city which plays an intermediate to reach our destination or the destination itself.

◆ Cost: As defined by the input(segments, distance, time or mpg)

◆ Goal state: the destination city with the required cost function



Done by: Aneri Shah, Dhruva Bhavsar, Hely Modi
