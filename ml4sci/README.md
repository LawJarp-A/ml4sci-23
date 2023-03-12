# Machine Learning for Science (ML4SCI)

* [Gsoc page](https://summerofcode.withgoogle.com/programs/2022/organizations/machine-learning-for-science-ml4sci)
* [Ideas page](https://ml4sci.org/gsoc/2023/summary.html)
* [Pre-req](https://docs.google.com/document/d/1lWTSASnVICm_4Zof7wr6_LkS24P_Z8TR1px_tctemQI/edit?usp=sharing)
* Socials
  * [Gitter](https://matrix.to/#/#ML4SCI_general:gitter.im)

## Pre - Requisites

### Task 1 
Common Task 1: Electron/photon classification
Datasets:
* https://cernbox.cern.ch/index.php/s/AtBT8y4MiQYFcgc (photons: https://cernbox.cern.ch/remote.php/dav/public-files/FbXw3V4XNyYB3oA/SingleElectronPt50_IMGCROPS_n249k_RHv1.hdf5)
* https://cernbox.cern.ch/index.php/s/FbXw3V4XNyYB3oA (electrons: https://cernbox.cern.ch/remote.php/dav/public-files/FbXw3V4XNyYB3oA/SingleElectronPt50_IMGCROPS_n249k_RHv1.hdf5)

Description: 32x32 matrices (two channels - hit energy and time) for two classes of
particles electrons and photons impinging on a calorimeter

Please use a deep learning method of your choice to achieve the highest possible
classification on this dataset (we ask that you do it both in Keras/Tensorflow and in
PyTorch). Please provide a Jupyter notebook that shows your solution. The model you submit should have a ROC AUC score of at least 0.80.

#### What is hit energy and time?
n the context of a calorimeter, "hit energy" refers to the amount of energy deposited by a particle as it passes through the detector. When a particle interacts with the material in the calorimeter, it produces a shower of secondary particles, which deposit their energy in the detector's active material. The total amount of energy deposited by the shower is measured and recorded as the "hit energy."

"Time" refers to the time at which the energy deposition occurs. The timing information is important for distinguishing particles that travel at different speeds, as particles that are traveling faster will deposit their energy at a different time than particles that are traveling more slowly. The time information is also useful for triggering the readout of the detector, as the energy deposits may occur at different times, depending on the particle's trajectory through the detector.

