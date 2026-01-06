# Developing-A-Prediction-System-For-Multiple-Disease-Using-Supervised-Learning-Models
An AI-driven health diagnostic tool utilizing Machine Learning to predict Diabetes, Heart Disease, and Parkinson’s. Built with Python and Streamlit, it features trained SVM and Logistic Regression models to provide real-time risk assessments from clinical data. This project offers a seamless UI for early diagnosis and data-driven healthcare.
A comprehensive machine learning-based application designed to predict the likelihood of multiple diseases (such as Diabetes, Heart Disease, and Parkinson's) based on user-provided clinical data. This project leverages various classification algorithms and provides a user-friendly interface via Streamlit.
📋 Table of Contents
         Overview
         Features
         Dataset 
         Information
         Installation
         Usage
         Model Performance
         Tech Stack
         Contributing
         
🔍 Overview
           Early diagnosis is critical for effective treatment. This repository contains the source code for a web-based diagnostic tool. By inputting specific medical parameters (like glucose levels, blood pressure, or vocal frequencies), the system utilizes pre-trained models to provide an instant health assessment.
                 Supported Diseases:
                      Diabetes: Predicts based on BMI, insulin, age, etc.
                      Heart Disease: Predicts based on chest pain type, cholesterol, and heart rate.
                      Parkinson’s Disease: Predicts using voice-related features and MDVP measures.
                      
✨ Features
         Multi-Disease Support: Access three different diagnostic tools in one dashboard.
         Real-time Prediction: Get instant results upon submitting data.
         Intuitive UI: Clean sidebar navigation and responsive input fields.
         Scalable: Easy to add new disease models by following the modular code structure.
         
📊 Dataset Information
      The models were trained using datasets from the UCI Machine Learning Repository and Kaggle.
      
⚙️ Installation
      To run this project locally, follow these steps:
               Clone the Repository:
                   Bash  git clone https://github.com/your-username/multiple-disease-prediction.git
                         cd multiple-disease-prediction
              Create a Virtual Environment:
                   Bash  python -m venv venv
                         source venv/bin/activate  # On Windows: venv\Scripts\activate
               Install Dependencies:
                    Bash   pip install -r requirements.txt
                    
🚀 Usage
    Ensure you have your saved models (e.g., .sav or .pkl files) in the saved_models/ directory.
       Run the Streamlit application:
             Bash    streamlit run app.py
    Navigate through the sidebar to select the disease you wish to test for.
    
📈 Model Performance
           We evaluated several algorithms (SVM, Logistic Regression, Random Forest) to find the most accurate models.
                        Diabetes Model: Support Vector Machine ($92\%$ accuracy)
                        Heart Disease Model: Logistic Regression ($85\%$ accuracy)
                        Parkinson's Model: SVM ($88\%$ accuracy)
                
🛠 Tech Stack
        Language: Python
        Libraries: Scikit-learn, Pandas, NumPy, Pickle
        Deployment: Streamlit
        Environment: Jupyter Notebook / VS Code
        
🤝 Contributing
        Contributions are what make the open-source community such an amazing place to learn, inspire, and create.
                   Fork the Project.
                   Create your Feature Branch (git checkout -b feature/AmazingFeature).
                   Commit your Changes (git commit -m 'Add some AmazingFeature').
                   Push to the Branch (git push origin feature/AmazingFeature).
                   Open a Pull Request.
                  
  📄 License
              Distributed under the MIT License. See LICENSE for more information.
