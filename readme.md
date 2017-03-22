# Introduction to Mathematical Programming

Linear, quadratic, MIP, non convex... maybe. Basic introduction to applied combinatorial optimization and some cool business problems.

Charles (Chris) Ochoa

## Sections

### Linear Programming

#### a. [Linear Programming Intro](http://nbviewer.jupyter.org/github/cochoa0x1/intro-mathematical-programming/blob/master/linear_programming/Linear%20Programming.ipynb)
The basics of modeling and solving linear programs with python PuLP.

#### b. [Network Flows](http://nbviewer.jupyter.org/github/cochoa0x1/intro-mathematical-programming/blob/master/linear_programming/factory_routing_problem.ipynb)
simple network flow done with pulp and networkx

#### c. [Traveling Salesman Problem](http://nbviewer.jupyter.org/github/cochoa0x1/intro-mathematical-programming/blob/master/linear_programming/traveling_salesman.ipynb)
Classic traveling salesman solved as an integer program

#### d. [Multiple Salesman and Vehicle Routing](http://nbviewer.jupyter.org/github/cochoa0x1/intro-mathematical-programming/blob/master/linear_programming/traveling_salesman2_vehicle_routing.ipynb)
Simple generalization of the traveling salesman

#### e. [Knapsack Problem](http://nbviewer.jupyter.org/github/cochoa0x1/intro-mathematical-programming/blob/master/linear_programming/knapsack_problem.ipynb)
Classic 0-1 Knapsack problem solved as an integer program


#### f. [Bin Packing](http://nbviewer.jupyter.org/github/cochoa0x1/intro-mathematical-programming/blob/master/linear_programming/bin_packing.ipynb)
Minimize the number of bins needed to pack items

#### g. [Logical Operations](http://nbviewer.jupyter.org/github/cochoa0x1/intro-mathematical-programming/blob/master/linear_programming/logical_operations.ipynb)
Model compex non-linear constraints and objectives via clever uses of binary variables.

## Setup
create a virtual environment

```
$ conda create --name math-prog python=3
```

activate it

```
$ source activate math-prog
```

install [PuLP](https://pythonhosted.org/PuLP/)

```
$ pip install pulp
```

### optional for now, 

install network x

```
$ pip install networkx
```

install the GNU Linear Programming Kit [GLPK](https://www.gnu.org/software/glpk/):

linux:

```
$ sudo apt-get install python-glpk sudo apt-get install glpk-utils
```

osx (via homebrew):

```
$ brew install glpk
```

windows: sorry :( 



