# Code for Deep Sequence-Based Models for Generating Reference Climate Datasets in Buildings’ Energy Efficiency Assessment

This repository contains the source code developed and used for the analyses and experiments presented in the research article:  
**"Deep Sequence-Based Models for Generating Reference Climate Datasets in Buildings’ Energy Efficiency Assessment"**, submitted to *IEEE Access*.

The code is available at: https://github.com/markogrebo/RY  
A citable version with DOI is archived at Zenodo: https://doi.org/10.5281/zenodo.15768673

## 📂 Repository Structure

- **`datapg.ipynb`**
- **`datank.ipynb`**
- **`databr.ipynb`**
- **`datapv.ipynb`**    
  These notebooks handle data preprocessing. They include tasks such as loading raw data, cleaning, transforming, and preparing it for analysis or modeling.

- **`refyearpg.ipynb`**
- **`refyearnk.ipynb`**
- **`refyearbr.ipynb`**
- **`refyearpv.ipynb`**
  These notebooks focus on analyzing publication years or reference data.

- **`rnnpg.ipynb`**
- **`rnnnk.ipynb`**
- **`rnnbr.ipynb`**
- **`rnnpv.ipynb`**
  These are the core implementation notebooks in which Recurrent Neural Networks (RNNs) are applied. They include models' architecture, training, evaluation, and predictions.

## ⚙️ Requirements

This codebase was developed in Python using Jupyter Notebook. Below are the required libraries:

```
pandas
numpy
seaborn
matplotlib
tensorflow
scikit-learn
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/repo-name.git
   cd repo-name
   ```

2. Open the notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```

3. Execute the cells in the following order:
   - `datapg.ipynb` → to prepare the dataset
   - `refyearpg.ipynb` → to analyze reference years
   - `rnnpg.ipynb` → to train and test the model

## 🔓 License

This code is licensed under the MIT License. You are free to use, modify, and distribute it under the terms of the license.

