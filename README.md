# Genetic-Algorithm-Swarm
To study and understand Genetic Algorithm and its applications .
We will use GA for finding the best path for a mobile robot in a 2D environment.  
We will simulate steps to  move from starting point to the endpoint while avoiding collisions with obstacles and minimizing total distance travelled.
We will attempt to understand how and where the concepts of Maze Solving using GA can be implemented to solve real world problems.

The choice of genetic operators is a crucial step for the convergence of the genetic algorithm.Thus we tried to improve the classic crossover operator. 
In our approach we propose an improved crossover operator that uses parents with good fitness to increase the quality of progeny as well as parents with low fitness value to explore the research space and ensure diversity among the population.
This operator also takes into account variable length chromosomes.
The population has a fixed size. As new generations are formed, individuals with least fitness die, providing space for new offspring.
The sequence of phases is repeated to produce individuals in each new generation which are better than the previous generation.

Crossover rate should be 80%-95% 
 Mutation rate should be low i.e. 0.5%-1% assumed as best 
 The method of selection should be appropriate 
Writing of fitness function must be accurate
They cannot always find the exact solution but they always find the best solution.

