# EIS-ML-BacterialDiagnostics

## Overview

This repository contains the codebase and documentation for a research project aimed at developing a rapid, cost-effective diagnostic tool for bacterial infections by combining Electrochemical Impedance Spectroscopy (EIS) with advanced machine learning (ML) techniques.

## Project Description

Bacterial infections represent a major global health challenge, and current diagnostic methods often suffer from long detection times and high costs. This project proposes a novel approach where EIS data—which captures the electrical properties of bacterial cells—is processed and interpreted using ML models. The goal is to accurately detect and quantify bacterial presence and viability, ultimately improving patient outcomes and food/water safety.

Key components of the project include:
- **Data Preprocessing:** Using libraries such as Pandas, NumPy, and SciPy to clean and normalize raw EIS data.
- **Feature Extraction & Dimensionality Reduction:** Implementing statistical analysis and Principal Component Analysis (PCA) with scikit-learn to derive meaningful features.
- **Model Development:** Building and validating individual models (Random Forests, Support Vector Machines, Neural Networks) and integrating them into a meta-model for enhanced predictive performance.
- **Visualization & Analysis:** Leveraging Matplotlib and Seaborn for exploratory data analysis and result visualization.
- **Interactive Prototyping:** Utilizing Jupyter Notebooks (and Google Colab) for iterative development and experimentation.

## Getting Started

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/dkanh6/EIS-ML.git
   cd EIS-ML
