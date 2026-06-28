#  Student Performance Prediction

> An End-to-End Machine Learning project that predicts a student's mathematics performance based on demographic, socio-economic, and academic attributes. The project demonstrates the complete lifecycle of a production-ready ML application—from data ingestion and preprocessing to model training, evaluation, and deployment through a web interface.

---

##  Overview

Educational institutions generate large amounts of student data that can be leveraged to improve academic outcomes. This project develops a Machine Learning solution capable of predicting a student's **Math Score** using various input features such as gender, parental education, lunch type, test preparation course, and previous reading and writing scores.

The project follows industry-standard software engineering practices, including modular architecture, exception handling, logging, configuration management, and a complete prediction pipeline.

---

##  Problem Statement

Predict a student's **Mathematics Score** using personal, educational, and demographic information.

This prediction can assist educators in:

* Identifying students who may require academic support.
* Understanding factors influencing academic performance.
* Enabling data-driven educational decision making.

---

##  Features

* End-to-End Machine Learning Pipeline
* Data Ingestion Pipeline
* Data Transformation Pipeline
* Model Training & Evaluation
* Prediction Pipeline
* Web-based User Interface
* Modular Project Architecture
* Custom Logging System
* Exception Handling
* Configuration Management
* Production-style Code Organization

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Machine Learning

* Scikit-learn
* CatBoost
* XGBoost
* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### Web Framework

* Flask

### Development Tools

* VS Code
* Git
* GitHub
* Jupyter Notebook

---

##  Project Structure

```
Student-Performance-Prediction/
│
├── artifacts/
│
├── notebook/
│   ├── EDA.ipynb
│   └── Model Training.ipynb
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline/
│   │   ├── predict_pipeline.py
│   │   └── train_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
├── static/
├── app.py
├── requirements.txt
├── setup.py
├── README.md
└── .gitignore
```

---

##  Machine Learning Workflow

```
Dataset
   │
   ▼
Data Ingestion
   │
   ▼
Data Transformation
   │
   ▼
Feature Engineering
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Model Selection
   │
   ▼
Prediction Pipeline
   │
   ▼
Flask Web Application
```

---

##  Dataset Features

| Feature                     | Description                |
| --------------------------- | -------------------------- |
| Gender                      | Student Gender             |
| Race/Ethnicity              | Student Group              |
| Parental Level of Education | Parent's highest education |
| Lunch                       | Standard / Free Lunch      |
| Test Preparation Course     | Completed / None           |
| Reading Score               | Reading Marks              |
| Writing Score               | Writing Marks              |
| **Target Variable**         | Mathematics Score          |

---

##  Installation

Clone the repository

```bash
git clone https://github.com/your-username/student-performance-prediction.git
```

Navigate to the project

```bash
cd student-performance-prediction
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the environment

Windows

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

Open your browser

```
http://127.0.0.1:5000
```

---

##  Model Pipeline

* Data Cleaning
* Missing Value Handling
* Feature Encoding
* Feature Scaling
* Model Training
* Hyperparameter Evaluation
* Model Selection
* Model Serialization
* Prediction Pipeline

---

##  Application Preview

> Add screenshots of:
>
> * Home Page
> * Prediction Form
> * Prediction Result
> * Model Output

---

##  Key Learning Outcomes

* Designing production-ready Machine Learning applications
* Building reusable ML pipelines
* Data preprocessing and feature engineering
* Model evaluation techniques
* Flask application development
* Project modularization
* Logging and exception handling
* Version control with Git & GitHub

---

##  Future Enhancements

* Docker Containerization
* CI/CD Pipeline
* Cloud Deployment (AWS/Azure)
* MLflow Experiment Tracking
* Model Monitoring
* REST API
* User Authentication
* Database Integration

---

##  Acknowledgements

This project was developed as part of my Machine Learning learning journey by implementing concepts taught in **Krish Naik's End-to-End Machine Learning course**. The project served as a practical exercise to understand how production-grade ML systems are designed, developed, and deployed.

---

##  Author

**Sashi Preetham**

Aspiring Data Engineer | Machine Learning Enthusiast | SQL • Python • Power BI • Azure • AWS

If you found this project useful, consider giving it a  on GitHub!
