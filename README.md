# Truck-Cargo-Load-Problem-by-Genetic-Algorithm

This problem helps to load Cargo on Truck / Cargo-ships taking profit into account.It deals with loading minimum weight of load and maximizing profit.Code is within Cargo_load.cpp while Cargo_data.csv is given as test file.

# Genetic Algorithm

Genetic Algorithm (GA) is a search-based optimization technique based on the principles of Genetics and Natural Selection. It is frequently used to find optimal or near-optimal solutions to difficult problems which otherwise would take a lifetime to solve. It is frequently used to solve optimization problems, in research, and in machine learning

# The Algorithms

  - Randomly initialize population
  - Determine fitness of population
- Repeat
   - Select parents from population
   - Perform crossover on parents creating population
   - Perform mutation of population
   - Determine fitness of population
- Until best individual is good enough

# Randomizing Population

A population of individualsare is maintained within search space for a GA, each representing a possible solution to a given problem. Each individual is coded as a finite length vector of components, or variables, in terms of some alphabet, usually the binary alphabet {0,1}. To continue the genetic analogy these individuals are likened to chromosomes and the variables are analogous to genes. Thus a chromosome is composed of several genes. 

# Fitness Function

The fitness function simply defined is a function which takes a candidate solution to the problem as input and produces as output how “fit” our how “good” the solution is with respect to the problem in consideration.

# Parents Selection

Parent Selection is the process of selecting parents which mate and recombine to create off-springs for the next generation. Parent selection is very crucial to the convergence rate of the GA as good parents drive individuals to a better and fitter solutions.

# Crossover 

The crossover operator is analogous to reproduction and biological crossover. In this more than one parent is selected and one or more off-springs are produced using the genetic material of the parents

# Mutation

In simple terms, mutation may be defined as a small random tweak in the chromosome, to get a new solution. It is used to maintain and introduce diversity in the genetic population. Mutation is the part of the GA which is related to the “exploration” of the search space. It has been observed that mutation is essential to the convergence of the GA while crossover is not. 

# Survival Of Fittest

The Survivor Selection Policy determines which individuals are to be kicked out and which are to be kept in the next generation. It is crucial as it should ensure that the fitter individuals are not kicked out of the population, while at the same time diversity should be maintained in the population.

# System

This will work fine in linux.To use in windows make sure you import right header files for sleep function and make few changes.
