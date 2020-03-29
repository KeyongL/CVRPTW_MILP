# MVRP-Gurobi
This code is written in Python-Gurobi API interface.
This is a capacitated multiple vehicle routing problem.
This code also has time windows constraint.
We can levitate the time windows constraint if only solving the capacitated problem.
Or we can levitate the capacity constraint if only dealing with time windows with unlimited vehicle capacity.
Either of those constraints are capable of eliminating subtours.

The CSV file has (x,y) coordinates of depot and customer nodes.
