# TransLoc

This are the codes accompanyng the paper "Practical computation of the charge mobility in molecular semiconductors using transient localization theory".
In order to compile the codes you need a fortran compiler installed (e..g. gfortran) as well as lapack and blas linear algebra routines.

Compile the code
----------------
to compile edit the 'Makefile' 

- select the appropriate compiler (ifort / gfortran) default `FC = gfortran`
- where is Lapack? default  `LIBLAPACK = /usr/lib/`
- executable's directory, default `INSTALLDIR = ./`
- `make rebuild`
- run the program `./INSTALLDIR/L2.x`

Parameters files
----------------

`Lattice.inp` : lattice parameters as well as the size of the supercell
 
`Params.inp` : hopping averages (J) and fluctuations (DeltaJ), Temperature and inverse of tau_in

the parameters are that of the isotropic case reported in the paper (theta=theta_0=0.955):

DeltaJ/J=0.5

T = 24.9900278474792[meV] = 290[K]

J = 100[meV] = 1160.46[K]

inverse_tau = 5[meV] = 58.0[K]

Output files
------------

`L2RTA.dat` contains the transient localization length along x and along y