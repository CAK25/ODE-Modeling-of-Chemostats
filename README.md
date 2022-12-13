# ODE Modeling of Chemostats
 Bifurcation analysis on chemostat models, modeling two ordinary differential equations on a plot, and sensitivity analysis by varying different paremters within the model.

The two (2) ODEs given in the research paper were plotted.


The steady state values of x and s were found using fsolve method and the Phase Portrait of the differential equations were plotted.


A bifurcation anaylsis with a constant s value of 0.8 mM (initial condition from the paper) and ten different values of umax ranging in even increments from 0.1 to 1 was plotted.


Hysterises effects of s (nutrient concentration mM) and x (cell density cells/mL) with different values of umax (-2,-1, 0, 1, and 2) were plotted against time (hours).

A sensitivity analysis was performed for both s (nutrient concentration mM) and x (cell density cells/mL).
First, umax was increased from 5%, 10%, and then 15% and both s (nutrient concentration mM) and x (cell density cells/mL) were plotted to see how changing the umax paramter affects s and x.
The steady state values for x and s were calculated for each case.

Second, Ks was increased from 20%, 30%, and then 60% and both s (nutrient concentration mM) and x (cell density cells/mL) were plotted to see how changing the Ks paramter affects s and x.
The steady state values for x and s were calculated for each case.

Third, D was increased from 5%, 10%, and then 15% and both s (nutrient concentration mM) and x (cell density cells/mL) were plotted to see how changing the D paramter affects s and x.
The steady state values for x and s were calculated for each case.

Finally, R was increased from 10%, 20%, and then 30% and both s (nutrient concentration mM) and x (cell density cells/mL) were plotted to see how changing the R paramter affects s and x.
The steady state values for x and s were calculated for each case.
