# DISEASE-SPREAD-MODEL
A simulation will model disease spread in a population. At the start, individuals have a 10%-90% chance of being susceptible, while non-susceptible ones have a 20%-50% chance of becoming infectious. The simulation begins with a mix of susceptible, infectious, and immune individuals, using a probabilistic transmission model.

Description

This project simulates the spread of a disease among individuals using a probabilistic approach. The simulation models infection dynamics where individuals can be categorized as susceptible, infectious, or immune. The spread follows the von Neumann neighborhood (N, W, S, E).

Features

Simulates disease spread using different probabilities for susceptibility (10% - 90%) and infectiousness (20% - 50%).

Uses a cellular automaton model for disease propagation.

Visualizes the infection spread process over time.

Computes the overall effect of different probability values on disease transmission.

Model and Assumptions

Assumptions

The population is represented as a 25×25 grid.

Disease spreads only through the von Neumann neighborhood (N, W, S, E).

The simulation starts with a mix of susceptible, infectious, and immune individuals.

There are no births, deaths, or movement of individuals.

The infectious state transitions to immune after a set duration.

The simulation runs for 50 timesteps.

Absorbing boundary conditions are applied.

Disease Spread Model

Each individual has a probability (probSusceptible) of being susceptible at the start and a probability (probInfectious) of becoming infectious if not initially susceptible. The simulation iterates over the grid, updating individual statuses based on neighboring conditions and probabilistic infection chances.

Results and Conclusion

Simulation Results

After running the program, the simulation outputs matrices representing the spread of disease for different probability values.

Conclusion

The results indicate patterns in disease spread. When probSusceptible is high compared to probInfectious, the disease may eventually die out. Otherwise, the infection continues spreading indefinitely. The probabilistic model can sometimes exhibit deterministic-looking patterns, highlighting the dynamic nature of disease transmission.

Contributors

Fadhlannafis Khawarizmi K.	

Gema Nadiku P.			

Muhammad Ariq Fakhri		

Ghaisan Zaki Pratama

M. Arif Wibisono	
