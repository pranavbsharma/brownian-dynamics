# Brownian Dynamics
brownianDynamics.m is an implementation of overdamped Langevin dynamics (an algorithm for stochastically evolving molecular systems in **implicit** solvent) for an arbitrary number of particles in a given N-dimensional space. 

Included are tools for calculating mean first-passage times of a pair of particles in this space, optionally while they are diffusing inside of a harmonic potential (**read:** spring-like attachment to a specific coordinate). Post-simulation analysis tools that are included: 1) if harmonic potential is ON, check that the particles obey the expected Boltzmann distribution during initialization and the simulation run, and 2) if harmonic potential is OFF, check that the mean square displacement of the particle ensemble obeys that predicted by the Stokes-Einstein relation.

**Developed for article:** Sensale, S., Sharma, P., & Arya, G. (2022). Binding kinetics of harmonically confined random walkers. Physical Review E, 105 (4), 044136.
