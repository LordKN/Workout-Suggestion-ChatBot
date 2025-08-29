🏋️‍♂️ Gym Recommendation Chatbot
📌 Overview

I developed a Gym Recommendation Chatbot that leverages machine learning and data science to provide personalized workout and nutrition plans.

This project demonstrates my ability to:

Design end-to-end ML pipelines (data preprocessing → model training → predictions).

Apply supervised learning (regression & classification) to real-world health & fitness data.

Build an interactive chatbot that transforms raw predictions into actionable insights.

Combine data-driven fitness plans with nutrition recommendations for a holistic approach.

🚀 Key Contributions & Skills Demonstrated

Machine Learning & Data Science

Built regression & classification models (Random Forest, Linear Regression).

Evaluated models with RMSE, R², accuracy, and classification reports.

Designed preprocessing pipelines (imputation, scaling, one-hot encoding).

Software Engineering

Modularized Python scripts (gym_chatbot_new.py, gym_ml_model_new.py).

Implemented model persistence with Pickle.

Integrated datasets into a conversation-based application.

Data Analysis & Visualization

Conducted EDA on gym member data.

Created visualizations (heatmaps, distributions, feature importance).

Interpreted dataset insights to refine recommendations.

AI-Powered User Experience

Built a chat-driven interface that adapts to user inputs.

Generated weekly workout schedules & personalized exercises.

Provided meal plans based on calorie predictions and nutrition data.

📂 Project Structure
├── gym_chatbot_new.py                # Chatbot: collects user input, generates plans:contentReference[oaicite:0]{index=0}
├── gym_ml_model_new.py               # ML models: training, predictions, visualization:contentReference[oaicite:1]{index=1}
├── members_with_exercise_recommendations.csv # Dataset of member profiles & exercise recs
├── nutrients_csvfile.csv             # Nutrition dataset for meal planning
├── models/                           # Auto-saved ML models
│   ├── calories_model.pkl
│   ├── workout_model.pkl
│   └── experience_model.pkl
├── visualizations/                   # Auto-generated EDA charts

🏃 Quick Start – How to Use
1. Clone the Repository
git clone https://github.com/yourusername/gym-chatbot.git
cd gym-chatbot

2. Install Dependencies
pip install -r requirements.txt

3. Train & Explore Models (Optional First Step)
python gym_ml_model_new.py


This will:

Train ML models on members_with_exercise_recommendations.csv.

Save them under models/.

Generate visualizations (visualizations/).

Output sample meal recommendations.

4. Run the Chatbot
python gym_chatbot_new.py


This will:

Start an interactive conversation in the terminal.

Collect your profile (age, weight, goals, etc.).

Predict your calories burned, workout type, and experience level.

Generate a personalized workout + meal plan.

Let you ask follow-up questions (e.g., “What’s my Monday workout?”).

5. Example Run
Welcome to the Gym Recommendation Chatbot!
I'll help you find the perfect workout plan based on your profile.

What is your age? 24
What is your gender? (m/f): m
What is your weight in pounds? 160
What is your height? (feet): 5
Inches: 10
...

Analyzing your profile...
Based on your profile, you would typically burn 420.55 calories per session.
Your workout style matches with: HIIT
Your experience level appears to be: 2 (Intermediate)

YOUR PERSONALIZED HIIT WORKOUT PLAN
------------------------------------------------------
Experience Level: Intermediate
Recommended Sessions: 4 days per week
Estimated Calories Burned: 420 per session
Hydration Recommendation: 2.2 liters (~9.3 cups per day)

📊 Machine Learning Models

Calories Burned Prediction → Linear Regression & Random Forest Regressor

Workout Type Prediction → Random Forest Classifier

Experience Level Prediction → Random Forest Classifier

Metrics Used → RMSE, R² Score, Accuracy, Feature Importance

🍎 Nutrition Recommendation Engine

Uses nutrients_csvfile.csv for food nutrients.

Selects meals to match predicted calorie needs.

Ensures variety across workout days.

Outputs recommendations with calories, protein, carbs, and fiber.
