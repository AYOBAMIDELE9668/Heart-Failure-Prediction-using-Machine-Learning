# Heart-Failure-Prediction-using-Machine-Learning
This project leverages the power of machine learning to predict **heart failure** based on a range of clinical parameters. With cardiovascular diseases being the **leading cause of death globally**, this model aims to provide early insights into heart disease risk, enabling timely diagnosis and intervention.
Cardiovascular diseases (CVDs) account for roughly **31% of global deaths** — that’s nearly 18 million lives lost each year. Many of these deaths are preventable with early detection.

This project attempts to automate the identification of heart failure **risk** using patient data and predictive modeling, helping medical professionals take proactive action.

## Objectives

- Predict whether a patient is likely to suffer from **heart disease** (1) or not (0).
- Use supervised learning for **binary classification**.
- Evaluate performance using cross-validation and multiple machine learning models.

## Dataset Description

The dataset used contains the following features:

| Feature | Description |
|--------|-------------|
| `Age` | Age of the patient |
| `Sex` | Biological sex (Male/Female) |
| `ChestPainType` | Type of chest pain (TA, ATA, NAP, ASY) |
| `RestingBP` | Resting blood pressure (mm Hg) |
| `Cholesterol` | Serum cholesterol (mg/dl) |
| `FastingBS` | Fasting blood sugar > 120 mg/dl (1 = True; 0 = False) |
| `RestingECG` | ECG results (Normal, ST, LVH) |
| `MaxHR` | Maximum heart rate achieved |
| `ExerciseAngina` | Exercise-induced angina (Y/N) |
| `Oldpeak` | ST depression induced by exercise |
| `ST_Slope` | Slope of the peak ST segment (Up, Flat, Down) |
| `HeartDisease` | Target variable (1 = Heart disease, 0 = No heart disease) |

##  Exploratory Data Analysis (EDA)

We conducted thorough EDA to understand:

- Distribution of continuous features (like Age, Cholesterol, MaxHR)
- Categorical variable patterns (like ChestPainType, ST_Slope)
- Correlations between features and target
- Outlier detection and data imbalances

Visualization libraries like **Seaborn** and **Matplotlib** were used extensively.

##  Feature Engineering & Preprocessing

Steps taken:

- One-hot encoding for categorical features
- Scaling numerical features using StandardScaler
- Handling class imbalance
- Feature importance analysis using statistical tests and model-based selectors
##  Modeling Approach

Multiple models were trained and compared:

- Logistic Regression
- Random Forest
- XGBoost
- LightGBM
- CatBoost

### Evaluation Strategy

- Used **cross-validation** (CV score ~90.5%)
- Measured accuracy, precision, recall, F1-score
- Confusion matrix for model performance understanding

##  Results

The top-performing models (e.g., LightGBM and XGBoost) gave a **cross-validation accuracy of ~90.5%**, indicating strong predictive power even with limited data.

##  What You'll Learn From This Project

- Real-world **binary classification** problem solving
- Best practices in **EDA**, **feature scaling**, and **model selection**
- Visual storytelling with **data visualizations**
- Practical deployment-ready modeling pipeline
