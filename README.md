# VITYarthi_Sem2_AIMLProject
# 🧠 AI-Powered Study Time Predictor 📚

An intelligent study assistant built with **Machine Learning** to help students optimize their preparation time based on topic complexity and exam urgency.

## 🚀 Overview
This project uses **Multiple Linear Regression** to predict the number of hours a student should dedicate to a specific topic. By analyzing historical data from a CSV file, the AI provides a data-driven recommendation instead of a guess.

## 📊 Features
- **Predictive Modeling:** Uses `Scikit-Learn` to calculate study requirements.
- **Data Visualization:** Generates real-time bar charts using `Matplotlib` to visualize stress factors vs. suggested hours.
- **Custom Dataset:** Integrated with `study_data.csv` for training the model.
- **User Interaction:** Interactive input prompts for a personalized experience.

## 🛠️ Tech Stack
- **Language:** Python 3.12
- **Libraries:** Pandas, Scikit-Learn, Matplotlib
- **Environment:** Jupyter Notebook / VS Code

## 📉 How It Works
The model evaluates five key "features" to make its prediction:
1. **Difficulty (1-10):** How hard the topic is.
2. **Importance (1-10):** Weightage in the exam.
3. **Current Knowledge (1-10):** How much you already know.
4. **Days to Exam:** Urgency of the deadline.
5. **Distraction Level (1-10):** Environmental factors.



## ⚙️ Installation & Usage
1. Clone the repository:
   ```bash
   git clone (https://github.com/sweety25bai10432-collab/AI-Study-Planner.git)
