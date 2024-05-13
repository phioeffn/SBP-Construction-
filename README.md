# Optimization-based construction procedure for function space SBP Operators

This is the public repository refering to the article 

"An optimization-based construction procedure for function space based summation-by-parts operators on arbitrary grids"

by Jan Glaubitz, Jan Nordström and Philipp Öffner. 

You find the code to produce function space SBP operators via an optization procedure and to reproduce the results 
from the paper. The code has several parts. 
The main parts are: 

SchrPics.jl (Test case for the Schrödinger equation) 

Convana.jl (For the convergence tests where the operators have to be adapted in bandedpoly.jl)

Bandedpoly.jl (Can be used to construct the operators as well as optest.jl.)


## Disclaimer for the code

Everything is provided as-is and without warranty. Use at your own risk!
