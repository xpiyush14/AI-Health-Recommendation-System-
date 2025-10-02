# AI-Health Recommendation System
An intelligent web application that predicts potential diseases based on user-input symptoms and provides comprehensive health recommendations using a machine learning model.


# 🌟 Key Features
🤖 AI-Powered Predictions: Utilizes a Support Vector Classifier (SVC) model trained on a comprehensive medical dataset to accurately predict potential diseases.

🩺 Intuitive Symptom Input: A user-friendly interface allows users to easily enter their symptoms as comma-separated text.

📚 Comprehensive Recommendations: For a predicted disease, the system provides:
1.)Description: A clear explanation of the condition.

2.)Precautions: Recommended preventive measures.

3.)Medications: A list of commonly suggested medications.

4.)Diet Plan: Dietary advice to aid recovery.

5.)Exercises: Suggested physical activities.

🌐 Modern & Responsive UI: A sleek, dark-themed interface built with Bootstrap 5, HTML5, and advanced CSS for a seamless experience on any device.

📄 Multi-Page Structure: A complete web application with dedicated pages for Home, About, Contact, Developer, and a Blog. 


# 🛠️ Technology Stack
1.) Backend Technologies
Python: The core programming language used for the server-side logic.

Flask: A micro web framework for Python used to build the web application, handle routing, and manage requests.

Machine Learning & Data Handling
Scikit-learn (sklearn): The primary machine learning library used to build and train the Support Vector Classifier (SVC) model for disease prediction.

Pandas: A data manipulation and analysis library used to load and manage the datasets (symptoms, precautions, medications, etc.) from CSV files.

NumPy: A fundamental package for numerical computation in Python, used to create and manipulate the input vectors for the model.

Pickle: A Python module used for serializing and de-serializing the trained machine learning model, allowing you to save and load it without retraining.

# 3.) Frontend Technologies
 HTML5: The standard markup language used to create the structure and content of all the web pages (index, about, contact, etc.).

CSS3: Used for styling the web pages, including the modern dark theme, gradients, animations, and responsive design.

JavaScript: Employed for client-side interactivity, such as handling form submissions, creating animations, and managing dynamic content like modals.

Bootstrap 5: A popular CSS framework used extensively for layout, responsive design, and pre-styled components like the navigation bar, buttons, cards, and modals.

# ⚙️ How It Works
The system's core is a pre-trained Support Vector Classifier (SVC) model.
1.) Symptom Input: The user enters their symptoms into the web form.

2.) Data Preprocessing: The Flask backend receives the input. The symptoms are then converted into a numerical vector using a predefined symptom dictionary.

3.) Prediction: This vector is fed into the loaded SVC model, which predicts a disease class.

4.) Recommendation Retrieval: Based on the predicted disease, the application retrieves relevant information (description, precautions, medications, etc.) from various CSV datasets.

5.) Display Results: The results are dynamically rendered on the frontend within interactive modals, providing a clean and organized view of the health recommendations.

# ⚠️ Disclaimer
This AI Health Recommendation System is intended for informational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of a qualified healthcare provider with any questions you may have regarding a medical condition.

