# Bharat-Internship - Machine Learning Projects worked on as a Data Science Intern

## Project Title: Titanic Survival Prediction  

This project delved into predicting passenger survival on the Titanic using a supervised machine learning algorithm - Logistic Regression. Logistic Regression is used because it is good for binary classification problems and will help provide a clear understanding of the relationship between the features and the survival outcome.  

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
- Survival Rate by Gender: Females had a significantly higher survival rate compared to males.
- Survival Rate by Passenger Class: Passengers in first class had the highest survival rate, followed by second class, with third class having the lowest survival rate.
- Age Distribution by Survival: Younger passengers had higher survival rates, with a noticeable peak in survival for children.
                                The age distribution of those who did not survive is more spread out across all ages.
- Fare Distribution by Survival: Passengers who paid higher fares tended to have higher survival rates, which correlates with the higher survival rate in first-class passengers.
- Correlation Matrix: There is a positive correlation between the Fare and Survived variables.
                      A negative correlation exists between the Pclass and Survived variables (lower class number, i.e., first class, is associated with higher survival).
                      The Sex variable also shows a significant negative correlation, indicating that being male is negatively associated with survival.

A web application was developed using Flask and a pre-trained machine learning model to predict Titanic survival. The application collects passenger details through a user-friendly HTML form and returns survival predictions instantly. I used ngrok to make the application accessible online, allowing real-time interaction. 
This project showcases the power of integrating machine learning with web development for practical applications.
