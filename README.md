# Lung Cancer Prediction Application

This repository contains a Streamlit-based web application for predicting lung cancer. It uses a Logistic Regression model trained to achieve an accuracy of **90%**. The application allows users to input their health-related details and provides predictions based on the trained model.

---

## Features

- Interactive web interface for lung cancer prediction.
- Input fields for user health details such as age, gender, smoking habits, etc.
- Utilizes a pre-trained Logistic Regression model (`lung_cancer_prediction.pkl`).
- Provides user-friendly predictive insights with appropriate messages.

---

## Input Parameters

- **GENDER**: Male or Female.
- **AGE**: Age in years (integer value).
- **SMOKING**: Indicates if the user smokes (Yes/No).
- **YELLOW FINGERS**: Indicates if the user has yellow fingers (Yes/No).
- **ANXIETY**: Indicates if the user has anxiety (Yes/No).
- **PEER PRESSURE**: Indicates if peer pressure exists (Yes/No).
- **CHRONIC DISEASE**: Indicates if the user has a chronic disease (Yes/No).
- **FATIGUE**: Indicates if the user experiences fatigue (Yes/No).
- **ALLERGY**: Indicates if the user has allergies (Yes/No).
- **WHEEZING**: Indicates if the user experiences wheezing (Yes/No).
- **ALCOHOL CONSUMING**: Indicates if the user consumes alcohol (Yes/No).
- **COUGHING**: Indicates if the user has a cough (Yes/No).
- **SHORTNESS OF BREATH**: Indicates if the user has shortness of breath (Yes/No).
- **SWALLOWING DIFFICULTY**: Indicates if the user has difficulty swallowing (Yes/No).
- **CHEST PAIN**: Indicates if the user experiences chest pain (Yes/No).

---

## Installation and Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/manitejagaddam/lung-cancer-prediction.git
   cd lung-cancer-prediction
   ```
2. **Install Dependencies**
   
  ```bash
  pip install -r requirements.txt
  ```
3. **Run the Application**
   
  ```bash
  streamlit run app.py
  ```

# Project Images :
![Screenshot 2024-12-24 141051](https://github.com/user-attachments/assets/415f6d63-b656-4ca4-9228-ec4e6e095da7)

![image](https://github.com/user-attachments/assets/18bb742a-af20-4c84-8e31-cfdb91db6ac4)

