# 📈 Simple Linear Regression From Scratch

This project demonstrates how to implement **Simple Linear Regression manually** using Python and NumPy, without relying on sklearn for the core calculations.

The model is built using a real-world Salary dataset and follows the complete machine learning workflow.

---

## 🚀 Project Overview

In this project, we:

- Loaded and explored the dataset
- Visualized the data using Matplotlib
- Manually calculated:
  - Mean of X and Y
  - Slope (M)
  - Intercept (B)
- Built the Linear Regression equation:
  
  y = Mx + B

- Predicted salary for new experience values
- Calculated evaluation metrics:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Compared manual implementation with sklearn

---

## 📊 Dataset

The dataset contains 30 samples with:

- **YearsExperience** → Independent Variable (X)
- **Salary** → Dependent Variable (Y)

The goal is to predict salary based on years of experience.

---

## 🧠 Mathematical Formula Used

Slope (M):

\[
M = \frac{\sum (x_i - \bar{x})(y_i - \bar{y})}
{\sum (x_i - \bar{x})^2}
\]

Intercept (B):

\[
B = \bar{y} - M\bar{x}
\]

Final Regression Equation:

\[
y = Mx + B
\]

---

## 📈 Model Evaluation

Regression metrics used:

- **MSE (Mean Squared Error)**
- **RMSE (Root Mean Squared Error)**
- **R² Score**

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn (for comparison)

---

## 📌 Key Learning Outcome

This project helps in understanding:

- How Linear Regression works internally
- The mathematics behind best-fit line
- How error is calculated in regression
- Difference between manual implementation and sklearn

---

## 👤 Author

Abdul Mamtaan

---

⭐ If you found this project helpful, feel free to star the repository!
