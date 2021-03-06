# myInterPhaseChangeFoam_solver
A multiphase solver for cavitation and boiling problems.
Solver for 2 incompressible, isothermal immiscible fluids with phase-change (e.g. cavitation). Uses a VOF (volume of fluid) phase-fraction based interface capturing approach, with optional mesh motion and mesh topology changes including adaptive re-meshing. The original solver was made by OpenFOAM community and this is a modified solver which has an additional field variable as temperature and its effect on boiling.

- The momentum and other fluid properties are of the "mixture" and a single momentum equation is solved.
- The set of phase-change models provided are designed to simulate cavitation but other mechanisms of phase-change are supported within this solver framework.
- Turbulence modelling is generic, i.e. laminar, RAS or LES may be selected.
![Image](https://cpp.openfoam.org/v8/dir_072f0e2674ae04115e1196cfcbf8d2aa_dep.png)

Source: OpenFOAM V6.0
