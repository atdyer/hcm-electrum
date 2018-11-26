# Electrum Models for Moment Distribution

This repository contains Electrum models of the Hardy Cross method of moment distribution. Things we'd like to model:

- [x] [Topology and progression through time](hcm.ele)
- [x] [Deadlock](hcm-deadlock.ele) - The only way for the model to deadlock is if the solution has converged
- [x] [Safety](hcm-safety.ele) - If allowed to run forever, the model will never deadlock
- [ ] [Convergence](hcm-convergence.ele) - a model will always converge on a solution
- [ ] Refinement - Various implementation techniques are refinements of our basic model