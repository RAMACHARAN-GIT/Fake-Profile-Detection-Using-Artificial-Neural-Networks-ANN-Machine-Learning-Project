**PROJECT TITLE**
**Fake Profile Detection Using Artificial Neural Networks (ANN)**

**Overview**
This project focuses on detecting fake social media profiles using Machine Learning and Deep Learning techniques. The model analyzes profile characteristics such as username patterns, followers, following count, profile picture presence, and other metadata to classify profiles as Fake or Real.
The project includes data preprocessing, exploratory data analysis (EDA), feature selection, model training, and prediction using an Artificial Neural Network.

**Problem Statement**
Fake accounts on social media platforms are widely used for spam, scams, misinformation, and bot activity. The goal of this project is to build a machine learning model that can automatically classify social media profiles as fake or genuine based on profile attributes.

**Dataset**
The dataset contains multiple profile-based features such as:
Profile picture availability, 
Username characteristics, 
Full name characteristics, 
Number of followers, 
Number of followings,
Number of posts,
Username numeric ratio,
Full name numeric ratio,
External URL presence,
Bio length,
Account privacy,
Target Variable is:
Fake
1 → Fake Profile
0 → Real Profile

**Technologies Used**
Programming	Python,
Data Analysis	Pandas, NumPy,
Visualization	Matplotlib, Seaborn,
Machine Learning	Scikit-learn,
Machine Learning models Logistic Regression, DecisionTreeClassifier, XGBoost,
Deep Learning	TensorFlow / Keras,
Model	Artificial Neural Network,
Development	Jupyter Notebook

**Project Workflow**
Data Collection,
Data Cleaning,
Exploratory Data Analysis (EDA),
Feature Selection,
Data Preprocessing,
Model Building using ANN,
Model Training,
Model Evaluation,
Prediction on new data,

**Model Architecture**
Artificial Neural Network includes:
Input Layer,
Hidden Layers with ReLU activation,
Output Layer with Sigmoid activation,
Used for Binary Classification (Fake vs Real Profiles).

**Model Evaluation Metrics**
Accuracy,
Confusion Matrix

**Key Insights**
Username patterns and numeric ratios are strong indicators of fake profiles.
Accounts with abnormal follower/following ratios show higher probability of being fake.
Neural Networks improve classification performance compared to simple models.

**Future Improvements**
Deploy the model using Streamlit Web Application,
Improve accuracy using ensemble models,
Collect larger datasets,
Integrate with social media API,

**Skills Demonstrated**
Machine Learning,
Deep Learning,
Artificial Neural Networks,
Data Analysis,
Feature Engineering,
Exploratory Data Analysis (EDA),
Data Visualization,
Binary Classification,
TensorFlow,
Scikit-learn,
Python Programming,
Model Evaluation
