# CI2024_lab1
The code implements an optimization algorithm to solve the Set Cover Problem. <br>
  The algorithm performs a certain number of iterations, and in each iteration, it looks for the best improvement among 5 neighbors of the current solution. To generate a neighbor it tweaks a certain number of entries.  The number of changed elements decreases over time. <br>
  Additionally, another method was tested, which considers simulated annealing and small intermediate hill-climber improvements. However, those additions slow down the algorithm, so it does not perform well for the high-dimensional case (so the simplest version should be used in this case).

  <br>
  <br>
Ideas are taken from lectures, discussions with my classmate Gabriele Pirilli (https://github.com/Gpir0) and his help. 

<br>
<br>
<br>
RESULTS: 

1)
UNIVERSE_SIZE = 100 <br>
NUM_SETS = 10 <br>
DENSITY = 0.2 <br>
Solution cost: 286.43775977201597 <br>
Computation time: 0.12 seconds <br>

2)
UNIVERSE_SIZE = 1_000 <br>
NUM_SETS = 100 <br>
DENSITY = 0.2 <br>
Solution cost: 6347.784660663539 <br>
Computation time: 0.39 seconds <br>

3)
UNIVERSE_SIZE = 10_000 <br>
NUM_SETS = 1_000 <br>
DENSITY = 0.2 <br>
Solution cost: 131592.85612894854 <br>
Computation time: 2.23 seconds <br>

4)
UNIVERSE_SIZE = 100_000 <br>
NUM_SETS = 10_000 <br>
DENSITY = 0.1 <br>
Solution cost: 2009895.2513356414 <br>
Computation time: 41.54 seconds <br>

5)
UNIVERSE_SIZE = 100_000 <br>
NUM_SETS = 10_000 <br>
DENSITY = 0.2 <br>
Solution cost: 2319998.564787915 <br>
Computation time: 41.41 seconds <br>

6)
UNIVERSE_SIZE = 100_000 <br>
NUM_SETS = 10_000 <br>
DENSITY = 0.3 <br>
Solution cost: 2610023.2840255746 <br>
Computation time: 57.14 seconds
