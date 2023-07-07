# Bivariate Clustering and Regression using MILP
> *This is a project for Combinatorial Optimization and Network Analysis course (1254083) at Amirkabir University of Technology.*


## This project implements the following paper:

**A unified framework for bivariate clustering and regression problems via mixed-integer linear programming**  
*(John Alasdair Warwicker, Steffen Rebennack)*  
*March 2023*  
[https://doi.org/10.1016/j.dam.2023.03.010](https://doi.org/10.1016/j.dam.2023.03.010)

### Data
[`DebrisFlow.txt`](./data/DebrisFlow.txt)[1][2] is one of the datasets provided in the paper which is used in this implementation to test model outputs.

---

### Dependencies
This project requires `pyomo` which you can install using **one of** the following commands:
```bash
$ conda install -c conda-forge pyomo
$ pip install pyomo
```

### References
[1] [V. Krasko, S. Rebennack, Two-stage stochastic mixed-integer nonlinear programming model for post-wildfire debris flow hazard management: Mitigation and emergency evacuation, European J. Oper. Res. 263 (1) (2017) 265–282.](http://dx.doi.org/10.1016/j.ejor.2017.05.004)

[2] [K. McCoy, V. Krasko, P. Santi, D. Kaffine, S. Rebennack, Minimizing economic impacts from post-fire debris flows in the western United States, Nat. Hazards 83 (1) (2016) 149–176.](https://link.springer.com/article/10.1007/s11069-016-2306-0)