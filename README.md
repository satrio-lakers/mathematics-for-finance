# Mathematics for Finance — Implementation

## Overview
Python implementation of concepts from **Mathematics for Finance: 
An Introduction to Financial Engineering** by Marek Capiński 
and Tomasz Zastawniak (Springer, 2003).

This repository documents my journey learning quantitative 
finance mathematics, chapter by chapter, with practical 
Python implementations.

## Structure
- `chapter_1/` — Introduction: A Simple Market Model

## Chapter 1: Introduction
### Concepts Implemented
- Simple return calculation
- Log return calculation  
- No-arbitrage condition checker (Proposition 1.1)
- Portfolio value computation
- Currency arbitrage detection — graph traversal approach
- Expected return calculation — E(K)
- Standard deviation (risk) calculation — σ
- Risk-return tradeoff analysis

### Key Findings
- No-arbitrage condition: Sd < A(1) < Su
- If A(1) ≥ Su → short stock, buy bond → arbitrage
- If A(1) ≤ Sd → buy stock, short bond → arbitrage
- Simple return vs log return — when to use each

### Exercises Completed
- Exercise 1.1 — Portfolio value and return calculation
- Exercise 1.2 — Portfolio replication (V(0) = 1,020)
- Exercise 1.3 — Currency arbitrage detector (automated)
- Checks all 6 possible 3-currency paths automatically
- Arbitrage found: USD→GBP→EUR→USD (+0.59% profit)
- Confirms: if one direction profits, opposite direction always loses
- Exercise 1.4 — Risk and return for 50-50 portfolio
  - Expected return: 12.5%
  - Standard deviation: 10%
  - Return range: 2.5% to 22.5%

## Tech Stack
- Python 3
- math, jupyter notebook

## Reference
Capiński, M. & Zastawniak, T. (2003). 
*Mathematics for Finance: An Introduction to Financial Engineering*. 
Springer.

## Author
Aril Satrio Saputro
Data Science Student | Universitas Airlangga
GitHub: github.com/satrio-lakers
