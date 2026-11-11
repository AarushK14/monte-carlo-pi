# Monte Carlo Estimation of Pi
Project outline: Estimated π using Monte Carlo simulation in Python by randomly placing points in a unit square and counting how many fall inside a quarter circle. Analysed how the average error changes as the number of points increases, using a log-log plot. Built on an iPad as part of teaching myself Python for quantitative finance.

A Python project that estimates π using random sampling (the Monte Carlo method).

## How it works
1. Generate n random points (x, y) with x and y between 0 and 1.
2. Count how many points land inside the quarter circle x² + y² ≤ 1.
3. The fraction of points inside approximates π/4, so π ≈ 4 × (points inside / n).

## What I investigated
- How the estimate changes as n increases
- How the average error behaves as n grows, shown on a log-log plot

## Built with
- Python
- NumPy / Matplotlib

## What I learned
- The Monte Carlo method and why more samples give better estimates
- That the error shrinks slowly as n grows (roughly 1/√n), which is why efficiency matters in simulations
- How to plot and interpret results on a log-log scale

## Next steps
- Simulating random-walk stock prices

## Author
Built by Aarush Kotwal while learning Python alongside A-level Further Maths, with an interest in quantitative finance.
