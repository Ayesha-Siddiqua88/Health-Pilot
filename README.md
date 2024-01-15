<img src="images/HealthPilot.png">

![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B.svg?style=for-the-badge&logo=Streamlit&logoColor=white)
<br>
![OpenAI](https://img.shields.io/badge/OpenAI-412991.svg?style=for-the-badge&logo=OpenAI&logoColor=white)
![ENV](https://img.shields.io/badge/.ENV-ECD53F.svg?style=for-the-badge&logo=dotenv&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75.svg?style=for-the-badge&logo=Plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
<BR>
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853.svg?style=for-the-badge&logo=Google-Sheets&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4.svg?style=for-the-badge&logo=Google-Cloud&logoColor=white)

<br><br>

## 🗒️ Table of Contents

- [What is Health Pilot?](#-what-is-health-pilot)
- [Features](#-features)
- [Installation](#-installation)
- [Run Application](#%EF%B8%8F-run-application)
- [How to Use](#how-to-use)
- [Working](#working)
- [Contributors](#-contributors)
<br>

## ⭐ What is Health Pilot?

Welcome to Health Pilot. Your virtual co-pilot for a healthier you! It is a Diabetes and Heart Disease Prediction System. This platform is designed to predict and analyze diabetes and heart disease using trained machine learning models. It also provides you with the necessary precautions with the help of AI integration, you need to take if you have these diseases. So let Health Pilot be your passport to healthier journet ahead.
<br><br>

## 🤓 Features

- Quick and accurate disease predictions.
- Safely store and manage your previous health reports, creating a comprehensive archive for easy reference and tracking.
- Provides Guidelines for effective diabetes and heart disease control.
- Google Sheets integration for data storage.
- Data visualization for analysis.
<br><br>

## 🔨 Installation

Before running the application, ensure you have the following installed on your machine:<br><br>

![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B.svg?style=for-the-badge&logo=Streamlit&logoColor=white)

<br>

- Streamlit
    
    ```bash
    pip install streamlit
    
    ```
    
- Plotly
    
    ```bash
    pip install plotly
    
    ```
    
- Gspread
    
    ```bash
    pip install gspread
    
    ```
    
- OpenAI
    
    ```bash
    pip install openai
    
    ```
    
- Streamlit Option Menu
    
    ```bash
    pip install streamlit-option-menu
    
    ```
    

While the other libraries are already present in your Python Standard Library. Additionally, for using the openai library, you need to have an OpenAI API key. Make sure to set up your OpenAI API key and store it securely. You can follow the OpenAI documentation to obtain your API key. Once you have your API key, you can set it up in your project by using dotenv to load environment variables from a file. Create a file named .env in your project directory and add the following line:

```bash
OPENAI_API_KEY=your_api_key_here

```

Replace <i><b>your_api_key_here</b></i> with your actual OpenAI API key. Lastly, in your Python code, add the following lines at the beginning:

```bash
from dotenv import load_dotenv
load_dotenv()

```

<br>

## 🏃‍♀️ Run Application

Clone the project

```bash
  git clone <https://github.com/Ayesha-Siddiqua88/Health-Pilot.git>

```

Go to the project directory

```bash
  cd my-project

```

Run the following code in terminal

```bash
  streamlit run app.py

```

<br>

## 🤔 How to Use

1. **Select a Disease Prediction:**
    - Use the sidebar to choose the disease prediction you are interested in (Diabetes, Heart Disease).
2. **Data Entry:**
    - Fill in the required information for the selected disease prediction.
    - Click the respective prediction button to get the result.
3. **View Results:**
    - View the prediction result and relevant information.
    - Explore additional analysis and visualizations available.

<br>

## 🎥 Working

https://github.com/Ayesha-Siddiqua88/Health-Pilot/assets/128472306/9a4522fc-2a15-418d-bbfc-cd4d25900a02

<br>

## 💙 Contributors

[![Contributor](https://img.shields.io/badge/Asma-Khanam-blue?style=flat&logo=github)](https://github.com/Asma-Khanam)
