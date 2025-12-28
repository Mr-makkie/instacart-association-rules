# instacart-association-rules
Scalable market basket analysis on large transactional data
# Scalable Market Basket Analysis on Instacart Data

## Overview
This project focuses on large-scale association rule mining using
the Instacart Market Basket dataset (3M+ grocery orders).

The main challenge was extracting meaningful patterns under memory
and runtime constraints.

## Dataset
- Instacart Market Basket Analysis
- 3M+ orders
- 50K+ products

Dataset is not included due to size and licensing constraints.

## Approach
- Built transaction-level data from normalized relational tables
- Applied frequency-based dimensionality reduction
- Evaluated Apriori vs FP-Growth algorithms
- Selected FP-Growth for scalability

## Key Engineering Decisions
- Apriori was infeasible at scale due to memory constraints
- FP-Growth significantly reduced runtime
- Lift was prioritized over confidence to avoid popularity bias

## Tools
Python, Pandas, MLxtend, Jupyter Notebook
