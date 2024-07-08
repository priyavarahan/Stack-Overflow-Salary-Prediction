# Stack-Overflow-Salary-Prediction
SALARY SIGHT: Tech Salary Prediction

Overview

This project utilizes data from the 2023 Stack Overflow survey, which includes feedback from 89,184 software engineers spanning 185 countries. Its main goals is to predict developer salaries.

Data Source

Survey Dataset: 2023 Stack Overflow Survey- https://survey.stackoverflow.co/

Respondents: 89,184 software engineers.

Geographic Scope: 185 countries.

How to Download and Run the Salary Sight Project

Prerequisites

Python 3.x: Ensure Python is installed on your system. You can download it from python.org. VS Code: Install Visual Studio Code from code.visualstudio.com. Git: Install Git from git-scm.com

Step 1: Clone the Repository Open a terminal or command prompt. Clone the project repository from GitHub : git clone REPO_URL

Step 2: Set Up and activate a Virtual Environment 1.Create a virtual environment: python -m venv venv

2.Activate the virtual environment: venv\Scripts\activate

On macOS/Linux:source venv/bin/activate

Step 3: Install Dependencies Install the required Python packages:pip install -r requirements.txt Access the repository: cd repository

Methodology - Compensation Prediction

Variables: YearsCodePro, CodingLanguageNum, OfficeStackAsyncNum, OpSysProfessionalNum, NEWCollabToolsNum, WorkExp, DatabaseNum, PlatformNum, OfficeStackSyncNum, Full-time Employment, Age_encoded, EdLevel_encoded, RemoteWork_encoded, Continent_encoded

Models Used: Utilize linear regression, SVM regression, RF regression and XGBoost models to predict software developers' salaries.

Performance Metrics: Root Mean Square Error (RMSE) ,Mean Squared Error(MSE) and R2

Key Insights

Salary Prediction : XG Boost model effectively predicts developer salaries, although with a Highest R^2 value
