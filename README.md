# Plugin_FIGARO_3D_PSF_optical_microscopy

## A plugin of Fiji (ImageJ) for fitting PSF of microscopes with 3D Gaussian shapes, from microsphere acquisitions possibly in high noise context

In the development of optical microscopes for biomedical imaging, the evaluation of resolution is a fundamental parameter achieved by Point Spread Function (PSF) measurements. Sometimes, this routine procedure is not easy or impossible in case of microspheres images presenting a high noise level. This method is based on a variational approach for PSF modeling through multivariate Gaussian fitting, adapted to images highly damaged.

## FIGRAO is a plugin of ImageJ (or Fiji) for estimating 3D PSFs

FIGARO have been validated for a PSF estimation of a multiphoton microscope.

## FIGARO is adapted to any kind of optical microscopes


In order to use this plugin, please, download FIGARO_-1.0.jar and place it into the folder of Fiji named "plugin". Restart Fiji. The plugin FIGARO appears into the plugin list of Fiji, gathering all the plugins already installed. Then, load the 3D images of a unique microsphere. Enter the pixel sizes in the 3 dimensions x, y and z. Excitation wavelength, numerical apearture, index and bead size can be filled. These information are involved in the generation of the PSF report for comparing the estimated PSF value with theoretical optimal value which can be deduced. 

Reference publication to cite in case of use of the plugin FIGARO:

T. K. Lau, E. Chouzenoux, C. Lefort and J.-C. Pesquet. Optimal Multivariate Gaussian Fitting for PSF Modeling in Two-Photon Microscopy. In Proceedings of the IEEE International Symposium on Biomedical Imaging (ISBI 2018), Washington DC, 4 - 7 April 2018

Contributors:

A. Lauret (CVN, CentraleSupélec, INRIA Saclay, University Paris Saclay)

K. Lau (Department of Mathematics, The Hong Kong University of Science and Technology)

E. Chouzenoux (CVN, CentraleSupélec, INRIA Saclay, University Paris Saclay & LIGM, UMR CNRS 8049)

C. Lefort (XLIM Research Institute, UMR CNRS 7252, France)

J.-C. Pesquet (CVN, CentraleSupélec, INRIA Saclay, University Paris Saclay)
