# stochastic-optim-electricity-grid

## Problem statement

In this project we consider the task of selecting power generators that minimize the total
cost of supplying enough electricity to satisfy regional demand, which is random.
To begin, suppose that we wish to select the optimal sizes of J = 4 different types of
generators: 1 gas fired, 2 coal fired, and 1 nuclear. The annualized capital cost (e/kwh) for
the acquisition of a generator of type $j = 1, ..., J$ is given by $c_j$ , while the cost of producing
a unit of energy (e/kwh) is given by $f_j$ . Note that while decisions regarding the generation
of electricity may be postponed until regional demand is known, decisions regarding the
acquisition of generation capacity (construction of the power plants) cannot be postponed.
Thus, we see a natural two-stage progression of the decisions being undertaken.

## Problem formulation

1. **_Two-stage SP model formulation_**: Formulate the power generation planning problem
   as a two-stage stochastic linear programming model.
2. **_Model implementation and solution_**: With the given dataset, solve your model employing either the Benders L-Shaped method or the Progressive Hedging algorithm. Report the purchased generation capacity and the total expected cost (investment +
   production).
3. **_Risk-averse formulation:_** Formulate the problem as a two-stage stochastic linear pro-
   gramming model with risk-averse measure CVaRα, instead of using the expected gen-
   eration cost, in the objective function.
4. **_Risk-averse model implementation and solution:_** With the given dataset, solve your
   risk-averse model with different confidence levels α employing the decomposition algo-
   rithm you developed in task 2.

## Data

_see notebook_
