# Pricing Competition Simulation

This repository contains [Jupyter notebooks](https://jupyter.org) for a simulation of pricing competition.
The goal of this repository is to provide a small simulation framework that allows to (i) simulate various pricing scenarios, (ii) collect the data of these scenarios, and (iii) learn the demand using various machine learning techniques.

Our aims is less on an end-to-end evaluation of demand learning techniques. Hence, we do not make any claims about the superiority of any technique. Our focus is to provide a framework for research on demand learning that allows users to evaluate how certain techniques can be applied to the challenge of demand learning on online market places.

## Jupyter Notebooks:
 * **demand_learning.ipynb**: this notebook reads the market data created before and trains various models in order to predict demand.
 * **market_simulation.ipynb**: this notebook creates three output files. For a given number of market situations, each market situation is simulated with the same starting conditions multiple times for a given time horizon.
 * **monte_carlo.ipynb**: this notebook creates two files. For a number of market situations and a set of prices, it creates features. Then for each market situation and each price it runs multiple simulations and tracks the purchases. For one price it also splits up the time between price adjustments.

## Miscellaneous

This project is part of our research on dynamic pricing at the [EPIC chair of the Hasso Plattner Institute](http://epic.hpi.de).
In case you have any questions or comments, feel free to contact Rainer Schlosser or Martin Boissier.

**Contributors:**
 * Rainer Schlosser (Fax: +49 (331) 5509-579)
 * Martin Boissier (@Bouncner)
 * Tom Schwarzburg (@tomschw)
