# rmodel

UI for an R-like experience of simple statistical modelling, but in Python.

# installation

````{bash}
pip3 install rmodel
````
or git-clone it.

# example

Install 
````{python}
from rmodel.polyfit import polyfit

P = polyfit(x=[1,2,3,4], y=[1.2, 3.5, 4.4, 5.5], deg=2)
P.plot()
````
