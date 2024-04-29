# FMTOMO
Source code and instructions for using FMTOMO

FMTOMO is a Fortran 90 code for undertaking 3-D traveltime tomography in spherical coordinates. Models consist of one or more layers within which velocity can vary in 3-D, separated by layer boundaries or interfaces that have variable geometry. A range of data can be exploited, including teleseismic arrival times from a variety of global body wave types, local and regional earthquake traveltimes, and reflection and refraction phases e.g. from airguns, explosions or vibroseis.The forward problem is solved using a the so-called Fast Marching Method, which is a grid-based eikonal solver, while the inverse problem is solved using an iterative non-linear approach based on a subspace inversion scheme. Unknowns that can be inverted for include velocity, interface and hypocenter parameters.

A fork known as FMTOMO-extras is also provided in this distribution. It uses the same base code as FMTOMO, but includes a routine for the fully non-linear relocation of hypocenters, which can be used in local earthquake tomography, for example.

FMTOMO has an extensive user guide, while FMTOMO-extras has a relatively brief userguide, since it is just an add-on to the base package.
