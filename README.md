# SIS-Model-for-Infectious-Diseases
The SIS model (Susceptible-Infected-Susceptible model) is a mathematical model used to describe the spread of infectious diseases in a population
It assumes that individuals can either be susceptible (able to be infected) or infected (contagious and able to spread the disease), but that they can also recover and become susceptible again.

In the SIS model, the spread of the disease is represented by two differential equations: one for the number of susceptible individuals and one for the number of infected individuals. These equations describe how the number of susceptible and infected individuals changes over time, based on the transmission rate (the probability of an infection being transmitted from an infected individual to a susceptible individual in a single time step) and the recovery rate (the probability of an infected individual recovering in a single time step).

By solving these differential equations, we can track the evolution of the infection in the population and predict how it may spread. The SIS model can be used to study the effectiveness of different public health interventions, such as vaccination programs or quarantine measures, in controlling the spread of infectious diseases.


Library: A library is a collection of pre-written code that we can use in our own programs. In this case, we are using the deSolve library to help us solve the differential equations that describe the spread of the infection.

Initial number of susceptible and infected individuals: The initial number of susceptible and infected individuals represents the starting point for our model. In this case, we have set the initial number of susceptible individuals to 10000 - 192 = 9808, and the initial number of infected individuals to 192.

Transmission rate: The transmission rate represents the probability of an infection being transmitted from an infected individual to a susceptible individual in a single time step. In this case, we have set the transmission rate to 0.5.

Recovery rate: The recovery rate represents the probability of an infected individual recovering in a single time step. In this case, we have set the recovery rate to 0.1.

Total population size: The total population size represents the total number of individuals in the population. In this case, we have set the total population size to 10000.

Derivative function: The derivative function computes the rate of change of the number of susceptible and infected individuals at a given time. It uses the transmission rate, recovery rate, and total population size to determine how the infection spreads.

Times: The times represent the points in time at which we want to compute the solution for our model. In this case, we are computing the solution at intervals of 0.1 time units from time 0 to time 5.

Initial state and parameter values: The initial state represents the initial number of susceptible and infected individuals, and the parameter values represent the transmission rate, recovery rate, and total population size.

ODE function: The ode function stands for "ordinary differential equation", and it is a mathematical tool that helps us solve differential equations. In this case, we are using the ode function to solve the differential equations that describe the spread of the infection.

Plot function: The plot function creates a graph of the results of our model. It shows how the number of susceptible and infected individuals changes over time.


