# python-assignment-part4

## Student Performance Analysis & Prediction

## 📌 Description
This project analyses a student performance dataset and builds a machine learning model to predict whether a student will pass or fail.  
It demonstrates data analysis, visualization, and machine learning using Python.

---

## 📂 Tasks Implemented

### 🔹 Task 1 — Data Exploration with Pandas
- Loaded dataset from `students.csv` using Pandas
- Displayed first 5 rows using `.head()`
- Printed dataset shape and column data types
- Generated summary statistics using `.describe()`
- Counted number of passing and failing students
- Computed average subject scores for pass and fail groups
- Identified student with highest overall average score

---

### 🔹 Task 2 — Data Visualization with Matplotlib
- Created bar chart showing average score per subject
- Plotted histogram of math scores with mean line
- Generated scatter plot of study hours vs average score (Pass vs Fail)
- Created box plot comparing attendance of pass vs fail students
- Plotted line graph of math and science scores across students
- Saved all plots as `.png` files

---

### 🔹 Task 3 — Data Visualization with Seaborn
- Created bar plots comparing math and science scores (Pass vs Fail)
- Generated scatter plot with regression lines for attendance vs performance
- Used Seaborn for cleaner and more visually appealing plots
- Compared Seaborn and Matplotlib in code comments

---

### 🔹 Task 4 — Machine Learning with Scikit-learn
- Selected features: subject scores, attendance, study hours
- Target variable: pass/fail
- Split dataset into training (80%) and testing (20%)
- Scaled features using `StandardScaler`
- Trained Logistic Regression model
- Evaluated model using training and test accuracy
- Printed predictions with student names and correctness
- Extracted and visualized feature importance
- Predicted outcome for a new student with probability

---

## 🛠 Technologies Used
- Python (Core + Data Science)
- Google Colab (Jupyter Notebook)
- Pandas for data analysis
- Matplotlib for plotting
- Seaborn for advanced visualization
- Scikit-learn for machine learning

---

## ▶️ How to Run
1. Open `part4_visualization_ml.ipynb` in Google Colab
2. Ensure `students.csv` is uploaded in the same environment
3. Run all cells sequentially
4. View outputs, plots, and model results

---

## ✅ Notes
- Dataset is small (15 students), so model accuracy may vary
- All plots are saved as `.png` files
- Code is well-commented for clarity
- Machine learning workflow implemented end-to-end

---

## 📁 File Structure
