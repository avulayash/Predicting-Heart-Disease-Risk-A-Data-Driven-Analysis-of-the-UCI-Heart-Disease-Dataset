🧾 Column Overview:
Numerical Columns: id, age, trestbps (resting blood pressure), chol (cholesterol), thalch (max heart rate), oldpeak (ST depression), ca (number of major vessels), num (target variable: heart disease presence)

Categorical Columns: sex, dataset, cp (chest pain type), fbs (fasting blood sugar), restecg (resting ECG), exang (exercise-induced angina), slope (slope of ST segment), thal

📉 Missing Data:
trestbps, chol, fbs, restecg, thalch, exang, oldpeak, slope, ca, and thal all have missing values.

Columns with substantial missing data:

slope (only 611 non-null)

ca (only 309 non-null)

thal (only 434 non-null)

📊 Target Variable (num):
Represents the presence of heart disease.

Likely encoded as:

0: No disease

1-4: Presence of disease (severity?)

📌 Notable Observations:
sex is mostly "Male" (~79%)

cp is mostly "asymptomatic"

fbs has a high imbalance (False dominates)
