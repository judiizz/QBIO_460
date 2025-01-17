# Exploring Deep Learning in Single-Cell Studies: PCA and Autoencoder Approaches for Feature Extraction and Clustering of Muscle Cells

## Overview
This project investigates the performance of traditional Principal Component Analysis (PCA) versus a deep learning autoencoder for feature extraction in high-dimensional single-cell RNA sequencing (scRNA-seq) data. The dataset focuses on hindlimb muscle from the Green Anole lizard, aiming to explore the biological complexity of muscle regeneration.

## Objective
The primary goal is to determine whether a fully connected neural network can reveal distinct clustering patterns beyond those identified by conventional scRNA-seq tools like Seurat and Scanpy, which primarily use PCA for dimensionality reduction.

## Methodology
- **Dimensionality Reduction**: Compared PCA and an autoencoder model for feature extraction.
- **Visualization**: Used UMAP (Uniform Manifold Approximation and Projection) for 2D visualization of the data.
- **Clustering**: Applied Gaussian Mixture Modeling (GMM) to identify clusters.
- **Data Source**: Single-cell RNA sequencing data from Green Anole lizard hindlimb muscle, obtained from USC Stem Cell Almada Lab.

## Key Findings
- The autoencoder model uncovered distinct subclusters within the data.
- These subclusters suggest heterogeneity in the muscle stem cell (MuSC) population.
- The results demonstrate the potential for deep learning methods to complement traditional ML approaches, offering deeper insights into biological complexity.

## Significance
By leveraging deep learning, this project highlights the potential for enhanced single-cell data analysis, particularly in understanding the regenerative processes in muscle stem cells.

## Technologies Used
- **Programming Languages**: Python
- **Deep Learning Framework**: TensorFlow/Keras (for the autoencoder)
- **scRNA-seq Tools**: Seurat, Scanpy
- **Visualization Tools**: UMAP, Matplotlib/Seaborn
- **Clustering**: Gaussian Mixture Modeling (GMM)

## Future Directions
- Extend analysis to other tissue types and organisms.
- Incorporate additional advanced ML models for scRNA-seq data.
- Validate findings through biological experiments.

