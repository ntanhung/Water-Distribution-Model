# Water-Distribution-Model
A Mathematical Model Used to Estimate The Optimal Allocation of Water.
The paper is our attempt at Problem B of the mathematical modeling contest MCM/ICM in 2022. 
## Abstract
We create a water and electricity allocation model to optimize the use of scarce water in the Colorado River for five states: Arizona, California, Colorado, New Mexico, and Wyoming. The model optimizes the water allocation for each state and remaining water levels in the reservoirs by maximizing the resource demand-fulfilling rates of each state. Considering power generation processes for the two hydroelectric power plants along the river, the Glen Canyon Dam and the Hoover Dam, we maximize the electricity demand fulfilling rate by optimizing water allocation. The water and electricity allocations depend on two important groups of variables. The first group of variables are the water supply to five different states, while the second group of variables are the water flow out of two dams respectively. In addition, the allocation of water to one of the three usages - residential, industrial, and agricultural purposes - will be determined by our defined constants. 

The model takes the form of a non-linear optimization problem, as we introduce the objective function that captures the water and energy demands of all states, with the goal of finding the optimal resource allocation while maintaining the sustainability of the water level. This system is solved using the constrained optimization by linear approximation method (COBYLA).

Using the model, we predict that without precipitation and with optimal resource distribution, the Colorado River will support 70\% of the demands of all stakeholders for approximately 490 days. 

By applying the model to different time constraints, we find that the optimized results for a shorter period (45 days) would lead to full fulfillment rates for water supply and electricity. For longer periods (90, 180, 360 days), our model suggests that the water supply should first go to lower basin states instead of upper basin states due to an additional utility brought by the additional electricity generation. 
