# Dijkstra-Algo
Dijkstra's Algorithm is a graph search algorithm used to find the shortest path from a single source node to all other nodes in a weighted graph. 
It works like--
1.Initialization:
•	Create a distance array that stores the shortest distance from the source node to every other node. Initialize the distance of the source node to 0 and the distance of all other nodes to infinity.
•	Create a priority queue (min-heap) to keep track of nodes with the minimum distance. Initialize it with the source node and its distance.
2.Main Loop:
While the priority queue is not empty:
•	Dequeue the node with the smallest distance from the priority queue.
•	For each neighbour of the dequeued node:
•	Calculate the tentative distance from the source node to the neighbour through the current node.
•	If the tentative distance is less than the recorded distance for the neighbour, update the distance and enqueue the neighbour into the priority queue.
3.Termination:
The algorithm terminates when the priority queue is empty, meaning all nodes have been visited and their shortest distances have been determined.
4.Result:
After the algorithm completes, the distance array will contain the shortest distances from the source node to all other nodes.
