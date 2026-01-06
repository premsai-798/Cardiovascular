
# Cardiovascular Disease Risk Prediction

This project focuses on leveraging machine learning algorithms to detect early warning signs of cardiovascular events, such as heart attacks, based on clinical and lifestyle data. It aims to identify the most relevant factors contributing to cardiovascular risk, comparing the performance of ensemble methods (e.g., Random Forest, XGBoost) with simpler models. The project also includes an analysis of the model’s interpretability using SHAP values, as well as addressing the challenges posed by class imbalance in predictive modeling.

## **Research Questions**
1. Can machine learning models accurately predict cardiovascular events (such as heart attacks), and how do ensemble methods compare to simpler models?
2. What lifestyle and clinical factors most significantly influence cardiovascular risk, and can SHAP analysis help interpret these findings?
3. How can predictive models be designed to address fairness and bias, especially in dealing with imbalanced datasets?

## **Dataset Details**
- **Name:** Cardiovascular Disease Risk Prediction Dataset
- **Source:** Mendeley Data – Cardiovascular Disease Risk Dataset
- **Contributors:** The dataset consists of anonymized clinical and lifestyle data, published by Elsevier, to aid in research on cardiovascular risk and early detection.

## **Libraries Used**
- **pandas** for data manipulation
- **matplotlib** and **seaborn** for data visualization
- **numpy** for numerical operations
- **scikit-learn** for machine learning models and metrics
- **SHAP** for model interpretability and explainability

## **Steps Performed in the Notebook**
1. **Importing Libraries:** Essential libraries are imported for data processing, model building, and evaluation.
2. **Reading the Dataset:** The dataset is loaded from an Excel file, and basic information about the data is displayed.
3. **Exploratory Data Analysis (EDA):** The dataset is explored using statistical methods and visualizations to understand the distribution of variables and relationships.
4. **Handling Missing Values:** Missing data is handled by filling numerical columns with the median and categorical columns with the mode.
5. **Feature Engineering and Scaling:** Features are prepared for model training using scaling techniques to standardize the data.
6. **Model Training:** Multiple machine learning models, including ensemble methods like Random Forest and XGBoost, are trained and evaluated.
7. **Model Evaluation:** Evaluation metrics such as accuracy, precision, recall, and F1-score are computed for model performance.
8. **SHAP Analysis:** SHAP values are used to interpret the model results and understand the most significant features influencing cardiovascular risk.

## **How to Run the Notebook**
1. Clone the repository to your local machine.
2. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn numpy scikit-learn shap
   ```
3. Download the dataset (Cardiovascular Disease Risk Dataset) and upload it in the appropriate location or use the dataset from the provided source.
4. Open the notebook in Jupyter Notebook or Google Colab.
5. Execute all the cells to perform data analysis and model training.

## **Results**
This project aims to predict cardiovascular risk using machine learning models and to identify the key lifestyle and clinical factors that influence the risk. The models are evaluated for their performance, and SHAP analysis helps interpret the significance of features in the final predictions.

## **Contributions**
Feel free to contribute by:
- Improving the model’s performance.
- Adding new machine learning algorithms.
- Enhancing feature engineering and preprocessing steps.

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
