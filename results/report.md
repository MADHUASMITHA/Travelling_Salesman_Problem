# TSP: SA vs GA — Comparison Report

This report compares Simulated Annealing (SA) and a Genetic Algorithm (GA) on the provided city instances.

## Results table

|   Cities |   SA Best |   SA Avg |   SA Std |   SA Time_Avg |   GA Best |   GA Avg |       GA Std |   GA Time_Avg |
|---------:|----------:|---------:|---------:|--------------:|----------:|---------:|-------------:|--------------:|
|       10 |   290.307 |  290.307 |   0      |     0.0108485 |   290.307 |  290.307 |  4.64125e-14 |      0.102874 |
|       20 |   386.43  |  414.086 |  38.9721 |     0.0178209 |   458.465 |  468.94  | 11.7787      |      0.168514 |
|       30 |   510.844 |  532.012 |  16.9178 |     0.0240242 |   719.378 |  747.383 | 37.9784      |      0.238479 |
|       40 |   618.993 |  667.3   |  40.62   |     0.0316024 |   796.143 |  888.285 | 83.4913      |      0.313543 |
|       50 |   821.054 |  858.678 |  36.8549 |     0.03882   |  1125.23  | 1213.47  | 69.7518      |      0.396835 |

## Notes

- Stage 1 (single-solution) algorithm chosen: **Simulated Annealing (SA)**.
- Stage 2 (population) algorithm chosen: **Genetic Algorithm (GA)**.
- Parameters were selected for a balanced trade-off between speed and solution quality for a 50-city dataset.
- Figures saved in `figures/` show solution quality and runtime scaling.
