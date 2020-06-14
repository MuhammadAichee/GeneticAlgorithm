# Probem Statement
In this assignment you will design and implement a simple genetic algorithm and explore its
performance in evolving solution to one numerical problem, investigating the effect that various
parameters have on its performance.
1. Design and implement a simple genetic algorithm, in a language of your choice, to work on
binary strings, and show its performance on the Max-1s problem where the aim is to get a
chromosome of all 1s. Use an 8-bit chromosome and, when calculating the fitness, map the
binary number onto an integer first; so the maximum fitness for an 8-bit chromosome is 255
which is the ideal case to reach.
2. Explore the performance of the algorithm as a function of population size and number of
generations. Min and max number of population size to explore performance can be of your
choice for e.g. min 4 and max 10.
3. Then increase the chromosome length and investigate/explore performance as a function of this
length.

By explore I mean you need to create a report in which graphs should be drawn to show how
performance has varied with respect to population size, number of generations and chromosome length
separately.
Bear in mind that you will be using random number generators and that, to get a representative
performance and results that are statistically significant, you will need to run each experiment several
times.

How to Run:
  1) Clone the project.
  2) Run command "pipenv install"
  3) Run command "pipenv shell"
  4) Run command "python main.py"
