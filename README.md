# AGN-Classification-Project
Code from my UCLA REU project analyzing JWST BoRG spectra to compute emission line ratios and classify galaxies.
# High-Redshift Galaxy Classification with JWST Spectroscopy
This repository contains code from my Summer 2025 UCLA Astrophysics REU project, focused on classifying galaxies in the early universe (z ≳ 6) using JWST NIRSpec data from multiple surveys.

## Project overview

The goal of this project is to improve classification of galaxies (e.g., distinguishing active galactic nuclei [AGN] from star-forming galaxies) at high redshift, where spectral differences become subtle and ambiguous. The work combines several components:

- **Spectral analysis:**  
  - Extraction of emission line fluxes (e.g., [OIII] λ5007, [OII] λ3727, Hβ, [NeIII] λ3869) and their uncertainties from reduced JWST spectra.
  - Computation of diagnostic line ratios (e.g., [OIII]/Hβ, NeIII/OII) for individual galaxies across several deep field surveys (including BoRG, CEERS, COSMOS, JADES).

- **SNR filtering:**  
  - Application of signal-to-noise ratio (SNR) cuts to ensure robust measurements for analysis and training.

- **Cross-matching with multiwavelength data:**  
  - Identification of X-ray and radio counterparts using archival catalogs to improve confidence in AGN classification.

- **Comparison with literature:**  
  - Validation of derived fluxes and ratios by comparing results against published values, accounting for differences such as logarithmic ratios used in prior work.

- **Machine learning groundwork:**  
  - Preparation of a training set combining securely classified low-redshift galaxies to enable future supervised machine learning approaches for high-redshift galaxy classification.


## Contact

Maintained by **Isaiah Mills-Terry**  
For questions or collaboration: please open an issue or contact me directly.

