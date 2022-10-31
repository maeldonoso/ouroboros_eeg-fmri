# ouroboros_eeg-fmri

## Ouroboros EEG-fMRI: Predicting EEG activity from fMRI activity and vice versa

Version: 22nd August 2022

Project developed by Maël Donoso, Ph.D. in Cognitive and Computational Neuroscience. Affiliations: Ouroboros Neurotechnologies (https://ouroboros-neurotechnologies.com/), Institut Lémanique du Cerveau (https://institut-cerveau.ch/), Policlinique Ostéopathique de Lausanne (https://policlinique-osteopathique-lausanne.ch/).

### Abstract

This project uses data science (NumPy, Pandas, Matplotlib) and machine learning (Scikit-Learn) tools on bandpowers obtained with Electroencephalography (EEG) and brain images obtained with functional Magnetic Resonance Imaging (fMRI). Our objective is to train machine learning models to predict EEG activity from fMRI activity, and vice versa, using a dataset from the open data repository OpenNeuro. Specifically, we use machine learning models with EEG predictors to predict the value of the fMRI BOLD signal, and machine learning models with fMRI predictors to predict the value of the EEG bandpowers. Our results show that both tasks are possible, suggesting that each technique provides some insight on processes that are, traditionally, in the realm of the other technique. 

### Structure and dependencies

This project is organized through a series of five JupyterLab Notebooks, to be run in order:

- 01. Data Analysis
- 02. Classification
- 03. Regression on fMRI data
- 04. Regression on EEG data
- 05. Results

Dependencies:

- python=3.6
- numpy=1.15
- scipy=1.2
- pandas=0.24
- matplotlib=3.0
- seaborn=0.9
- jupyterlab=2.1
- notebook=6
- scikit-learn=0.20
- tensorflow=1.12
- tensorflow-hub=0.4.0
- requests=2.20
- pillow=5.3
- graphviz=2.38
- python-graphviz=0.8.4
- pip=18.1
- tqdm
