# Competing Bandits in Matching Markets — Reproduction and Extensions

### Semester Project — Swiss Joint Master in Computer Science

This repository contains the code, report, and presentation for a semester project completed in the seminar **Trustworthy AI Models and Systems** at the **University of Neuchâtel**, within the **Swiss Joint Master in Computer Science**.

The project reproduces and extends the results of the paper:

> Liu, L. T., Mania, H., & Jordan, M. (2020). *Competing Bandits in Matching Markets*.

---

## Project Overview

This project studies learning dynamics in matching markets through a reproduction and extension of the original paper.

We implement centralized multi-armed bandit algorithms and evaluate their performance in matching environments. The work focuses on understanding regret behavior, convergence, and the impact of different market structures.

---

## Main Contributions

- Implementation of centralized **ETC (Explore-Then-Commit)** and **UCB (Upper Confidence Bound)** algorithms  
- Reproduction of key experimental results from the original paper  
- Analysis of regret in matching market settings  
- Extension using alternative evaluation metrics (e.g., optimal matching regret)  
- Experiments on randomized and more complex market scenarios  
- Exploration of a two-sided learning setting  

---

## Repository Contents

- `matching-markets.ipynb` — implementation and experimental analysis  
- `report.pdf` — full report with methodology, results, and discussion  
- `presentation.pdf` — presentation slides  

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/allizha/matching-markets-extension-study.git
