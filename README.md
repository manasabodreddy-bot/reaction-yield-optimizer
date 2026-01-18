# Reaction Yield Optimizer

## Overview
This project explores baseline machine learning approaches for reaction yield prediction in low-data settings. The focus is on building a clean modeling pipeline and examining the behavior of simple surrogate models when applied to limited reaction datasets.

The project is intended as an exploratory study rather than a fully optimized reaction optimization system.

## Motivation
Predicting reaction yields is an important but challenging problem in computational chemistry. Experimental data are often scarce, noisy, and highly sensitive to reaction conditions, making reliable prediction difficult.

This project was motivated by an interest in understanding how far simple models can be pushed in such data-limited regimes, and where their limitations become apparent.

## Dataset
Due to the limited availability of large, clean reaction yield datasets, this project uses a curated reaction dataset inspired by published cross-coupling reaction studies. The dataset is intended to support methodological exploration rather than definitive performance benchmarking.

## Methodology
Reaction components are featurized using standard molecular representations. A Random Forest regressor is used as a baseline surrogate model to predict reaction yields.

The emphasis is on establishing a transparent modeling pipeline and evaluating baseline behavior rather than performing extensive hyperparameter optimization.

## Experiments
Experiments were conducted using a train–test split of the available data. Model performance was evaluated using standard regression metrics such as mean absolute error (MAE).

These experiments serve as a feasibility study for reaction yield modeling under data-scarce conditions.

## Results
Baseline models achieved limited predictive performance, reflecting both the difficulty of the task and the constraints imposed by dataset size and representation. These results suggest that more expressive models and richer reaction descriptors would be required for reliable yield prediction.
A representative visualization (active_learning_plot.png) is included to illustrate model behavior during iterative data selection under limited data conditions.
## Limitations
This study is limited by the size and scope of the dataset, simplified reaction representations, and the exclusion of detailed experimental conditions such as solvent, temperature, and catalyst loading.

As a result, the project should be viewed as an exploratory analysis rather than a production-ready optimization framework.

active_learning_plot.png # Visualization illustrating model behavior during iterative selection
README.md # Project documentation
