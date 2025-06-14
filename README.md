# Machine Learning in Drug Design (2025)

This repository contains course materials for the course "Machine Learning in Drug Design." In the `labs` directory, there are materials covering the following topics:

1. Python and machine learning basics (revision)
    - Textual representations of molecules: SMILES
    - Vector representations of molecules: descriptors and fingerprints
    - Introduction to RDKit
    - Classical ML models: Linear Regression, Random Forest, Support Vector Machines
2. Exploration of publicly available small molecule datasets
    - ChEMBL database of bioactive molecules
    - ZINC database of purchasable molecules
    - PubChem database of chemical information about small molecules
    - Exploratory Data Analysis (EDA)
    - Quantitative Structure-Activity Relationship (QSAR) and Virtual Screening (VS)
3. Graph neural networks
    - Neural networks architectures and training
    - Molecular graphs, atomic featurization
    - Message passing neural networks
    - Graph convolutional neural networks
    - Explainability: Grad-CAM
4. Molecular docking
    - Molecular data formats: SMI, SDF, MOL2, PDB
    - Force fields
    - Protein folding
    - Molecular docking with AutoDock Vina, Smina, QuickVina
    - Interaction fingerprints
    - Pharmacophores
5. Protein deep learning
    - Simplified protein graph representations
    - Voxel grid representation
    - Mesh representation for encoding protein surface
    - 3D convolutional neural networks for encoding proteins
6. Deep generative models
    - Autoencoders
    - Recurrent neural networks
    - SMILES generators: ReLeaSE and REINVENT
    - Graph-based generative models: JT-VAE
    - Reinforcement learning and Bayesian optimization for molecular property optimization
7. Uncertainty prediction
    - Aleatoric and epistemic uncertainty
    - Conformal prediction

## About us

[GMUM](https://gmum.net/) (Machine Learning Research Group) is a group at the Jagiellonian University working on various aspects of machine learning, and in particular deep learning - in both fundamental and applied settings. The group is led by prof. Jacek Tabor.

Some of the research directions our group pursues include:
- generative models: efficient training and sampling; inpainting; super-resolution,
- theoretical understanding of deep learning and optimization,
- natural language processing,
- drug design and cheminformatics,
- unsupervised learning and clustering,
- computer vision and medical image analysis.

We are hosting machine learning seminars that are open to the public. You can check the schedule on [our website](https://gmum.net/seminars.html) and join online (links posted on [our Facebook](http://facebook.com/gmum.net)).
You can also add seminar info to your [Google calendar](https://calendar.google.com/calendar/u/0?cid=ZDJjcTFudnU0Y2UxNXNnODltdDc4Y3BtcTBAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ).

## Environment Setup

Python will be used throughout the course. The environment setup steps are shown below:

1. Install [miniconda](https://docs.conda.io/en/latest/miniconda.html) following the instructions for your operating system.
2. Download this repository: `git clone https://github.com/gmum/mldd25.git`.
   - You need to have [Git](https://git-scm.com/) installed.
3. Install environment from the YAML file: `conda env create -f environment.yml`.

_Important! If you would like to use your GPU to train neural networks, add the line `pytorch-cuda={cuda version}` in the `environment.yml` file. The current CUDA version is 12.1, but you should check your graphics card compatibility first._

## Grading scheme

The final course grade is equal to the project
grade, if the laboratories have been passed.

The laboratory grade is based on the assignments
turned in. Class attendance is mandatory and two
unexcused absences are allowed. More unexcused 
absences will result in failing the course (NZAL).

| percentage | grade |
|------------|-------|
| \>90%      | 5     | 
| \>80%      | 4.5   | 
| \>70%      | 4     | 
| \>60%      | 3.5   | 
| \>50%      | 3     | 
| ≤50%       | 2     | 

Automatic grader available at `mldd.matinf.uj.edu.pl`