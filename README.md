## Car Purchase Prediction Analysis
### Project Overview
This data science project investigates factors influencing car purchases using machine learning techniques. The goal is to predict whether a potential customer will purchase a car based on demographic and financial attributes.
Dataset Description

### Source: Car purchase dataset
Size: 1000 records
Features:

Gender
Age
Annual Salary


Target Variable: Purchase (0 = No Purchase, 1 = Purchase)

### Data Preprocessing

Label encoded categorical variables
Performed feature selection using Chi-square test
Selected most relevant features: Age and Annual Salary
Standardized features using StandardScaler

### Machine Learning Models Explored

#### Logistic Regression

Accuracy: 86.5%
F1 Score: 0.816


#### K-Nearest Neighbors

Best Parameters:

5 neighbors
Uniform weights


Accuracy: 93.5%
F1 Score: 0.915


#### Random Forest Classifier

Best Parameters:

50 estimators
Minimum samples split: 8


Accuracy: 91.5%
F1 Score: 0.889


#### XGBoost Classifier

Best Parameters:

300 estimators
Learning rate: 0.01


Accuracy: 90.5%
F1 Score: 0.879


#### Support Vector Classifier

Best Parameters:

C: 10
Kernel: RBF
Degree: 2


Accuracy: 93%
F1 Score: 0.909



### Key Insights

K-Nearest Neighbors performed best with 93.5% accuracy
Feature Importance:

First Feature (likely Age): 0.287 importance
Second Feature (likely Annual Salary): 0.213 importance



### Visualization Highlights

Gender distribution analysis
Age distribution plot
Salary distribution visualization
Purchases by gender breakdown

### Technologies Used

Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
XGBoost

Potential Business Applications
This model could help:

Target marketing efforts
Predict potential car buyers
Understand purchasing behavior correlations

### Future Work

Collect more diverse dataset
Experiment with more advanced feature engineering
Try ensemble methods
Incorporate more demographic variables

### How to Reproduce

Clone the repository
Install required dependencies
Run the Jupyter notebook
Explore data and models

Limitations

Relatively small dataset
Limited feature set
Potential bias in data collection

License
**None**
Authors
Melchizedek Ackah-Blay
