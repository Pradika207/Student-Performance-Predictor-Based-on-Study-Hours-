📘 Project Title:
Student Performance Predictor Using Linear Regression (Pure Python)

🧠 Objective:
The goal of this project is to predict a student’s exam score based on the number of hours they study, using a simple linear regression algorithm implemented with core Python, without using any external libraries. This helps understand the relationship between study hours and performance in a mathematical, practical way.

📝 Problem Statement:
Students often ask, “How much should I study to score well?”
This project answers that by creating a predictive model. By analyzing real-world-like data of study hours and scores, the model can forecast a student’s expected marks for any given number of study hours.

🧮 Approach & Methodology:
Data Collection:
A small dataset was created manually, containing 8 students' study hours and corresponding scores.

Mathematical Technique:

We apply the Least Squares Method to calculate:

Slope (m): how much the score increases per hour studied

Intercept (c): the expected base score even if no study happens

The linear regression formula used:

ini
Copy
Edit
y = mx + c
Where:

y = predicted score

x = hours studied

m = slope

c = intercept

Prediction:

The user enters how many hours they plan to study.

The program then predicts their exam score using the formula.

🧾 Sample Input & Output:
yaml
Copy
Edit
Enter number of study hours: 6

📌 Predicted Score for studying 6.0 hours: 70.00
💡 Why This Project is Valuable:
Gives hands-on experience with regression analysis

Shows how real-world decisions (like study time) can be modeled using AI logic

Doesn’t require any libraries — runs on any basic Python environment

Ideal for beginners in the Artificial Intelligence & Data Science (AIDS) department

🛠️ Tools & Technologies Used:
Python (Core)

Basic math and statistics

Online Python compilers (e.g., Programiz, Replit)

🌟 Future Improvements:
Add a GUI using Tkinter or Streamlit

Expand dataset for more accuracy

Introduce other factors like sleep hours, subject difficulty, etc.
