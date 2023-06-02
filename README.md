# Project Proposal: Predicting the Presence of Heart Disease

### Introduction

Heart disease refers to the buildup of plaque in the heart's arteries that can ultimately lead to a heart attack, heart failure, or death. [The Government of Canada website](https://www.canada.ca/en/public-health/services/publications/diseases-conditions/heart-disease-canada.html) identifies heart disease as the 2nd leading cause of death in Canada. According to 2017–2018 data from the Canadian Chronic Disease Surveillance System (CCDSS):

- about 1 in 12 (or 2.6 million) Canadian adults age 20 and over live with diagnosed heart disease
- every hour, about 14 Canadian adults age 20 and over with diagnosed heart disease die

Heart disease impacts a significant portion of the population and prevention of heart disease is clearly important so that more people can live longer, healthier lives. The development of data-driven methods for predicting heart disease can be used to improve prevention processes by advancing our understanding of the associated risk factors and identifying disease at early onset to allow for rapid intervention.

The Cleveland Heart Disease database ([cleve.mod](https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/cleve.mod)), available from the [UCI machine learning repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease), contains 14 variables related to heart disease diagnosis in 303 anonymous patients. The variable information is as follows:

- Age (years)
- Sex (male or female)
- Chest pain type (typical angina, atypical angina, non-anginal pain, asymptomatic)
- Resting blood pressure (mm Hg)
- Cholesterol (mg/dl)
- Fasting blood sugar < 120 mg/dl (true or false)
- Resting electrocardiographic results (normal, abnormal, hypertrophy)
- Max. heart rate (BPM)
- Exercise induced angina (true or false)
- Oldpeak - ST depression induced by exercise relative to rest (mm)
- Slope - the slope of the peak exercise ST segment (upsloping, flat, down sloping)
- Number of major vessels colored by fluoroscopy (0 to 3)
- Thalassemia blood disorder (normal, fixed defect, reversible defect)
- Presence of heart disease (yes or no)

This project aims to answer the question: can we use the Cleveland Heart Disease data set to develop a classification model to predict the presence of heart disease in a patient, and if so, what is the accuracy of the classification model?
