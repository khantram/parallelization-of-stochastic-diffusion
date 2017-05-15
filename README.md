## CSCI 373.002 - Final Project (continued work)
### Parallelizing Stochastic Diffusion using MPI

@Nathan Breedlove, Eliot Dixon, Kenny Tram

######## Notes
- spacial_stoch.c - Serial Implementation
- MPI_spacial_stoch.c - Parallel Implementation
- Notable animations of stochastic diffusion (generated in serial) included

######## To-do List
- Kill signals to assure that all processors "finish" when appropriate
- combine_output.c - A program to combine the output of each processor; synchronized by time
