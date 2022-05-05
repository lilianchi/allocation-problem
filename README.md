### allocation-problem
Brown furniture makes three products. The resources required are skilled fabrication labor, unskilled assembly labor, machining, and
wood. The following resource availabilities, requirements and unit profits are known.


|  Requirements per unit | Chairs     | Desks   | Tables | Resources available  |
| :------------          |   :---:    | -------:|-------:| -------:|
| `Fabrication (hr)`    | 4      | 6      |   2     | 2000 hr |
| `Assembly (hr) `      | 3      | 8      |   6     | 2000 hr |
| `Machining (hr)`      | 9      | 6      |   4     | 1440 hr |
| `Wood (sq. ft) `      | 30     | 40     |   25    | 9600 sq. ft |
| `Profit per Unit `    | $16    | $20    |   $14   |    |

How much of what to produce?

### Programming language
Python

### Authors
* Mohit Tawarmalani
* Li-Ci Chuang

### Packages Used
import gurobipy as gp
from gurobipy import Model, GRB
import pandas as pd
from collections import OrderedDict
import matplotlib.pyplot as plt
