🌍 Climate Change Social Media Engagement Analysis

📊 A Data Science & NLP Project using NASA Climate Dataset
____________________________________________________________________________________________________________________________________________________________________________________________________________________
📌 Project Overview

Climate change awareness heavily relies on social media platforms to reach the public. This project analyzes climate-related social media posts and predicts user engagement (likes) using Natural Language Processing (NLP) and Machine Learning techniques.
The goal is to understand how textual content and interaction metrics influence engagement.
____________________________________________________________________________________________________________________________________________________________________________________________________________________
🎯 Objectives

Analyze climate-related social media posts
Clean and preprocess textual data
Convert text into numerical features using TF-IDF
Build a regression model to predict likes
Evaluate model performance
Visualize actual vs predicted engagement

____________________________________________________________________________________________________________________________________________________________________________________________________________________
📂 Dataset Description

Source: NASA Climate-related Social Media Data

Column Name                  Description

date                         Date of the post
profileName                  Posting profile
text                         Climate-related post content
likesCount                   Number of likes (Target)
commentsCount                Number of comments

Total Records: 522
Data Type: Text + Numerical
____________________________________________________________________________________________________________________________________________________________________________________________________________________
🧠 Problem Type

🔹 Regression Problem
Predicting the number of likes a post receives.
____________________________________________________________________________________________________________________________________________________________________________________________________________________
🛠️ Technologies Used

Python 🐍
Pandas & NumPy
Matplotlib & Seaborn
Scikit-learn
NLTK
Jupyter Notebook
____________________________________________________________________________________________________________________________________________________________________________________________________________________
⚙️ Project Workflow

1️⃣ Data Loading
2️⃣ Data Cleaning
3️⃣ Text Preprocessing
4️⃣ Feature Engineering (TF-IDF)
5️⃣ Train-Test Split
6️⃣ Model Training
7️⃣ Model Evaluation
8️⃣ Visualization
____________________________________________________________________________________________________________________________________________________________________________________________________________________
🤖 Machine Learning Model

Model Used: Linear Regression

Why Linear Regression?

-Simple & interpretable
-Suitable for regression tasks
-Beginner-friendly and internship-appropriate
____________________________________________________________________________________________________________________________________________________________________________________________________________________
📈 Evaluation Metrics

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score

These metrics help measure how close predicted likes are to actual likes.
____________________________________________________________________________________________________________________________________________________________________________________________________________________
📊 Results

The model successfully captured general engagement trends
Predictions were accurate for moderate engagement posts
Performance can be improved using advanced models
____________________________________________________________________________________________________________________________________________________________________________________________________________________
🔮 Future Enhancements

Use advanced models like Random Forest or XGBoost
Perform sentiment analysis
Convert into classification (High vs Low engagement)
Analyze time-based engagement trends
Include hashtag and reach-based features
____________________________________________________________________________________________________________________________________________________________________________________________________________________
📁 Project Structure
|
├── climate_nasa.csv
├── climate_engagement_model.pkl
├── climate_analysis.ipynb
├── README.md
____________________________________________________________________________________________________________________________________________________________________________________________________________________
🎓 Learning Outcomes

Hands-on experience with NLP preprocessing
Feature extraction using TF-IDF
Building and evaluating ML models
Working with real-world climate data
____________________________________________________________________________________________________________________________________________________________________________________________________________________
📝 Conclusion
This project demonstrates the application of Data Science and Machine Learning to climate change awareness. It showcases skills in data preprocessing, NLP, model building, and evaluation, making it ideal for academic projects, internships, and beginner portfolios.

⭐ If you found this project helpful, give it a star!
