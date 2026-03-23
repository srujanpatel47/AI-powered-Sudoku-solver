# AI-Powered Sudoku Solver

A hybrid Sudoku solver that combines machine learning with classical search algorithms to improve solving efficiency while preserving logical correctness.

## Overview

This project explores how learning-based predictions can work together with rule-based search to solve Sudoku puzzles more efficiently. Instead of relying only on a traditional solver or only on a neural model, the system uses machine learning as a heuristic layer to reduce search space and support faster solving.

## Problem

Sudoku can be solved with classical algorithms such as backtracking and constraint satisfaction, but difficult puzzles can become computationally expensive. Pure machine learning approaches can be fast, but they may fail to guarantee valid solutions.

## Solution

I built a hybrid approach that combines:
- machine learning-based prediction for missing values
- classical search algorithms for rule-based solving and validation

This design helps balance:
- speed from model-guided heuristics
- accuracy from constraint-based solving

## Algorithms Implemented

- Backtracking
- Constraint Satisfaction Problem (CSP)
- A* Search
- Dancing Links (DLX)

## Machine Learning Component

The project uses a learning-based model to predict missing values in Sudoku grids. These predictions are used to guide classical solvers by narrowing the solution space before search begins.

## Tech Stack

- Python
- TensorFlow
- NumPy
- Jupyter Notebook / Google Colab

## How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/srujanpatel47/AI-powered-Sudoku-solver.git
   cd AI-powered-Sudoku-solver

## Key Outcomes

- Built a hybrid ML + search system for Sudoku solving
- Reduced search space using model-guided predictions
- Improved solving performance across algorithms
- Focused on runtime, node reduction, and solver efficiency

## Repository Structure

- `sudoku-solver.ipynb` — main notebook containing the implementation and experiments
- `AI-project-report.pdf` — project report
- `AI-Project-Proposal.pdf` — initial project proposal

## Notes

The large raw dataset file is intentionally not included in this repository to keep the repo lightweight and easy to review.

## Future Improvements

- Upload a cleaner modular Python version beyond the notebook
- Add benchmark tables and example puzzle outputs
- Add visual comparison of solver performance
- Extend the learning model for stronger prediction quality

## Author

**Srujan Patel**  
GitHub: [srujanpatel47](https://github.com/srujanpatel47)  
LinkedIn: [srujan-patel-6674b6212](https://www.linkedin.com/in/srujan-patel-6674b6212/)