# Vertex Cover Approximation: Greedy vs Monte Carlo

This project implements and compares two approximation algorithms for solving the **Vertex Cover Problem** in graph theory:
- **Greedy Algorithm**: Selects vertices with the highest degree first
- **Monte Carlo Algorithm**: Picks a random edge and includes both endpoints

## 📊 Problem Statement
The Vertex Cover Problem is NP-Hard. Approximation algorithms are used to find near-optimal solutions efficiently for large graphs.

## 🔧 Technologies Used
- Python
- NetworkX
- NumPy
- Matplotlib

## 🧠 What This Notebook Covers
- Generates connected undirected graphs with varying sizes and densities
- Implements both Greedy and Monte Carlo approximations
- Measures and compares:
  - Size of the resulting vertex cover
  - Runtime performance
  - Scalability across different graph sizes

## 📁 Experiment Setup
- Node sizes: 100, 500, 1000, 5000
- Average degrees: 2, 4, 8
- Evaluation based on execution time and cover size

## 📎 Applications
- Network design
- Bioinformatics
- Resource allocation
- Approximation algorithm benchmarking

## 🚀 How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Install dependencies:
   ```python
   !pip install networkx matplotlib
