# Health-Risk-Predictor
Machine Learning Web App that predicts health risk levels based on lifestyle factors.

🩺 Health Risk Predictor

A Machine Learning Web App built using Python and Streamlit that predicts an individual's health risk level based on lifestyle factors such as age, diet, exercise, sleep, stress, BMI, smoking habits, alcohol consumption, and family medical history.

🚀 Project Overview

The Health Risk Predictor model helps users estimate their potential health risk level (e.g., Low, Medium, or High) using a trained machine learning model.
It can serve as an early awareness tool to encourage healthy lifestyle choices.

🧠 Features

Interactive Streamlit web interface

Accepts multiple user inputs such as age, diet, exercise, sleep hours, etc.

Encodes categorical data using pre-trained LabelEncoders

Displays predicted risk level (Low / Medium / High)

Generates an interactive bar chart visualizing user lifestyle factors using Plotly

🧩 Tech Stack
Category	Technology
Programming Language	Python
Web Framework	Streamlit
Data Visualization	Plotly
Machine Learning	Scikit-learn
Model Saving	Pickle
📂 Project Structure
Health-Risk-Predictor/
│
├── app.py                     # Streamlit web app
├── risk_predictor.ipynb       # Jupyter notebook for model training
├── risk_predictor.pkl         # Trained ML model
├── label_encoders.pkl         # Saved label encoders
└── README.md                  # Project documentation

🧮 Input Features
Feature	Description	Example
Age	User's age	25
Diet Quality	Quality of daily diet	Good
Exercise (per week)	Number of days of exercise per week	3
Sleep Hours	Average sleep hours per night	7
Stress Level	Stress intensity	Medium
BMI	Body Mass Index	22.5
Smoking	Whether the person smokes	No
Alcohol Consumption	Alcohol intake level	Low
Family History	Family medical disease history	Yes/No
📊 Output

Predicted Health Risk: Low / Medium / High

Lifestyle Visualization: Interactive bar chart showing your current lifestyle pattern.

💡 Future Improvements

Include real health dataset for better accuracy

Add disease-specific prediction (e.g., heart disease, diabetes)

Integrate user feedback system to track health improvement over time

👨‍💻 Author

Saurabh Verma
🎓 BCA (Data Science & AI) Student at Shri Ramswaroop Memorial University (SRMU)
📧 princeverma3666@gmail.com

