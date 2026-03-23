# Daily Water Intake Analysis — Fresh Data Mining Project

## Dataset
- **File:** dataset/daily_water_intake_1000.xlsx
- **CSV:** dataset/daily_water_intake_1000.csv
- **Source:** Kaggle — Daily Water Intake & Hydration Patterns Dataset
- **URL:** https://www.kaggle.com/datasets/sonalshinde123/daily-water-intake-and-hydration-patterns-dataset
- **Records:** 1000 individuals
- **Features:** 16 columns
- **Target:** Hydration_Status (Adequate / Inadequate)

## How to Run in Google Colab
1. Go to colab.research.google.com
2. File → Upload Notebook → select Daily_Water_Intake_Analysis_1000.ipynb
3. Runtime → Run All
4. When prompted → Upload daily_water_intake_1000.xlsx
5. All 12 graphs generate automatically!

## Project Contents
- Daily_Water_Intake_Analysis_1000.ipynb  ← Main notebook
- dataset/daily_water_intake_1000.xlsx    ← Excel dataset (show to faculty)
- dataset/daily_water_intake_1000.csv     ← CSV dataset
- output_graphs/                          ← Graphs saved here after running

## Techniques Used
1. EDA — 12 professional graphs
2. Classification — Logistic Regression, Decision Tree, Random Forest, KNN, SVM
3. K-Means Clustering (Elbow Method, k=3)
4. Apriori Association Rule Mining
5. ROC Curve — All 5 models
6. Confusion Matrix + Feature Importance

## Dataset Columns
| Column | Description |
|--------|-------------|
| UserID | Unique ID (U0001 to U1000) |
| Age | Age 18-64 years |
| Gender | Male / Female |
| Weight_kg | Body weight in kg |
| Height_cm | Height in cm |
| Activity_Level | Low / Moderate / High |
| Climate | Cold / Temperate / Hot |
| Occupation | Type of work |
| Daily_Water_Intake_Liters | Actual intake per day |
| Recommended_Intake_Liters | WHO recommended amount |
| Health_Status | Poor / Good / Excellent |
| Sleep_Hours | Daily sleep hours |
| Coffee_Cups_Per_Day | Coffee consumed daily |
| Alcohol_Units_Per_Day | Alcohol consumed daily |
| BMI | Body Mass Index |
| Hydration_Status | TARGET: Adequate / Inadequate |

## GitHub
github.com/somasanthosh1/Daily-Water-Intake-Analysis
