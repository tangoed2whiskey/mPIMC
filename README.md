# mPIMC
Path Integral Monte Carlo code in Mathematica


mPIMC is a bosonic Path Integral Monte Carlo code written in Mathematica.  The aim of mPIMC is to provide an easy-to-understand, easy-to-modify, easy-to-generalise code base that is still efficient for simulations of larger systems.

mPIMC was designed with cold atomic gas simulations in mind; as such, it works with finite systems, allowing the explicit inclusion of external traps, harmonic or otherwise.

This is an explicitly parallel code; it will set up and use as many kernels as it can on the system you run it on.  This parallelisation is used simply to reduce statistical error bars in the results.

To use mPIMC, extract the zip file into somewhere on your $Path, e.g. C:\ProgramData\Mathematica\Applications and then take a look at the example files (Documentation\English\Tutorials).


If you find a bug (or, even better, fix a bug) in this code, please let me know via tmw38@tcm.phy.cam.ac.uk and I'll put a fix in the main version.
