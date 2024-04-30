# FMTOMO
Source code and instructions for using FMTOMO

FMTOMO is a Fortran 90 code for undertaking 3-D traveltime tomography in spherical coordinates. Models consist of one or more layers within which velocity can vary in 3-D, separated by layer boundaries or interfaces that have variable geometry. A range of data can be exploited, including teleseismic arrival times from a variety of global body wave types, local and regional earthquake traveltimes, and reflection and refraction phases e.g. from airguns, explosions or vibroseis.The forward problem is solved using a the so-called Fast Marching Method, which is a grid-based eikonal solver, while the inverse problem is solved using an iterative non-linear approach based on a subspace inversion scheme. Unknowns that can be inverted for include velocity, interface and hypocenter parameters.

A fork known as FMTOMO-extras is also provided in this distribution. It uses the same base code as FMTOMO, but includes a routine for the fully non-linear relocation of hypocenters, which can be used in local earthquake tomography, for example.

FMTOMO has an extensive user guide, while FMTOMO-extras has a relatively brief userguide, since it is just an add-on to the base package.

## Documentation

A detailed manual for FMTOMO can be found in the docs subdicrectory. A brief document outlining how to use the FMTOMO Extras packages is also included in this subdirectory.

## Installation

The complete distro of the FMTOMO package (fmtomov1.2.tar.gz) and FMTOMO Extras package (fmtomo_extrasv1.1.tar.gz). These can be unpacked using something like "tar -xvzf filename". The instruction manuals contain detailed installation instructions.

## Citation

If you use FMTOMO, please cite

Rawlinson, N., and M. Urvoy (2006), Simultaneous inversion of active and passive source datasets for 3-D seismic structure with application to Tasmania, Geophys. Res. Lett., 33, L24313, doi:10.1029/2006GL028105. 

de Kool, M., Rawlinson, N. and Sambridge, M. (2006), A practical grid-based method for tracking multiple refraction and reflection phases in three-dimensional heterogeneous media, Geophysical Journal International, Volume 167, 253–270, https://doi.org/10.1111/j.1365-246X.2006.03078.x

If you use FMTOMO Extras, please cite

Pilia S., N. Rawlinson, N. G. Direen, P. R. Cummins, and N. Balfour (2013), Structural controls on localized intraplate deformation and seismicity in southern Australia: insights from local earthquake tomography of the Flinders Ranges, Journal of Geophysical Research: Solid Earth, 118, 2176–2190, doi:10.1002/jgrb.50168.

## Contact

If you have any questions, please contact Nick Rawlinson (nr441@cam.ac.uk)
