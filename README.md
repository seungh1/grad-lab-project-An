# grad-lab-project-An
QE repo for IMGS 609

# **Project: Exploitation of Hyperspectral Imagery using Graph Convolutional Network**

## **Description**: Hyperspectral Imaging (HSI) data typically has hundreds of bands associated with a wavelength for each pixel in an image. These bands can be exploited to search and identify certain materials in the scene as they can have specific spectra features that can be delineated from the background. This technique is called target detection and many tradition algorithms such as the Adaptive Coherence Estimator (ACE) have proven to be a robust and reliable method with background that is gaussian in nature and targets that are linear. However, effects in the atmosphere, viewing geometry, and mixing of materials can make the scene non-gaussian and non-linear. This project will explore the feasibility of utilizing Graph Convolution Network (GCN) on Hyperspectral Imaging data to perform target detection on non-linear targets and non-gaussian backgrounds.

## **Data and Imaging Modality**: Multiple datasets will be used to train, validate, and evaluate the GCN model. Primarily, the SHARE 2010 and ROCX 2025 are readily available to use from RIT CIS. Various scenes that contain red/blue panels and UXO landmines will be used as the target of interest.

## **Programming Language & Tools**: Python 3.12 with Numpy, Scipy, Spy, Torch, and Sklearn packages

## Roadmap

- [x] Build baseline algorithms into workflow for comparison 
- [ ] Modify GCN model to perform target detection
- [ ] Evaluate GCN model on dataset
- [ ] ?????
- [ ] Profit
