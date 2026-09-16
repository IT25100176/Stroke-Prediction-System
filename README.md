# Stroke Prediction Dataset

## Course Information

**Course:** IT2011 - Artificial Intelligence and Machine Learning

**Progress Review I:** Data Preprocessing and Exploratory Data Analysis (EDA)

---

## Dataset Information

**Dataset Name:** Stroke Prediction Dataset

The dataset contains 15,000 patient records and 22 attributes related to demographic, lifestyle, and health-related factors.

The objective of this project is to perform data cleaning, preprocessing, and exploratory data analysis (EDA) to prepare the dataset for future machine learning model development.

---

## Preprocessing Techniques Performed

1. Missing Value Handling
2. Encoding Categorical Variables
3. Outlier Detection and Analysis
4. Scaling and Normalization
5. Feature Selection
6. Feature Engineering

---

## Folder Structure

```text
Group_ID/
├── README.md
├── data/
│   ├── raw/
│   │   └── stroke_prediction_dataset.csv
│   └── external/
├── notebooks/
│   ├── IT25100174_MissingValueHandling.ipynb
│   ├── IT25100176_EncodingCategoricalVariables.ipynb
│   ├── IT25100158_OutlierDetection.ipynb
│   ├── IT25100183_ScalingAndNormalization.ipynb
│   ├── IT25100187_FeatureSelection.ipynb
│   ├── IT25100192_FeatureEngineering.ipynb
│   └── group_pipeline.ipynb
├── results/
│   ├── eda_visualizations/
│   ├── outputs/
│   └── logs/
```

---

## Individual Notebooks

### IT25100174_MissingValueHandling.ipynb

- Missing value identification
- Missing value treatment
- Verification of cleaned data

### IT25100176_EncodingCategoricalVariables.ipynb

- Identification of categorical attributes
- Label Encoding implementation
- Verification of encoded attributes

### IT25100158_OutlierDetection.ipynb

- Boxplot analysis
- IQR method
- Outlier detection results

### IT25100183_ScalingAndNormalization.ipynb

- Numerical feature scaling
- StandardScaler implementation
- Scaling verification

### IT25100187_FeatureSelection.ipynb

- Removal of irrelevant features
- Feature importance analysis
- Top feature visualization

### IT25100192_FeatureEngineering.ipynb

- Blood pressure feature extraction
- Creation of `Systolic_BP` and `Diastolic_BP`
- Feature engineering visualizations

---

## Group Pipeline

The `group_pipeline.ipynb` notebook contains:

- Dataset loading
- Exploratory Data Analysis (EDA)
- Missing value handling
- Encoding categorical variables
- Outlier detection
- Scaling and normalization
- Feature selection
- Feature engineering
- Preprocessing summary
- Overall conclusion

---

## How to Run

1. Open any notebook using Google Colab.
2. Upload `stroke_prediction_dataset.csv`.
3. Run all cells sequentially.
4. Review outputs and visualizations.

---

## Conclusion

The Stroke Prediction Dataset was successfully preprocessed through multiple data preparation techniques, including missing value handling, encoding, outlier detection, scaling, feature selection, and feature engineering.

The resulting dataset is cleaner, more structured, and better prepared for future machine learning and predictive analytics tasks.
