===============================================================================
PROJECT: Feigenbaum Constant Computation Engine
===============================================================================

OVERVIEW:
Calculates the Feigenbaum constant delta (delta ≈ 4.66920160910299067185...) to 
arbitrary precision (N digits). Delta is a fundamental universal constant governing 
chaos theory across fluid turbulence, electronic circuits, and population dynamics.

ALGORITHM & MATHEMATICS:
- Period-Doubling Ratio Limit:
    delta = lim_{k -> infinity} (r_k - r_{k-1}) / (r_{k+1} - r_k)
- Evaluates period-doubling bifurcation roots for quadratic maps using mpmath + gmpy2.
