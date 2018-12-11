# TransLoc

Compile the code
----------------
to compile edit the 'Makefile' 

- select the appropriate compiler (ifort / gfortran) default `FC = gfortran`
- where is Lapack? default  `LIBLAPACK = /usr/lib/`
- executable's directory, default `INSTALLDIR = ./`
- `make rebuild`
- run the program `INSTALLDIR /L2.x`

Parameters files
----------------

`Lattice.inp` : lattice parameters as well as the size of the supercell
 
`Params.inp` : hopping averages (J) and fluctuations (DeltaJ), Temperature and inverse of tau_in

the parameters are that of the isotropic case reported in the paper (theta=theta_0=0.955):

DeltaJ/J=0.5

T = 290[K] = 24.9900278474792[meV]

J = 100[meV] = 1160.46289251836[K]

inverse_tau = 5[meV] = 58.0231446259179[K]

Output files
------------

`L2RTA.dat` contains the transient localization length along x and along y