# NYU Computational Economics 2026

This repository contains lecture materials for Tom's NYU Computational Economics course, Spring Quarter 2026.

## Course Content

### Part I: Statistics, Information, and Asset Pricing

**Statistics and Information**

1. Statistical Divergence Measures
2. Likelihood Ratio Processes
3. Heterogeneous Beliefs and Financial Markets
4. Likelihood Processes For VAR Models
5. Mean of a Likelihood Ratio Process
6. A Problem that Stumped Milton Friedman
7. A Bayesian Formulation of Friedman and Wald's Problem
8. Exchangeability and Bayesian Updating
9. Likelihood Ratio Processes and Bayesian Learning
10. Incorrect Models
11. Bayesian versus Frequentist Decision Rules

**Asset Pricing and Finance**

12. Asset Pricing: Finite State Models
13. Competitive Equilibria with Arrow Securities
14. Heterogeneous Beliefs and Bubbles
15. Speculative Behavior with Bayesian Learning

### Part II: Overlapping Generations and Advanced Topics

16. Transitions in an Overlapping Generations Model
17. A Long-Lived, Heterogeneous Agent, Overlapping Generations Model
18. Information and Consumption Smoothing
19. Consumption Smoothing with Complete and Incomplete Markets
20. Tax Smoothing with Complete and Incomplete Markets
21. Recursive Models of Dynamic Linear Economies
22. Gorman Aggregation

## Building the Book

To build the Jupyter Book locally:

```bash
conda env create -f environment.yml
conda activate quantecon
cd lectures
jupyter-book build .
```

The HTML output will be in `lectures/_build/html/`.

## Source

These lectures are sourced from:
- [Intermediate Quantitative Economics with Python](https://python.quantecon.org/)
- [Advanced Quantitative Economics with Python](https://python-advanced.quantecon.org/)
