Titanic Survival Prediction Dashboard
A machine learning-powered dashboard that predicts passenger survival on the Titanic, combining exploratory data analysis with logistic regression and interactive deployment through a Flask web application.

Short Description / Purpose
This dashboard allows users to explore key Titanic passenger attributes and predict survival likelihood based on input features like age, class, fare, and gender. It was built to practice data science workflows from data cleaning and model training to real-world deployment.

Tech Stack
The project leverages the following technologies:

Python – Main programming language for data preprocessing, modeling, and app logic.

Pandas, NumPy, Seaborn, Matplotlib – Used for data analysis and visualization.

Scikit-learn – Logistic Regression model training and evaluation.

Flask – To deploy the model as a web application with a prediction form.

Ngrok – For tunneling the Flask app to create a publicly accessible URL.


📊 Data Source
Source: Titanic dataset from Kaggle 
Structure: Includes passenger details like:
Pclass, Sex, Age, SibSp, Parch, Fare, Embarked
Target label: Survived (0 = No, 1 = Yes)
Missing values handled for Age, Fare, and dropped Cabin.
Categorical values encoded (e.g., Sex: male = 0, female = 1).

🌟 Features / Highlights
• Business Problem
The Titanic disaster data is widely used in machine learning. A key challenge is building a model that predicts survival outcomes using incomplete and noisy historical data.

• Goal of the Dashboard
To create a streamlined ML pipeline and an intuitive interface that:
Predicts survival likelihood based on user inputs.
Offers insights into passenger profiles that impacted survival.
Helps learners and analysts understand classification workflows.

• Walkthrough of Key Visuals
Survival Distribution by Gender: Compare male vs. female survival likelihood.
Class vs. Survival: Understand how ticket class affected survival.
Fare vs. Survival: Track how fare price related to chances of survival.
Embarkation Point Influence: Visual correlation between port of embarkation and survival.
Age Distribution with Survival Overlay: Analyze survival rates across age groups.

• Prediction Web App (Flask + HTML)
Clean HTML interface for inputting features.
Model deployed using Flask and hosted via Ngrok.
Outputs instant survival prediction (0 = did not survive, 1 = survived).

• Business Impact & Insights
💡 Educational Value: Great tool for ML beginners to understand model pipelines.
⚙️ Deployable: Includes both backend logic and frontend UI for real-world use.
📈 Interactive: Users can explore how individual features affect survival.
