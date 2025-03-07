# Customer Segmentation

## Overview
This project focuses on customer segmentation using machine learning techniques. It involves preprocessing customer data, encoding categorical variables, and building classification models to segment customers into different groups.

## Dataset
The dataset is sourced from Kaggle: [Customer Segmentation Dataset](https://www.kaggle.com/datasets/abisheksudarshan/customer-segmentation/data). It contains both categorical and numerical features, providing valuable insights into customer behavior.

## Steps Involved
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Standardizing numerical features
2. **Exploratory Data Analysis (EDA)**
   - Visualizing distributions and relationships
   - Checking for multicollinearity using Variance Inflation Factor (VIF)
3. **Model Building**
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Naïve Bayes
   - Linear Discriminant Analysis (LDA)
4. **Model Evaluation**
   - Classification Report
   - Confusion Matrix
   - Precision, Recall, and F1-score
   - ROC-AUC Score

## Visualizations
Graphs generated during data analysis and modeling are stored in the `visualizations/` directory.

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```

## Conclusion
This project demonstrates customer segmentation using machine learning models. The models' performance is evaluated using standard metrics, and insights are derived from the data to aid business decisions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.
