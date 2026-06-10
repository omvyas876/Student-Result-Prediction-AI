# 🎓 Student Result Prediction Using Machine Learning

> A Machine Learning project that predicts a student's final marks based on Study Hours, Attendance Percentage, and Past Academic Performance using Linear Regression.

---

## 📖 Overview

Student academic performance is influenced by multiple factors such as study habits, attendance, and previous results. This project uses a **Linear Regression** model to analyze these factors and predict a student's final marks.

The system also classifies the predicted result as **PASS** or **FAIL**, helping students and educators understand expected performance and identify areas for improvement.

---

## ✨ Features

- Predicts final marks using Machine Learning
- Uses Linear Regression for regression analysis
- Evaluates model performance using MAE and R² Score
- Supports predictions for multiple students
- Interactive user input for real-time prediction
- PASS/FAIL classification
- Clean and beginner-friendly implementation

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| NumPy | Numerical Operations |
| Pandas | Data Manipulation |
| Scikit-Learn | Machine Learning |
| Linear Regression | Prediction Algorithm |
| StandardScaler | Feature Scaling |

---

## 📂 Project Structure

```text
Student-Result-Prediction-AI/
│
├── main.py
├── data.py
├── model.py
├── predict.py
├── utils.py
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

The project uses a sample dataset of 30 students containing:

| Feature | Description |
|----------|-------------|
| Study Hours | Daily study hours |
| Attendance | Attendance percentage |
| Past Marks | Previous academic marks |
| Final Marks | Actual final marks (Target Variable) |

### Sample Data

| Study Hours | Attendance | Past Marks | Final Marks |
|------------|------------|------------|------------|
| 8 | 90 | 78 | 82 |
| 5 | 75 | 60 | 63 |
| 3 | 60 | 45 | 47 |
| 7 | 85 | 72 | 76 |
| 2 | 50 | 35 | 38 |

---

## ⚙️ Machine Learning Workflow

### Step 1: Dataset Creation
A dataset containing student academic information is prepared.

### Step 2: Feature and Target Selection

**Features:**
- Study Hours
- Attendance
- Past Marks

**Target:**
- Final Marks

### Step 3: Train-Test Split

The dataset is divided into:
- 80% Training Data
- 20% Testing Data

### Step 4: Feature Scaling

StandardScaler is used to normalize the input features before training.

### Step 5: Model Training

A Linear Regression model is trained on the scaled training data.

### Step 6: Model Evaluation

#### Mean Absolute Error (MAE)
Measures average prediction error.

#### R² Score
Measures how well the model explains the variance in data.

### Step 7: New Student Prediction

The trained model predicts marks for unseen students.

### Step 8: Interactive Prediction

Users can enter:
- Study Hours
- Attendance Percentage
- Past Marks

The system predicts:
- Final Marks
- PASS / FAIL Status

---

## 🧠 Why Linear Regression?

Linear Regression is used because:

- Final marks are continuous numerical values
- Easy to implement and understand
- Suitable for small datasets
- Fast training and prediction
- Provides good baseline performance

### Prediction Formula

```text
Final Marks =
b₀ + b₁(Study Hours)
+ b₂(Attendance)
+ b₃(Past Marks)
```

Where:

- **b₀** = Intercept
- **b₁, b₂, b₃** = Coefficients learned by the model

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/omvyas876/Student-Result-Prediction-AI.git
cd Student-Result-Prediction-AI
```

Install required libraries:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install numpy pandas scikit-learn
```

---

## ▶️ Running the Project

Run the project using:

```bash
python main.py
```

or

```bash
python student_result_predictor.py
```

---

## 💻 Example Output

```text
=======================================================
       STUDENT RESULT PREDICTOR
=======================================================

--- Model Performance ---
Mean Absolute Error : 1.85
R² Score            : 0.98

--- Prediction Result ---
Predicted Final Marks : 74.3 / 100
Result                : PASS
Performance           : Good
```

---

## 🎯 Applications

- Academic Performance Analysis
- Student Progress Monitoring
- Educational Research
- Learning Analytics
- Early Identification of Weak Students

---

## ⚠️ Limitations

- Uses a small sample dataset
- Prediction quality depends on data quality
- Does not consider external factors such as health, environment, or personal circumstances

---

## 🔮 Future Enhancements

- Larger real-world datasets
- GUI using Tkinter
- Web application using Flask or Streamlit
- Data visualization dashboards
- Model saving and loading using Pickle
- Advanced Machine Learning models:
  - Random Forest
  - XGBoost
  - Gradient Boosting

---

## 📚 Learning Outcomes

This project demonstrates:

- Data Preprocessing
- Feature Scaling
- Train-Test Splitting
- Linear Regression
- Model Evaluation
- Real-Time Prediction
- End-to-End Machine Learning Workflow

---

## 📄 License

This project is developed for educational and learning purposes.

Feel free to use, modify, and improve it for academic projects.

---

⭐ If you found this project useful, consider giving it a star!
