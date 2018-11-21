# simulated-annealing

# Report.
## Motivation
In this work we consider Simulated Annealing approach. It is an optimisation technique to find optimal value of non-convex function in a reasonable time, which doesn’t guarantee to find the best solution, but at least good one. 

## Findings
Algorithm was tested with three different values of cooling: 0.95, 0.98, 0.995 for fast, medium and slow cooling rates correspondingly. Dependence of function value from cooling rate and number of iterations is shown below:
![alt text](https://github.com/piaxar/simulated-annealing/blob/master/media/graphs.png)
Main observation is that increasing cooling rate, i.e. slowing down simulation, leads to finding better local minima, but takes considerably more iterations. Exact number of iterations for depicted simulations are listed in table below.  So the question of choosing between accuracy and performance should be considered when applying this method.

| Simulation     | Number of iterations |
|----------------|----------------------|
| Slow cooling   | 6891                 |
| Medium cooling | 1710                 |
| Fast cooling   | 674                  |

Regarding task of finding the best path, solution found by slow cooling is shown below. It is evident that better solution can be found, but it requires more iterations. 



References
Wikipedia, simulated annealing: https://en.wikipedia.org/wiki/Simulated_annealing

