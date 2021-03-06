# maxent-julia
A Julia implementation of the maximum-entropy basis functions. (Compatible with Julia 1.0)

# Author
<a href="https://github.com/aaortizb">Alejandro Ortiz-Bernardin</a>, Assistant Professor, Department of Mechanical Engineering, Universidad de Chile.

José M. Cáceres, Undergraduate Research Assistant, Department of Mechanical Engineering, Universidad de Chile.

# Instructions
The program is controlled by the main.jl function. This is the only function that
must be setup by the user. To execute the code, setup the problem parameters in
main.jl (further instructions are given there) and run it.

When setting up main.jl make sure that
  - length(x) = dim
  - if dim>=2, length(x) = size(ncoord)[2]
  - if dim=1, length(x) = length(ncoord)/n
  - size(ncoord)[1] = n
  - length(gamma) = n
  - length(ilambda) = dim

Anyway, an error is thrown when any of the previous equalities are not satisfied.

# License
This project is licensed under the GPL3 License. This program is free software; it can be redistributed or modified under the terms of the GNU General Public License 3 as published by the Free Software Foundation.
