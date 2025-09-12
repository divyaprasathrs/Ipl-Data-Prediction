IPL Match Winner Prediction 🏏

This project focuses on predicting the winner of an Indian Premier League (IPL) match using historical match data. By analyzing factors like teams, toss outcomes, venue, and player performance, the project aims to build machine learning models that provide accurate match winner predictions.

📊 Dataset Overview

The IPL dataset contains detailed match information, including:

Season: Year of the IPL season

City: City where the match was played

Date: Date of the match

Team1 & Team2: Teams playing in the match

Toss_winner & Toss_decision: Team winning the toss and their decision (bat/bowl)

Result & Winner: Outcome of the match

Win_by_runs & Win_by_wickets: Margin of victory

Player_of_match: Awarded player for best performance

Venue: Stadium where the match was held

Umpires: Officials overseeing the match

✅ Project Tasks 🔧 Data Cleaning and Preprocessing

Handle missing values and null entries

Encode categorical variables like team names and toss decisions

Remove outliers and inconsistent data points

📈 Exploratory Data Analysis (EDA)

Analyze distributions of matches, team wins, and toss outcomes

Explore relationships between features and match results

Visualize patterns using bar charts, pie charts, and histograms

🏗 Model Training & Evaluation

Train multiple machine learning models:

Logistic Regression, SVM, KNN, Decision Tree, Random Forest, XGBoost

Evaluate models using Accuracy, Precision, Recall, and F1-score

Select the best-performing model and tune hyperparameters

📊 Visualization

Plot team performance trends and venue-wise win statistics

Visualize the effect of toss decisions on match outcomes

📌 Insights & Interpretation

Certain teams and venues have higher win probabilities

Toss decisions can influence match results

XGBoost consistently provides the highest prediction accuracy

🛠 Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost)

Jupyter Notebook

Pickle (for saving the trained model)

GitHub for version control and collaboration


This project is licensed under the MIT License.
