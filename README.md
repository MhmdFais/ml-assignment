# ML Assignment

## Data set selected - [Adult Census Income](https://www.kaggle.com/datasets/uciml/adult-census-income?resource=download)

## Steps Followed

### Data Preprocessing

For this preprocessing part, fllowing steps have been done

1. Handle Missing Values:

   - Replace '?' entries (e.g., in workclass, occupation, native-country) with NaN
   - Impute missing categorical values with the mode of their respective columns or treat them as a separate category

2. Convert Categorical to Numerical

   - Convert categorical columns into numerical format using Label Encoding or One-Hot Encoding

3. Feature Scaling

   - Standardize numerical features to improve model performance

4. Split Dataset

### Choosing a ML model

Since this is a binary classification problem we can use the following modles

- Logistic Regression : Simple, interpretable, Works well when data is linearly separable
- Decision Tree : Handles categorical and numerical data, Prone to overfitting
- Random Forest : Reduces overfitting, Performs well on structured data
- Gradient Boosting (XGBoost, LightGBM, CatBoost) : Best for accuracy but computationally expensive
- Support Vector Machine (SVM) : Works well in small datasets
- Neural Networks (Deep Learning) : Honestly an overkill for this project

Above are the models we can use for this project and we decided to select **Random Forest** because

- It works well with structured data, avoids overfitting

### Showing Results

As shown in the program there many factors that impact the income, But we have only chosen to plot charts
for the following three factors

- Capital Gain
- Relationship Status
- Age
