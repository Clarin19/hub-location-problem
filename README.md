# hub-location-problem
Metaheuristics applied to solve Hub Location Problem

Overview:

An uncapacitated single allocation p-hub location problem constructed in Python programming language and tested on CAB, TR and RGP for varying nodes.
Metahueristics, namely Simulated Annealing and a variant of Variable Neighbourhood Search, Variable Neighbourhood Descent (VND) is leveraged to suggest optimal hub locations for the optimisation problem.

Objective Function:

To select optimal hub location thereby minimising the total transportation cost

Assumptions:

• The number of hubs to be open is predetermined

• A link is assumed to be present between every hub pair

• There is economies of scale for using Inter-Hub connections

• There is no direct path between spoke nodes

• The transportation cost and flow demand between the nodes are constant and known in advance

• The hubs have unlimited capacity and there is no limit for the number of spoke nodes that can be assigned to a particular hub

• The transportation cost to be minimised as part of the objective function is assumed to be linearly dependent on the distance between the nodes
