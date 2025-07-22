# Employee-Salary-Prediction-Rachel-Arora
This project is done under my 6-week virtual internship with Edunet Foundation in collaboration with IBM SkillsBuild platform given by AICTE internship portal.

# 💼 AI-Powered Salary Prediction Web App
Welcome to the **AI Salary Predictor** – an intelligent web application that estimates employee salaries based on key factors such as age, gender, education level, job title, and years of experience.

> 🎯 Built using **Python, Streamlit, and Machine Learning**, this project aims to bridge data and decision-making with ease and accuracy.

## 🚀 Features

- 🔍 **Instant Salary Prediction**  
  Upload details like age, education, job title, and more to get real-time salary estimations.

- 🤖 **Trained ML Pipeline**  
  Powered by a highly optimized machine learning model with:
  - ✅ **R² Score**: 0.91 (Excellent performance)
  - ✅ **RMSE**: ₹15,616.67

- 📦 **Interactive Web UI**  
  Built using **Streamlit**, offering a clean and intuitive user interface.

- 💾 **Model Trained on Kaggle Dataset**  
  Uses real-world data to deliver accurate predictions.

## How to Run
1. Clone this repository
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Run the app:  
   `streamlit run app.py`

## Files
- `app.py`: Main Streamlit app
- `requirements.txt`: requirements required
- `salary_prediction_pipeline.pkl`: Serialized trained model

  
## 📊 Model Performance

|               Metric               |     Value      |
|------------------------------------|----------------|
| **Mean Squared Error (MSE)**       | 243,880,416.72 |
| **Root Mean Squared Error (RMSE)** | ₹15,616.67     |
| **R-squared (R² Score)**           | 0.91           |

---

## 🧠 Technologies Used

- **Python 3.10+**
- **Streamlit**
- **Scikit-learn**
- **Pandas, NumPy, Matplotlib** 
- **Joblib** for model saving/loading

---

## 💡 How It Works

1. User inputs:
   - Age
   - Gender
   - Education Level
   - Job Title
   - Years of Experience

2. The input is passed to a **trained ML pipeline** (`salary_prediction_pipeline.pkl`).

3. The model outputs an estimated **salary (in INR ₹)** based on historical trends.
   
# 📁 Access Project 
Project Link: https://employee-salary-prediction-app-by-rachel.streamlit.app/

# 🎥 Project Demo
Access Video here 👉 [Demo](https://drive.google.com/file/d/1yb9TiO01I__R1LYY4O-3crp15sayLuaW/view?usp=drive_link)

# 📌 Future Improvements
- 🌐 Add multilingual support
- 📈 Integrate salary visualizations
- 💼 Expand dataset to include job industries and locations

# 🙌 Acknowledgments
- Dataset sourced from Kaggle
- Inspired by real-world HR and data science use cases

# 📬 Contact Me
Created with love by Rachel Arora. 🌐 LinkedIn: https://www.linkedin.com/in/rachelarora/
