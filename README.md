Student Academic Performance Prediction (Multilinear Regression)

Dataset
Source: Kaggle (Public)
Link: https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

Target Variable
Final Exam Score – calculated as the average of Math, Reading, and Writing scores.

The student performance dataset was loaded from Kaggle to predict academic performance based on academic, behavioral, and lifestyle factors using Multilinear Regression. Input features such as study hours per day, attendance percentage, parental education level, test preparation course, and sleep hours were selected. Categorical features were encoded into numerical format, and missing values were handled using suitable imputation techniques. Feature scaling was applied using StandardScaler to normalize the data. The dataset was split into training and testing sets, and a Multilinear Regression model was trained to predict final exam scores. Model performance was evaluated using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² score. Regression coefficients were analyzed to interpret the influence of each feature on student performance, and model optimization was performed using feature elimination, Ridge Regression, and Lasso Regression. Visualizations such as predicted vs actual exam scores, coefficient magnitude comparison, and residual distribution plots were generated to assess model accuracy.

Vehicle Fuel Efficiency Prediction (Polynomial Regression)

Dataset
Source: Kaggle (Public)
Link: https://www.kaggle.com/datasets/uciml/autompg-dataset

Target Variable
Miles Per Gallon (MPG)

The Auto MPG dataset was obtained from Kaggle to predict vehicle fuel efficiency using Polynomial Regression. Engine horsepower was selected as the independent variable to model the non-linear relationship with fuel efficiency. Missing values were handled using appropriate imputation methods, and feature scaling was applied using StandardScaler. Polynomial features were generated for degrees 2, 3, and 4, and the dataset was split into training and testing sets. Polynomial Regression models were trained for each degree and used to predict MPG values. Model performance was evaluated using MSE, RMSE, and R² score, and comparisons were made across polynomial degrees to identify underfitting and overfitting. To control model complexity and improve generalization, Ridge Regression was applied. Visualizations including polynomial curve fitting, training vs testing error comparison, and overfitting and underfitting demonstrations were used for analysis.


# 24ADI003_24BAD022_EXP-03
