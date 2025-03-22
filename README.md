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
