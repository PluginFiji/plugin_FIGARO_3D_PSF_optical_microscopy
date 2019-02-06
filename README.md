# plugin_FIGARO_3D_PSF_optical_microscopy

A plugin of Fiji (ImageJ) for fitting PSF of microscopes with 3D Gaussian shapes, from microsphere acquisitions possibly in high noise context

In the development of instruments for biomedical microscopy, the evaluation of resolution is a fundamental point achieved by Point Spread Function (PSF) measurements. Sometimes, this routine procedure is not easy or impossible in case of microspheres images presenting a high noise level.

Here, we propose a plugin of ImageJ (or Fiji) for estimating 3D PSFs of microscopes, which have been validated for a PSF estimation of a multiphoton microscope.

This method is based on a variational approach for PSF modeling through multivariate Gaussian fitting, adapted to images highly damaged.

Reference publication to cite in case of use of the plugin FIGARO:

T. K. Lau, E. Chouzenoux, C. Lefort and J.-C. Pesquet. Optimal Multivariate Gaussian Fitting for PSF Modeling in Two-Photon Microscopy. In Proceedings of the IEEE International Symposium on Biomedical Imaging (ISBI 2018), Washington DC, 4 - 7 April 2018

In order to use this plugin, please, download FIGARO_-1.0.jar and place it into the folder of Fiji named "plugin". Restart Fiji. The plugin FIGARO appears into the plugin list of Fiji, gathering all the plugins already installed.

Contributors:

A. Lauret (CVN, CentraleSupélec, INRIA Saclay, University Paris Saclay)

K. Lau (Department of Mathematics, The Hong Kong University of Science and Technology)

E. Chouzenoux (CVN, CentraleSupélec, INRIA Saclay, University Paris Saclay & LIGM, UMR CNRS 8049)

C. Lefort (XLIM Research Institute, UMR CNRS 7252, France)

J.-C. Pesquet (CVN, CentraleSupélec, INRIA Saclay, University Paris Saclay)
