# What dMFTlab is
A didactic/explorative implementation of (real axis) IPT-based Dynamical Mean Field Theory for the half-filled Hubbard model on the Bethe lattice, within Matlab language (R2019a).

# License and stuff
This code has been implemented taking inspiration from these two didactic sources:
1. http://www.physics.rutgers.edu/~haule/681/Perturbation.pdf   
2. https://www.cond-mat.de/events/correl19/manuscripts/rozenberg.pdf
and the hands-on material given therein, in particular a tutorial-intended jupyter notebook provided by Óscar Nájera (available at http://mycore.core-cloud.net/index.php/s/oAz0lIWuBM90Gqt) under the BSD 3-Clause License. Here we provide a Matlab rewrite, plus some extensions (phase diagram loops, including convergence and self-mixing control, various post-processing and data analysis routines), again under BSD 3-Clause License. You can read more about allowed use of this code in the LICENSE file.

# To do
- Insert a "restarting" protocol for full phase diagram spans. The gloc0=0 conditions appers to be too weak to obtain accurate UC1 lines. (in progress...)
- Compute the Luttinger Integral, as defined in *Phys. Rev. B 102, 081110(R)* and *J. Phys.: Cond Mat 28 025601*. Since it appears to be quantized it could become the perfect flag for phase diagrams; much better than Z.
