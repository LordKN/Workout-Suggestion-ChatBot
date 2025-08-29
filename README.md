# ▶️ How It Works

## User Interaction: Chatbot collects age, gender, BMI, workout frequency, and goals.

### ML Predictions:

🔹 Calories burned per session

🔹 Predicted workout type (Cardio, Strength, Yoga, HIIT)

🔹 Predicted experience level (Beginner → Advanced)

### Personalized Output:

Weekly workout schedule with exercises.

Hydration & recovery guidelines.

Daily meal recommendations based on calorie needs.

# 🏃 Quick Start – How to Use
## 1. Clone the Repository
git clone https://github.com/yourusername/gym-chatbot.git
cd gym-chatbot

## 2. Install Dependencies
pip install -r requirements.txt

## 3. Run the Machine Learning Pipeline (Optional First Step)

### This will:

Load and preprocess the gym dataset.

Train the ML models (calories, workout type, experience level).

Save the trained models under the models/ directory.

Generate visualizations in the visualizations/ folder.

Output sample meal recommendations.

python gym_ml_model_new.py


### 📂 After running, you should see:

models/calories_model.pkl, models/workout_model.pkl, models/experience_model.pkl

Plots like workout_types.png, calories_by_workout.png

## 4. Run the Chatbot
python gym_chatbot_new.py


This will:

Start an interactive conversation in the terminal.

Ask about your age, gender, weight, height, heart rate, workout frequency, and fitness goals.

Predict your calories burned, workout type, and experience level.

Generate a personalized weekly workout plan with daily exercise lists.

Provide meal recommendations for workout days.

Allow you to ask follow-up questions, such as:

“How many calories will I burn?”

“What’s my Monday workout?”

“How much water should I drink daily?”

## 5. Example Run
Welcome to the Gym Recommendation Chatbot!
I'll help you find the perfect workout plan based on your profile.

What is your age? 
24
What is your gender? (m/f): 
m
What is your weight in pounds? 
160
What is your height? (feet): 
5
Inches: 
10
...

Analyzing your profile...
Based on your profile, you would typically burn 420.55 calories per session.
Your workout style matches with: HIIT
Your experience level appears to be: 2 (Intermediate)

## YOUR PERSONALIZED HIIT WORKOUT PLAN
------------------------------------------------------
Experience Level: Intermediate
Recommended Sessions: 4 days per week
Estimated Calories Burned: 420 per session
Hydration Recommendation: 2.2 liters (~9.3 cups per day)
