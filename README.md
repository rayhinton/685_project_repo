# Detecting ovarian cancer using wavelet entropy to analyze blood protein spectra

The code in this repository was used for my final project in STAT 685 at TAMU, as guided by Dr. Brani Vidakovic. The wavelet entropy is calculated for multiple regions of a blood protein mass spectra, and the entropies are used in machine learning algorithms to classify ovarian cancer patients into cases or controls.

# Usage

- The main machine learning pipeline is in `Entropies and direct methods combined.ipynb`. 
- The performance of Logistic Regression, Support Vector Machine, and K-Nearest Neighbor classifiers is compared. Hyperparameters tuning is carried out with a grid search, and the best performing settings are selected using cross-validation.

# Credit

- Vimalajeewa D, Bruce SA, Vidakovic B. Early detection of ovarian cancer by wavelet analysis of protein mass spectra. _Statistics in Medicine_. 2023; 42(13): 2257-2273. doi: [10.1002/sim.9722](https://doi.org/10.1002/sim.9722).
- National Cancer Institute. Clinical Proteomics Program Databank - Proteomics Patterns. [https://home.ccr.cancer.gov/ncifdaproteomics/ppatterns.asp](https://home.ccr.cancer.gov/ncifdaproteomics/ppatterns.asp). Accessed March 7, 2023.
