# Achieving highest accuracy with different ML Algorithms

### Project Overview:
This project involves building a machine learning model to predict the adaptivity level of students in online education. The adaptivity level is the target variable, and it represents how well students adapt to online learning environments.

### Dataset Description:

This dataset appears to contain information about students and their characteristics, as well as a target variable representing their adaptivity level. Here's a breakdown of each feature:

1. **Gender**: This feature represents the gender of the student, with possible values being "Boy" or "Girl".
2. **Age**: The age group of the student, categorized into ranges such as "21-25" or "16-20".
3. **Education Level**: Indicates the educational level of the student, such as "University", "College", or "School".
4. **Institution Type**: Specifies the type of institution the student attends, with options like "Government" or "Non Government".
5. **IT Student**: Indicates whether the student is an IT student or not, with values "Yes" or "No".
6. **Location**: Represents the location of the student, typically denoted as "Yes" but lacks clarity.
7. **Load-shedding**: Indicates the level of load-shedding experienced by the student, categorized into "Low" or "High".
8. **Financial Condition**: Represents the financial condition of the student, with categories like "Mid" or "Poor".
9. **Internet Type**: Specifies the type of internet connection used by the student, such as "Wifi" or "Mobile Data".
10. **Network Type**: Indicates the type of network used by the student, such as "4G" or "3G".
11. **Class Duration**: Represents the duration of the class attended by the student, categorized into ranges like "3-6" or "1-3".
12. **Self Lms**: Indicates whether the student uses a self-learning management system, with values "Yes" or "No".
13. **Device**: Specifies the device used by the student, such as "Tab" or "Mobile".
14. **Adaptivity Level**: This is the target variable representing the adaptivity level of the student.


### Data Preprocessing:
- **Encoding Categorical Variables**: Categorical variables are encoded using one-hot encoding to convert them into a numerical format suitable for machine learning models.
- **Standardization**: Numerical features are standardized using `StandardScaler` to scale them to have a mean of 0 and a standard deviation of 1.

### Model Building and Evaluation:
- Several classification algorithms are trained and evaluated on the dataset, including Random Forest, Logistic Regression, Support Vector Machine (SVM), Decision Tree, and Gradient Boosting.
- The accuracy of each model is calculated using the `accuracy_score` metric.
- Random Forest achieved the highest accuracy among all models.

### Conclusion:
- Based on the evaluation results, the Random Forest algorithm is selected as the final model for predicting the adaptivity level of students in online education.

