# Introduction to Mathematical Programming

An introduction to (mostly) linear programming and combinatorial optimization problems in python.

Charles (Chris) Ochoa

currently a work in progress

## Who is this book for?

This book is for someone who already knows python, is not afraid of basic math (mostly math as a written language), and has the need to solve combinatorial problems. The book will cover linear programs both continuous and integer and some theory on the algorithms that solve these. It will also cover the PuLP open source linear modeling library, some convex optimization, and lots of case studies and examples along with discussions about improving performance. Also maybe some combinatorial game theory if I ever get the time and quadratic programming.



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



