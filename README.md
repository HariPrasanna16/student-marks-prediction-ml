Student Marks Prediction using Machine Learning

Problem Statement
Predict a student’s exam score based on the number of hours studied using a Machine Learning regression model.

Dataset
The dataset contains two numerical columns:
Hours – Number of hours studied
Scores – Marks obtained
The data is clean and contains no missing values.

Approach
Performed basic data exploration and visualization
Observed a linear relationship between hours studied and scores
Split data into training and testing sets (80/20)
Applied Linear Regression (Supervised Learning)
Evaluated model performance using MAE and R² score

Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn

Model Evaluation
Mean Absolute Error (MAE): 3.37
R² Score: 0.97

Interpretation:
On average, the model’s predictions differ from actual marks by approximately 3–4 marks, which is reasonable for a single-feature regression model.

Visualization
Scatter plot showing relationship between study hours and scores
Regression line comparing actual vs predicted values

Key Learnings
Importance of data visualization before model building
Understanding how Linear Regression works in practic
Why train-test split is essential for generalization
Role of evaluation metrics in measuring model performance
Limitations of using a single feature for prediction

Future Improvements
Add more features such as attendance or previous scores
Try Polynomial Regression
Apply cross-validation
Convert the model into a simple web app using Streamlit

Conclusion
This project focuses on building strong Machine Learning fundamentals using a simple and interpretable regression model. It serves as a foundation for more advanced ML projects in the future.
