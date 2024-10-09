# CI2024_lab1
The code implements an optimization algorithm to solve the Set Cover Problem. 
  The algorithm performs a certain number of iterations, and in each iteration, it looks for the best improvement among 5 neighbors of the current solution. To generate a neighbor it tweaks a certain number of entries.  The number of changed elements decreases over time. 
  Additionally, another method was tested, which considers simulated annealing and small intermediate hill-climber improvements. However, those additions slow down the algorithm, so it does not perform well for the high-dimensional case (so the simplest version should be used).
