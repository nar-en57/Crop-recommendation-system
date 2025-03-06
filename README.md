# Crop Recommendation System

This project builds a machine learning model to recommend suitable crops based on soil and climate data.

## Dataset

* Source: https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset
* Description: Dataset containing soil nutrient ratios, temperature, humidity, pH, and rainfall.

## Methodology

1.  Data loading and preprocessing with Pandas.
2.  Exploratory data analysis (EDA).
3.  Feature and target variable separation.
4.  Data splitting into training and testing sets.
5.  Model training using Random Forest Classifier.
6.  Model evaluation (accuracy, classification report).
7.  Feature importance analysis.
8.  Prediction examples.

## Key Findings

* The Random Forest Classifier achieved high accuracy.
* Feature importance analysis revealed key factors for crop selection.
* The model can provide useful crop recommendations.

## Visualizations

* **Distribution Plots:** Show the distribution of each feature, providing insights into their spread and potential outliers.
  
![image](https://github.com/user-attachments/assets/7deb4d63-fd77-49c1-82fa-0462ea8d1fbe)
![image](https://github.com/user-attachments/assets/935a5e8c-f926-4027-8e3d-390a00e2635b)
![image](https://github.com/user-attachments/assets/cd7d5277-75db-4196-8bad-a96a807d3a15)
![image](https://github.com/user-attachments/assets/5c47f29a-2fc0-40f7-a560-8689bb55bdc4)
![image](https://github.com/user-attachments/assets/2dd37a7d-7f75-4f54-8ebc-776c26711b06)
![image](https://github.com/user-attachments/assets/0aa8e81f-f00e-4e29-a18b-63bc3c67fca4)
![image](https://github.com/user-attachments/assets/b7426a0f-300a-40bd-b888-206b9d5e3e6b)

* **Correlation Heatmap:** Visualizes the correlation matrix of numeric features, highlighting relationships between variables.
  
![image](https://github.com/user-attachments/assets/ec036ca2-a40e-401c-9434-3342271b996f)

* **Feature Importance Bar Chart:** Displays the importance of each feature in the model's predictions, indicating the key factors influencing crop selection.
  
![image](https://github.com/user-attachments/assets/d25e2cc1-3cd9-4936-8b5e-a70df4e15c8c)

## Last Recommendation Screenshot

![image](https://github.com/user-attachments/assets/0d4d030f-686e-498a-aee2-cde72669ea44)
* This screenshot shows the last prediction made by the model.

## Libraries Used

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Instructions

1.  Clone the repository.
2.  Create and activate a virtual environment.
3.  Install dependencies: `pip install -r requirements.txt`
4.  Run the Jupyter Notebook: `jupyter notebook crop_recommendation.ipynb`

## Conclusion

This project successfully developed a crop recommendation system. The model can assist farmers in making informed decisions. Further work could include more data, model tuning, and deployment.
