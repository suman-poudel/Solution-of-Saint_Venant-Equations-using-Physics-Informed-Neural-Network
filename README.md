# Solution-of-Saint_Venant-Equations-using-Physics-Informed-Neural-Network

This repository contains a solution to the simplified Saint-Venant Equation (SVE) using Physics-Informed Neural Networks (PINNs).

The continuity equation for SVE is taken as dh/dt + d(hu)/dx = 0.

The momentum equation for SVE is taken as du/dt + u * du/dx + g * dh/dx = 0.

Following are the assumptions made for simplifying the SVE equations:
1. The friction slope S_f ​ and bed slope S_0 ​ are ignored.
2. One-Dimensional Flow Approximation
3. No Lateral Inflows or Outflows
4. Hydrostatic Pressure Assumption
5. Shallow Water Assumption
