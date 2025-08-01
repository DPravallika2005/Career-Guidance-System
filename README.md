# 🎯 Career Guidance System

**Career Guidance System** is a smart, interactive, and data-driven web-based application designed to help students make informed career choices based on their interests. It leverages a structured psychological questionnaire and an advanced **XGBoost** machine learning model to recommend the most suitable career paths. The system aims to bridge the gap between academic interests and real-world career options by offering personalized and accurate recommendations.

---

## 🌟 Motivation

Choosing a career is one of the most critical decisions in a student’s life. Many students make decisions based on peer pressure, societal trends, or a lack of proper guidance. This often leads to dissatisfaction, skill mismatches, and underperformance in the professional world. This project was built to **empower students with data-backed career recommendations** using a simple yet effective questionnaire model and machine learning techniques. The goal is to make career guidance **accessible, objective, and personalized**.

---

## 📌 Project Objective

The main goal of this project is to provide a virtual career counselor that uses a psychological-based interest analysis framework to recommend top career paths. This system is intended to assist:
- School and college students in exploring suitable career options.
- Counselors and educators in identifying student inclinations early.
- Institutions in implementing scalable career guidance without the need for manual evaluation.

---

## 🧠 How It Works

- The user answers a **36-question survey**, with Yes/No responses.
- Each question is categorized into 9 core interest domains such as Science, Creativity, Management, Healthcare, Technology, etc.
- Each domain has 4 questions to assess a student’s inclination.
- Based on the number of 'Yes' responses, a **score vector** is generated.
- This vector is fed into a **pre-trained XGBoost model**, which outputs the **top 4 most relevant career domains**.
- PHP and Python integration via **XAMPP** ensures smooth frontend-backend communication and model execution.

---

## 🚀 Features

- ✅ Clean and responsive UI built with HTML, CSS, and PHP
- 📊 Domain-wise analysis of interest areas
- 🤖 ML-based prediction using XGBoost for high accuracy
- 🔁 Real-time integration of PHP and Python via system-level scripting
- 🧩 Customizable for different age groups and educational levels
- 📂 Easy deployment using XAMPP for local hosting or cloud platforms

---

## 🛠️ Technologies Used

| Component       | Technology Used                  |
|----------------|----------------------------------|
| Frontend       | HTML, CSS, JavaScript            |
| Backend        | PHP, Python                      |
| Machine Learning | XGBoost, Pandas, Scikit-learn    |
| Hosting        | XAMPP (Apache Server + MySQL)    |
| Communication  | PHP Shell Execution (to call Python model) |

---

## 🔧 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DPravallika2005/Career-Guidance-System.git
   cd Career-Guidance-System
