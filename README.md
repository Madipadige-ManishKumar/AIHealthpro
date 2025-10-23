# 🧠 AIHealthPro

A **Flask-based Machine Learning web app** for predicting multiple diseases including **Diabetes, Lung Disease, Liver Disease, and Blood Pressure conditions**.

This project allows users to:

* Enter medical parameters through an easy-to-use web form.
* Predict the likelihood of health conditions using trained ML models (Logistic Regression, Decision Tree, SVM).
* View real-time disease predictions instantly in the web app.



---

## Setup & Usage Instructions

1. **Clone the Repository**

```bash
git clone https://github.com/Madipadige-ManishKumar/Hand-Written-equation-solver.git
cd Hand-Written-equation-solver
```

2. **Create a Python Virtual Environment (Optional but Recommended)**

```bash
python -m venv venv
```

Activate the virtual environment:

* **Windows:**

```bash
venv\Scripts\activate
```

* **macOS / Linux:**

```bash
source venv/bin/activate
```

3. **Install Dependencies**

```bash
pip install -r requirements.txt
```
```

4. **Run the Flask App**

```bash
python wsgi.py
```

* This will start the flask server.
* Open your browser at the URL displayed in the terminal (usually `http://localhost:5000`).

5. ** How It Works**


* 1. User inputs medical data (like glucose level, heart rate, enzyme levels, etc.)
*  2. The system processes the data through trained ML models (Logistic Regression, Decision Tree, SVM)
*  3. The model predicts the likelihood of the disease.
*  4. The result is displayed instantly on the web interface.
