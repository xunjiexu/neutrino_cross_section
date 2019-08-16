# This code shows how to analytically compute neutrino cross sections using FeynCalc.


cross-section_compute.nb computes the cross section,

results are summarized in cross_section_result.nb.

Conventions are taken from two of my papers:

[1] J. Link, X. Xu, JHEP, [1903.09891],
Searching for BSM neutrino interactions in dark matter detectors.

[2] W. Rodejohann, X. Xu, C. Yaguna, JHEP, [1702.05721],
Distinguishing between Dirac and Majorana neutrinos in the presence of general interactions.

If FeynCalc is not installed on your computer, you need to run the following code in your Mathematica to install FeynCalc

Import["https://raw.githubusercontent.com/FeynCalc/feyncalc/master/install.m"];

InstallFeynCalc[]