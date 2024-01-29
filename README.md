# AVIRIS-NG Introduction ENVI Format Surface Reflectance

**Author:** Michele Thornton       
**Date:** August 14, 2022       
**Contact for the ORNL DAAC:** uso@daac.ornl.gov

Keywords: AVIRIS, Python, ABoVE

## Overview
This tutorial demonstrates methods to read and perform a Principal Components Analysis on 1 file of Surface Reflectance data from the AVIRIS-NG instrument. The AVIRIS-NG (Airborne Visible/Infrared Imaging Spectrometer-Next Generation) instrument provides continuous radiance measurements of surface reflectance. This approximates one step in a study of Wetland Vegetation Classification conducted by NASA's Arctic-Boreal Vulnerability Experiment (ABoVE) Science team. The study incorporated data from NASA airborne instruments, including the AVIRIS-NG instrument. The ABoVE study included applications associating spectral characteristics with land cover classification focused on water and wetland vegetation communities over the Peace-Athabasca Delta (PAD), Canada.

In this tutorial, we'll use python methods to:

- Read and explore a flight path of AVIRIS-NG Spectral Reflectance (L2) data
- Create Spectral Profiles of the AVIRIS-NG data
- Export georeferenced multiband geoTIFF files
- Run a Principal Components Analysis (PCA) on an AVIRIS-NG Spectral Reflectance file

This tutorial is inspired by a small subset of methods described in this dataset.  

**Citation:**  Wang, C., T.M. Pavelsky, E.D. Kyzivat, F. Garcia-Tigreros, F. Yao, X. Yang, S. Zhang, C. Song, T. Langhorst, W. Dolan, M. Kurek, M.E. Harlan, L.C. Smith, D. Butman, R.G.M. Spencer, C.J. Gleason, and D.L. Peters. 2022. ABoVE: Wetland Vegetation Classification for Peace-Athabasca Delta, Canada, 2019. ORNL DAAC, Oak Ridge, Tennessee, USA. https://doi.org/10.3334/ORNLDAAC/2069

**Credit**: Many methods in this tutorial borrowed from Delta-X Applications Workshop, Daniel Jensen, NASA Postdoctoral Researcher,  [Delta-X Airborne Visible/Infrared Imaging Spectrometer - Next Generation (AVIRIS-NG), Part I](https://www.youtube.com/watch?v=Ht9JdXmzKZI&list=PLO2yB4LGNlWq9KE_7Er7EIYDF6Yj9MOV2&index=3)

## AVIRIS-NG Introduction Notebook
- [AVIRIS-NG Introduction ENVI Format Surface Reflectance](ExploringAVIRIS-NGSurfaceReflectance.ipynb)

## Related Resources

More resources related to ORNL DAAC data and web services can be found at the [ORNL DAAC Learning](https://daac.ornl.gov/resources/learning/) page.
