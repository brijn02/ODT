# ODT: Optical Diffraction Tomography
Python implementation of my Bachelor thesis, which is included as a PDF file. 

Forward methods:
- Mie Scattering: Compute the field of a cylinder with constant refractive index (exact, Born and Rytov approximation)
- SSNP: Split-step non-paraxial model

Reconstruction methods:
- FDT OR: the full rotation of an object
- FDT LA: a fixed object with a different input angle from the source
- SSNP Reconstruction: using both the phase and intensity to find the RI, implemented with TensorFlow (automatic differentiation)
- FDT OR and SSNP Reconstruction combined: The output of the FDT OR is used as input for the SSNP reconstruction

## Installation
The code can be installed if both Param and TensorFlow are installed. Tutorials are presented at https://param.holoviz.org/ and https://www.tensorflow.org/install.
![](https://github.com/brijn02/ODT/blob/main/Figures/2D_SSNP_Solver.gif)
