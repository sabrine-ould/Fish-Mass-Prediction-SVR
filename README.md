# 🐟 Fish Mass Prediction using SVR

\<p align="center">
&#x20; \<strong>Predicting Fish Body Mass with Machine Learning\</strong>
&#x20; \<br>
&#x20; \<em>Programming for Data Science · Master 1 · 2026–2027\</em>
\</p>

\<p align="center">
&#x20; \<img src="[https://img.shields.io/badge/Theme-T3%20Fish-167D9A?style=for-the-badge](https://img.shields.io/badge/Theme-T3%20Fish-167D9A?style=for-the-badge)" />
&#x20; \<img src="[https://img.shields.io/badge/Model-SVR-2455A4?style=for-the-badge](https://img.shields.io/badge/Model-SVR-2455A4?style=for-the-badge)" />
&#x20; \<img src="[https://img.shields.io/badge/Task-Regression-398477?style=for-the-badge](https://img.shields.io/badge/Task-Regression-398477?style=for-the-badge)" />
\</p>

---

## 01 · Project Overview

This project is a Data Science mini-project focused on predicting fish body mass using **Support Vector Regression (SVR)** with an RBF kernel.

The study uses fish measurements and environmental variables to predict the logarithm of fish mass.

## 02 · Project Information

| **Property** | **Description**                 |
| :----------- | :------------------------------ |
| Theme        | T3 – Fish                       |
| Group        | G1 – Regression                 |
| Pair ID      | T3Vr1-B3                        |
| Model        | Support Vector Regression (SVR) |
| Kernel       | RBF                             |
| Epsilon      | 0.1                             |

## 03 · Dataset

\<blockquote>
&#x20; The dataset contains information about \<strong>12,288 fish\</strong> belonging to \<strong>24 species\</strong> across \<strong>118 sites\</strong>.
\</blockquote>

**Original source:** Arranz et al. (2022), *Data in Brief*.

**DOI:** [10.1016/j.dib.2022.108248](https://doi.org/10.1016/j.dib.2022.108248)

## 04 · Project Structure

```text
Fish-Mass-Prediction-SVR/
│
├── Data/
│   ├── Dataset files
│   └── Data dictionary
│
├── Documentation/
│   └── Project instructions
│
├── Notebook/
│   └── fish_svr_project.ipynb
│
├── requirements.txt
└── README.md
```

## 05 · Installation & Execution

**Step 1 — Clone the repository**

```bash
git clone https://github.com/sabrine-ould/Fish-Mass-Prediction-SVR.git
cd Fish-Mass-Prediction-SVR
```

**Step 2 — Install dependencies**

```bash
pip install -r requirements.txt
```

**Step 3 — Launch Jupyter Notebook**

```bash
jupyter notebook
```

**Step 4 — Run the project**

Open `Notebook/fish_svr_project.ipynb` and execute all cells from beginning to end.

## 06 · Methodology

The project follows these main stages:

| Stage | Description                                        |
| :---: | :------------------------------------------------- |
|   01  | Exploratory Data Analysis (EDA)                    |
|   02  | Data Cleaning and Preprocessing                    |
|   03  | Categorical Feature Encoding                       |
|   04  | Feature Scaling                                    |
|   05  | Baseline Model Evaluation                          |
|   06  | SVR Hyperparameter Tuning                          |
|   07  | Model Evaluation using Site-Based Cross-Validation |

---

\<p align="center">   \<strong> T3Vr1-B3 \</strong>   \<br>   \<em>Programming for Data Science · 2026–2027\</em> \</p>

