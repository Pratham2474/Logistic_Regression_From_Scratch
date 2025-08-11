# Logistic_Reg_From_Scratch
![log1](https://user-images.githubusercontent.com/67974590/195117996-c43bb372-2219-49cd-85f7-1856301c5df3.jpeg)
![log2](https://user-images.githubusercontent.com/67974590/195118016-c208962d-e290-46bf-a3e0-421e5fad1778.jpeg)
🚢 Titanic Survival Prediction
A comprehensive machine learning project using the famous Titanic dataset to predict passenger survival. This project walks through the full data science pipeline—from data cleaning and exploratory analysis to feature engineering and model evaluation—demonstrating how structured data can be transformed into actionable insights.

📘 Project Overview
The Titanic dataset is a classic binary classification problem where the goal is to predict whether a passenger survived the disaster based on features like age, gender, class, and fare. This project emphasizes:
- Data preprocessing and handling missing values
- Feature engineering and encoding
- Model training and hyperparameter tuning
- Evaluation using accuracy, precision, recall, and ROC curves

📂 Dataset Description
| Feature | Description | 
| PassengerId | Unique ID | 
| Survived | Target variable (0 = No, 1 = Yes) | 
| Pclass | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) | 
| Name, Sex, Age | Demographics | 
| SibSp, Parch | Family aboard | 
| Ticket, Fare | Travel details | 
| Cabin, Embarked | Location info | 



🧪 Data Preprocessing
- Handling missing values (Age, Cabin, Embarked)
- Encoding categorical variables (Sex, Embarked)
- Feature scaling (Fare, Age)
- Creating new features:
- FamilySize = SibSp + Parch + 1
- IsAlone = 1 if FamilySize == 1
- Title extraction from Name

🧠 Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gradient Boosting (optional)
Each model is evaluated using cross-validation and compared using metrics like accuracy, F1-score, and ROC-AUC.

📊 Project Workflow
- Exploratory Data Analysis (EDA)
- Survival rates by gender, class, age
- Correlation heatmaps
- Distribution plots
- Feature Engineering
- Categorical encoding
- Derived features (e.g., Title, IsAlone)
- Model Training
- Train-test split
- Hyperparameter tuning (GridSearchCV)
- Evaluation
- Confusion matrix
- ROC curve
- Feature importance

🚀 Getting Started
📦 Requirements
- Python 3.8+
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
▶️ Run the Project

# Navigate to the project folder
cd Titanic_Survival_Prediction

# Run the script
python titanic_model.py



📈 Results
- Achieved up to ~82% accuracy using Random Forest and Gradient Boosting
- Feature importance shows Sex, Pclass, and Title as key predictors
- ROC curves and confusion matrices included for model comparison

🛠️ Future Enhancements
- Ensemble stacking for improved performance
- Deployment as a web app using Streamlit or Flask
- Integration with automated pipelines (e.g., MLflow)

🤝 Contributing
Pull requests are welcome! Feel free to suggest new features, improvements, or visualizations.
