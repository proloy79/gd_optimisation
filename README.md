# Gradient Descent In Depth

## Overview

This project explores the behavior of several optimization algorithms — Gradient Descent (GD), Backtracking GD, Stochastic Gradient Descent (SGD const and decaying)— on a 1D objective function. It is divided onto 2 notebooks : gradient_descent_in_depth and gradient_descent_summary_and_experiments. 

It visualizes:
- Optimization trajectories
- Distance of iterates from the minimizer
- Final suboptimality as a function of step size
The goal is to build intuition about stability, convergence speed, and noise under different hyperparameters.

## Features
- Plot full optimization trajectories (x_k,f(x_k))
- Plot distance  over iterations
- Compare final gaps  across step sizes
- Support for multiple starting points x_0
- Clean, reproducible plotting utilities
- Optional PDF export for all figures

## Visualizations
1. Trajectories
	Shows how each method moves through the landscape.
	Useful for spotting overshooting, oscillation, or slow contraction.
2. Distance from Minimum
	Plots  to isolate convergence behavior independent of the function shape.
3. Final Gap vs Step Size
	Bar chart comparing

across step sizes and starting points.

## Usage
Run all experiments in the order listed in the index.

## Installation
pip install -r requirements.txt
