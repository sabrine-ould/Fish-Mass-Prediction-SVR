🐟 Fish Mass Prediction | SVR
<p align="center">
  **Predicting Fish Body Mass Using Machine Learning**
</p>

📌 About the Project
A Data Science mini-project focused on predicting fish body mass using Support Vector Regression (SVR) with an RBF kernel.

## Project Overview
This project is a Data Science mini-project focused on predicting fish body mass using **Support Vector Regression (SVR)** with an RBF kernel.

The study uses fish measurements and environmental variables to predict the logarithm of fish mass.

## Project Information
- **Theme:** T3 – Fish
- **Group:** G1 – Regression
- **Pair ID:** T3Vr1-B3
- **Model:** Support Vector Regression (SVR)
- **Kernel:** RBF
- **Epsilon:** 0.1

## Dataset
The dataset contains information about 12,288 fish belonging to 24 species across 118 sites.

**Source:** Arranz et al. (2022), Data in Brief.

**DOI:** https://doi.org/10.1016/j.dib.2022.108248

## Project Structure
- `Data/` – Original dataset files and data dictionary.
- `Documentation/` – Project instructions.
- `Notebook/` – Jupyter notebook containing the project implementation.
- `requirements.txt` – Required Python libraries.

## Installation and Execution

1. Clone the repository:
   ```bash
   git clone https://github.com/sabrine-ould/Fish-Mass-Prediction-SVR.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Fish-Mass-Prediction-SVR
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the notebook:
   ```bash
   jupyter notebook
   ```

5. Run `Notebook/fish_svr_project.ipynb` from beginning to end.

## Methodology
The project includes:
- Exploratory Data Analysis (EDA).
- Data cleaning and preprocessing.
- Categorical feature encoding.
- Feature scaling.
- Baseline model evaluation.
- SVR hyperparameter tuning.
- Model evaluation using site-based cross-validation.

## Authors
T3Vr1-B3 – Programming for Data Science, Academic Year 2026–2027.
