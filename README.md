# Travelling saleman with Ant Colony Optimization

This repository contains a simple implementation of the Ant Colony Optimization algorithm for the travelling salesman problem.
Our code is mainly a report on how the variation of hyper-parameter impact the performance of the algorithm and accuracy of the solution.


## Change-log

-2022/3/29 : Initial release, with no implementation, 4 files created
    - README.md
    - requirements.txt
    - TSP-ACO.py
    - TSP-ACO.ipynb


## Todo-list
1. Implement the algorithm
2. Add hyper-parameter pruning and configuration
3. Add statistical analysis of the results

## Data

The data used in this repository is the [TSP-ACO] dataset, which contains 48 cities in the United States. The data is stored in the `data` folder.


## Requirements

- Python 3.6
- Matplotlib 2.2.2
- Numpy 

## Usage
First, install the required package using pip:
    
```bash
pip install -r requirements.txt
```
To run the program, simply execute the following command:

```bash
python3 TSP-ACO.py
```

There is an iteractive version for this repository, where you can configure the code and hyper-parameter [TSP-ACO](TSP_nb.ipynb)


## Citation
[Ant Colony Optimization for the Traveling Salesman Problem](https://www.researchgate.net/publication/220568269_Ant_Colony_Optimization_for_the_Traveling_Salesman_Problem)
