 
## Overview
This repository contains the computational pipeline for mapping and analyzing the structural features of the human hippocampus. The project evaluates the heritability of hippocampal structure, its structural covariance, and its latent connections to behavioral profiles.

## Pipeline and File Structure 

* **`Demographics.ipynb`**: Parses restricted and unrestricted participant data to extract twin topology (Monozygotic/Dizygotic pairs, singletons) and baseline demographic covariates (Age, Gender, Race).  
* **`Mean_metrics.ipynb`**: Computes and visualizes the average morphological metrics (such as thickness, curvature, gyrification, and T1w/T2w ratios) across the hippocampal surface using unfolded coordinate spaces.
* **`Heritability.ipynb`**: Calculates the heritability of the extracted features, leveraging the MZ/DZ twin variance.
* **`Scov_Hip_Hip.ipynb`**: Maps the structural covariance within the hippocampus, analyzing how different topological regions vary together across the subject cohort.
* **`RCCA.ipynb`**: Performs Regularized Canonical Correlation Analysis (RCCA) to identify the latent space connecting hippocampal variation with behavioral traits.
