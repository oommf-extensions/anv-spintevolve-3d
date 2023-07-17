# Anv_SpinTEvolve_3d
Martin Lang<sup>1, 2</sup> and Hans Fangohr<sup>1, 2, 3</sup>

<sup>1</sup> Max Planck Institute for the Structure and Dynamics of Matter, Luruper Chaussee 149, 22761 Hamburg, Germany   
<sup>2</sup> Faculty of Engineering and the Environment, University of Southampton, Southampton SO17 1BJ, United Kingdom  
<sup>3</sup> Center for Free-Electron Laser Science, Luruper Chaussee 149, 22761 Hamburg, Germany

## About

Generalisation of the spin-transfer torque extension (`Anv_SpinTEvolve`) of
OOMMF (https://math.nist.gov/oommf/), initially written by Antoine Vanhaverbeke
(https://www.zurich.ibm.com/st/nanomagnetism/spintevolve.html). The original
version of the extension can be seen in
[this commit](https://github.com/oommf-extensions/anv-spintevolve-3d/tree/75ddb5d04c40a7c7213ab2bba9cf1f4e7e0d79a8),
it is distributed as part of OOMMF and taken from the OOMMF source distribution (further details are availble under https://math.nist.gov/oommf/contrib/oxsext/).
The modified version supports arbitrary current directions (`3d`).

Support in [Ubermag](https://ubermag.github.io) will be provided in the next release.

## Installation options

- Copy `src/spintevolve_3d.cc` and `src/spintevolve_3d.h` to the `app/oxs/local` directory in OOMMF and recompile following the standard procedure (`$ tclsh oommf.tcl pimake distclean && tclsh oommf.tcl pimake upgrade && tclsh oommf.tcl pimake`).
- A copy of the OOMMF sources with the extension included already is available under https://github.com/fangohr/oommf. Further installation options are provided there.
- OOMMF with the additional extension can be installed from [conda-forge](https://anaconda.org/conda-forge/oommf) (starting with version `2.0b0.post1`).
