Breast Cancer Prediction Web App

A machine learning-powered web application that predicts whether a tumor is benign or malignant based on 30 diagnostic features. Built with PyTorch and Flask, trained on the UCI Breast Cancer dataset, and deployed on Render.

🔧 Tech Stack: PyTorch, Flask, HTML/CSS, Google Colab, Render
💾 Model: 2-layer neural network, Binary classification
📦 Deployment: Hosted on Render with environment-aware configuration
🖥️ User Interface: HTML form with 30 input fields and prediction display


Integrated Power BI dashboards to visualize diagnostic feature trends, model predictions, and classification results in a machine learning-based breast cancer detection system.

Full Tech Stack Used
🧠 Machine Learning & Data Processing
PyTorch – For building and training the neural network model.

Scikit-learn (sklearn) – For:

Loading the UCI Breast Cancer dataset

Preprocessing using StandardScaler

Splitting data using train_test_split

NumPy – For numerical operations and array handling.

Pandas (optional, if you use it in Power BI or for CSV export) – Useful for creating/exporting datasets.

🌐 Web Framework & Backend
Flask – Lightweight Python web framework used to:

Create the web server

Handle form input and predictions

Connect frontend to backend

🖥️ Frontend & UI
HTML/CSS – For creating the user interface (form for inputting 30 features).

Jinja2 – Flask’s templating engine used to render HTML and pass the prediction result.

🚀 Deployment
Render – For deploying the Flask app to the web.

OS (Python's os module) – To handle environment variables (PORT) for deployment.

📊 Visualization (Planned)
Power BI (planned) – To visualize:

Feature distributions

Prediction outcomes

Model performance (accuracy, confusion matrix, etc.)
