# Fundamentals-of-AI-and-ML-Evaluated-Course-Project
This project implements Multiple Linear Regression in pure Python without external libraries. It uses Stochastic Gradient Descent to manually optimize weights and bias, demonstrating the core mathematical principles of Supervised Learning.
Student Marks Predictor (Linear Regression from Scratch) 🎓
Hi! This is a project I built to understand how Machine Learning actually works behind the scenes. Instead of just using a library like Scikit-Learn to do the work for me, I wrote the math and the learning loop in pure Python.

The Problem
As a student, balancing study hours, sleep, and attending classes is a constant struggle. I wanted to see if I could build an AI that calculates exactly how much each of these factors affects a final grade.

How it Works (The "Brain")
This project uses Multiple Linear Regression. I implemented an optimization algorithm called Stochastic Gradient Descent (SGD).

Initialization: The model starts knowing nothing (weights are 0).

The Learning Loop: It goes through 10,000 cycles (epochs). In each cycle, it makes a guess, calculates how far off it was (the error), and slightly adjusts its "weights" for study, sleep, and attendance.

Prediction: Once trained, you can type in your own data, and the model uses its learned weights to predict your percentage.

Features
Zero Libraries: No numpy, no pandas, no sklearn. Just raw Python math.

Multi-Variable: It doesn't just look at study hours; it considers sleep and attendance too.

Interactive: You can run the script and input your own data to see your predicted score.

Human-Readable: I wrote the code to be clean and easy to follow, with print statements that explain what the AI is "thinking" while it trains.

Why I Built This
I wanted to prove that I understand Gradient Descent and Weight Optimization. It’s easy to call a function, but building the engine from scratch taught me why things like "learning rates" matter (and how they can break the model if they're too high!).

How to Run
Make sure you have Python installed.

Download student_predictor.py.

Run it in your terminal:

Future Goals
Add a simple web interface using Streamlit.

Add a feature to calculate the "Impact Factor" (showing which habit helps your grade the most).



