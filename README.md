# TransLoc

Compile the code
----------------
to compile edit the 'Makefile' and select the appropriate compiler then 'make rebuild' the code name is L2.x you can run it directly by doing './L2.x'. A fortran compiler is needed as well as lapack libraries.

Parameters files
----------------

'Lattice.inp' : lattice parameters as well as the size of the supercell
 
'Params.inp' : hopping averages (J) and fluctuations (DeltaJ), Temperature and inverse of tau_in

the parameters are that of the isotropic case reported in the paper (theta=theta_0=0.955):

DeltaJ/J=0.5

T = 290[K] = 24.9900278474792[meV]

J = 100[meV] = 1160.46289251836[K]

inverse_tau = 5[meV] = 58.0231446259179[K]
