# Quantum Support Vector Machine (QSVM) on MNIST with D-Wave Quantum Annealers

**Authors:** Taimur Khan (UFZ), Salvatore Zammuto (TUM), Hessen Mousa (CSB), Benjamin Papajewski (FZJ)

This repo contains code for training and evaluating a Quantum Support Vector Machine (QSVM) using QUBO formulations and solving them on D-Wave quantum annealers (Pegasus topology) or hybrid solvers.

For a binary QSVM implemenation see, [qsvm-binary.ipynb](./qsvm-binary.ipynb)

### Dataset

We use the Scikit-Learn's "digits" dataset that has 1797 images of hand written digits with 8x8 pixels. We chose this instead of original MNIST dataset to reduce the pixel dimesnions from 256x256 pixels per iamge to 8x8.

### Slides

See our presentation slides for the JUNIQ/EPIC Summer School on Quantum Computing (2025) here --> [slides](./JUNIQ-EPIC_slides.pdf)

### Method

This code is adapted from:
📜 G. Cavallaro, D. Willsch, M. Willsch, K. Michielsen, and M. Riedel, “Approaching Remote Sensing Image Classification with Ensembles of Support Vector Machines on the D-Wave Quantum Annealer,” in Proceedings of the IEEE International Geoscience and Remote Sensing Symposium (IGARSS), pp. 1973-1976, 2020, https://doi.org/10.1109/IGARSS39084.2020.9323544
https://gitlab.jsc.fz-juelich.de/cavallaro1/svm_quantum-annealer


