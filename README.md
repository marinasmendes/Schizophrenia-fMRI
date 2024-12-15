### Programming for Psychologists (2024/2025)
## Home Assignment - Brain Imaging for Schizophrenia
**Course code:** M_PROPSY\
**Course coordinator:** Matthias Nau\
**Teaching assistant:** Anna van Harmelen\
**Student:** Marina Saraiva Mendes\
**Date:** 26/11/2024

This is a home assignment for the course *Programming for Psychologists*, at the Vrije Universiteit of Amsterdam. It consists of analysis of fMRI data to examine brain activity associated with schizophrenia. The results were plotted through histograms and brain activation maps. The dataset used was sourced from [NeuroSynth](https://neurosynth.org/), a platform for meta-analytic brain studies.

## Data Used

The data used for this analysis includes:
- **Functional MRI data**: This contains brain activation information related to schizophrenia.
- **Structural MRI data**: This is a high-resolution MRI scan of the human brain's anatomy.
- **Source**: The data can be found on [Neurosynth-Schizophrenia](https://neurosynth.org/analyses/terms/schizophrenia/).
    - For the analysis, two files were used, which can be easily downloaded from the above-mentioned website, in the sections `schizophrenia: uniformity test`, and `anatomical`.
    - `schizophrenia: uniformity test` is later referred to as functional data
## Notebook

The analysis and data visualization were implemented in a Jupyter Notebook `(Marina-Mendes_Schizophrenia-fMRI)`. The notebook file includes code for:
1. Loading functional and anatomical MRI data.
2. Visualizing the brain activation using the `plot_stat_map` function from Nilearn's library.
3. Plotting a histogram of functional data.

## Python and Packages Used

Python 3.12.4 was used for this project. Additionally, the following libraries were used:
- [Nilearn version 0.10.4](https://nilearn.github.io/stable/index.html)
- [NiBabel version 5.3.2](https://nipy.org/nibabel/)
- [Matplotlib version 3.9.2](https://matplotlib.org/stable/index.html)
