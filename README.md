# Diabetes Prediction Project

This project aims to predict the onset of diabetes based on certain diagnostic measures using machine learning algorithms.

## Dataset

The dataset used for this project is the Pima Indians Diabetes Database, originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The dataset contains diagnostic measures for 768 patients, including:

- Number of times pregnant
- Plasma glucose concentration
- Diastolic blood pressure
- Triceps skin fold thickness
- 2-Hour serum insulin
- Body mass index (BMI)
- Diabetes pedigree function
- Age

## Methodology

The project follows these steps:

1. **Importing Required Libraries:** Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.
2. **Data Loading:** Loading the dataset using Pandas.
3. **Data Preprocessing:**
    - Checking for missing values.
    - Exploring the correlation between features.
    - Visualizing the correlation using a heatmap.
4. **Model Training:**
    - Splitting the data into training and testing sets.
    - Training a Logistic Regression model.
5. **Model Evaluation:** 
    - Making predictions on the test data.
    - Calculating the accuracy of the model.

## Results

The Logistic Regression model achieved an accuracy of approximately 80% on the test dataset.

## Conclusion

In this project, we successfully developed a machine learning model to predict the onset of diabetes based on diagnostic measures. The model's accuracy indicates its potential to assist healthcare providers in identifying individuals at risk of diabetes, allowing for early intervention and better disease management.

