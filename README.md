# Bharat-Internship - Machine Learning Projects worked on as a Data Science Intern

## Project Title: Titanic Survival Prediction  

This project delved into predicting passenger survival on the Titanic using a supervised machine learning algorithm - Logistic Regression. Logistic Regression because it is good for binary classification problems. It will provide a clear understanding of the relationship between the features and the survival outcome.  

Here's a brief overview of the process and insights:

1. Data Preprocessing and Cleaning:
- Cleaned the dataset by handling missing values in columns like `Age`, `Cabin`, and `Embarked`.- Dropped the 'Cabin' column and filled the null values in the 'Embarked' and 'Age' column with the mode and mean values.
- Converted categorical variables such as `Sex` and `Embarked` into numerical formats using a dictionary.

2. Feature Engineering:
- Created new features such as `FamilySize` (combining `SibSp` and `Parch`) and `Title` (extracted from the `Name` column).
- Selected significant features that contribute to survival prediction including `Pclass`, `Sex`, `Age`, `Fare`, `Embarked`, and `FamilySize`.

3. Model Building:
- Applied the algorithm - Logistic Regression
- Fine-tuned hyperparameters to improve model performance.

4. Model Evaluation:
- Used cross-validation to ensure the robustness of the models.
- Evaluated model performance with metrics such as accuracy, precision, recall, and F1-score.

5. Insights Derived:
- The male gender had a higher survival rate compared to the female.
- Passengers in upper class (1st class) were more likely to survive.
- Family size had a significant impact on survival, with smaller families having better chances.
- Fare also played a crucial role, with higher fares correlating with higher survival rates.

The details of this prediction was hosted [here](https://a9f2-34-145-128-248.ngrok-free.app/) on ngrok using an html file which makes the input process easier for users.
This project has been a fantastic learning experience, and I'm excited to continue exploring and growing in the field of data science.
