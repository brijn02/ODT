# ODT: Optical Diffraction Tomography
Python implementation of my Bachelor thesis, which is included as PDF file. 

Forward methods:
- Mie Scattering: Compute the field of a cylinder with constant refractive index (exact, Born and Rytov approximation)
- SSNP: Split-step non-paraxial model

Reconstruction methods:
- FDT OR: the full rotation of an object
- FDT LA: a fixed object with different input angle of source
- SSNP Reconstruction: using both the phase and intensity to find the RI, implemented with TensorFlow (automatic diffrentation)
- FDT OR and SSNP Reconstruction combined: The output of the FDT OR is used as input for the SSNP reconstruction

## Installation
The code can be installed if both Param and TensorFlow are installed. Tutorials are presented in https://param.holoviz.org/ and \https://www.tensorflow.org/install
