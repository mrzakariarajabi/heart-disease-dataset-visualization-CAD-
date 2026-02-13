# heart-disease-dataset-visualization-CAD-

This repository provides the dataset and ipynb(python) source code used to generate the figures and plots reported in our article. The purpose of sharing this repository is to improve transparency, reproducibility, and reusability of the experimental results, enabling other researchers to replicate the visualizations and perform further benchmarking on the same clinical dataset.

The repository includes:  
1) the cardiovascular dataset used in the study, and  
2) python (`.ipynb`) scripts that reproduce the statistical plots and analyses included in the manuscript.

---

## Dataset Description

The dataset included in this repository is a clinical cardiovascular dataset designed for the analysis and prediction of heart disease status. It contains demographic, clinical examination results, laboratory measurements, and lifestyle-related risk factors. The dataset can be used for statistical analysis, predictive modeling, and classification experiments in medical and clinical research.

The dataset is provided in CSV format and contains the following features:

| Feature     | Description |
|------------|-------------|
| **Age**     | Age of the patient (in years) |
| **sex**     | Sex of the patient |
| **cp**      | Chest pain type |
| **trestbps**| Resting systolic blood pressure (mmHg) |
| **chol**    | Serum cholesterol level (mg/dl) |
| **cigs**    | Cigarettes smoked per day |
| **years**   | Number of years as a smoker |
| **fbs**     | Fasting blood sugar > 120 mg/dl |
| **famhist** | Family history of coronary artery disease |
| **restecg** | Resting electrocardiographic results |
| **thalach** | Maximum heart rate achieved |
| **thalrest**| Resting heart rate |
| **tpeakbps**| Peak exercise systolic blood pressure |
| **tpeakbpd**| Peak exercise diastolic blood pressure |
| **trestbpd**| Resting diastolic blood pressure |
| **exang**   | Exercise-induced angina |
| **oldpeak** | ST depression induced by exercise relative to rest |
| **slope**   | Slope of the peak exercise ST segment |
| **ca**      | Number of major vessels (0–3) colored by fluoroscopy |
| **thal**    | Thallium-201 stress scintigraphy |
| **num**     | Diagnosis of heart disease (angiographic disease status) |
| **outcome** | Binary diagnosis of heart disease (angiographic disease status) |

The dataset includes both multi-class and binary target variables. The **`num`** attribute represents angiographic disease status in a multi-class form, while the **`outcome`** variable provides a binary classification label indicating the presence or absence of heart disease.

---

## Reference

If you use this dataset or repository in your research, please cite the following article:

Marateb, H. R., & Goudarzi, S. (2015). *A noninvasive method for coronary artery diseases diagnosis using a clinically-interpretable fuzzy rule-based system*. Journal of Research in Medical Sciences, 20(3), 214–223.  
https://journals.lww.com/jrms/fulltext/2015/20030/A_noninvasive_method_for_coronary_artery_diseases.2.aspx



