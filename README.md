# AI-HEALTH-AGENT
This project is an AI-powered assistant that generates personalized, condition-friendly daily meal plans for people with Diabetes and Gastritis
# AI-Powered Medical Diet Assistant for Diabetes & Gastritis

## Overview
This project provides personalized daily diet recommendations for users with Diabetes and Gastritis.

## Features
- Personalized meal plan based on medical conditions
- Considers age, gender, and food preferences
- Safe and healthy diet suggestions

## Files
- `diet_assistant.ipynb` : Main notebook
- `report.pdf` : Project report
- `images/` : Screenshots and plots
# AI-Powered Personalized Diet Planner

This is a Python-based AI-powered personalized diet planner that recommends food items and generates meal plans based on user goals and dietary preferences. It also predicts the daily calorie requirement based on user information.

---

## Features

1. **Food Recommendation**  
   - Suggests food items based on fitness goals: `weight_loss`, `muscle_gain`, or `maintenance`.  
   - Supports different diet types: `vegan`, `vegetarian`, `non_vegetarian`.

2. **Meal Plan Generation**  
   - Generates a simple 3-meal plan (Breakfast, Lunch, Dinner) for the day.

3. **Daily Calorie Prediction**  
   - Predicts daily calorie requirement based on user age, weight, height, and activity level.

---

## Dataset

- The script uses sample datasets included in the code.  
- You can replace them with real datasets for nutrition and user info.

---

## Installation

1. Clone this repository:
```bash
git clone https://github.com/<your-username>/AI-Diet-Planner.git
pip install pandas scikit-learn
# Get recommended foods
recommend_food('muscle_gain', 'vegan')

# Generate meal plan
generate_meal_plan('weight_loss', 'vegetarian')

# Predict daily calories
predict_calories([26, 62, 168, 2])  # age, weight(kg), height(cm), activity_level
---- Recommended Foods ----
   food_name  calories  protein  carbs   fat
3       Tofu -1.35     0.00     -0.35 -0.05
4   Broccoli -1.10    -0.87     -0.05 -0.87

---- Meal Plan ----
Breakfast:
 - Oats (Calories: -0.23)
 - Broccoli (Calories: -1.10)

Lunch:
 - Oats (Calories: -0.23)
 - Broccoli (Calories: -1.10)

Dinner:
 - Oats (Calories: -0.23)
 - Broccoli (Calories: -1.10)

---- Predicted Daily Calories ----
Predicted Daily Calories: 2100
# Get recommended foods
recommend_food('muscle_gain', 'vegan')

# Generate meal plan
generate_meal_plan('weight_loss', 'vegetarian')

# Predict daily calories
predict_calories([26, 62, 168, 2])  # age, weight(kg), height(cm), activity_level.
# AI-Health-Agent: AI-Powered Medical Diet Assistant

**AI-Health-Agent** is an AI-powered assistant that generates personalized, condition-friendly daily meal plans for people with **Diabetes** and **Gastritis**. It also predicts daily calorie requirements and suggests foods based on dietary preferences and fitness goals.

---

## Features

### Personalized Meal Plans
- Generates 3-meal plans (Breakfast, Lunch, Dinner) tailored for **Diabetes** and **Gastritis** patients.
- Considers user age, gender, activity level, and food preferences.
- Ensures safe and healthy food recommendations.

### Food Recommendation
- Suggests foods based on fitness goals: `weight_loss`, `muscle_gain`, `maintenance`.
- Supports diet types: `vegan`, `vegetarian`, `non_vegetarian`.

### Daily Calorie Prediction
- Estimates daily calorie requirement based on age, weight, height, and activity level.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/AI-Diet-Planner.git
from diet_assistant import generate_meal_plan

generate_meal_plan('weight_loss', 'vegetarian')
cd AI-Diet-Planner
pip install pandas scikit-learn
from diet_assistant import recommend_food

recommend_food('muscle_gain', 'vegan')
from diet_assistant import predict_calories

# Format: [age, weight(kg), height(cm), activity_level]
predict_calories([26, 62, 168, 2])

🥗 AI-Health-Agent

AI-Health-Agent is an AI-powered assistant that creates personalized meal plans for people with Diabetes and Gastritis.
It provides safe and healthy food recommendations based on diet preferences, fitness goals, age, gender, and activity level, and estimates daily calorie needs.


---

🌟 Features

Personalized Meal Plans: Breakfast, Lunch, and Dinner tailored for medical conditions.

Food Recommendations: Suggests foods for weight loss, muscle gain, or maintenance; supports vegan, vegetarian, and non-vegetarian diets.
🥗 AI-Health-Agent

AI-Health-Agent is an AI-powered assistant that creates personalized meal plans for people with Diabetes and Gastritis.
It provides safe and healthy food recommendations based on diet preferences, fitness goals, age, gender, and activity level, and estimates daily calorie needs.


---

🌟 Features

Personalized Meal Plans: Breakfast, Lunch, and Dinner tailored for medical conditions.

Food Recommendations: Suggests foods for weight loss, muscle gain, or maintenance; supports vegan, vegetarian, and non-vegetarian diets.

AI-Health-Agent

AI-Health-Agent is an AI-powered assistant that creates personalized meal plans for people with Diabetes and Gastritis. It provides healthy, safe, and tailored food recommendations based on diet preferences, fitness goals, age, gender, and activity level.

🌟 Key Features

Personalized meal plans for Breakfast, Lunch, and Dinner

Supports weight loss, muscle gain, or maintenance

Vegan, vegetarian, and non-vegetarian options

Diabetes-friendly and stomach-friendly meals

Meal reminders, recipe suggestions, and weekly tracking

Export plans as PDF


Stay healthy, manage your diet, and achieve your fitness goals effortlessly!
