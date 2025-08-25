
# 🎓 Student Habits & Academic Performance Analysis

This project explores how different study habits, sleep patterns, and lifestyle choices influence student academic performance. By analyzing survey data from students, it aims to derive actionable insights for educators and learners to improve learning outcomes.

---

## 📁 Project Structure

* `student_habits_performance.csv`: Dataset containing responses from students on study patterns and grades.
* `student-data-analysis.ipynb`: Jupyter Notebook with data analysis, visualization, and insights.
* `README.md`: Documentation and project summary.

---

## 🧠 Objective

To analyze the relationship between students' daily habits—such as study time, screen time, sleep hours, and breakfast routine—and their academic performance, measured through self-reported grades.

---

## 📊 Dataset Overview

* **Rows**: *\[1000 students]*
* **Key Columns**:

  * `StudyHours`, `ScreenTime`, `SleepHours`
  * `TakesBreakfast`, `ClassParticipation`, `ExtraCurricular`
  * `Grade` (Academic performance level: A, B, C, etc.)

---

## ⚙️ Project Workflow

### 1. **Data Cleaning**

* Removed missing and duplicate records
* Converted categorical variables to numerical formats (e.g., Yes = 1, No = 0)

### 2. **Exploratory Data Analysis (EDA)**

* Visualized:

  * Distribution of grades by study hours
  * Screen time vs academic performance
  * Breakfast habits vs student grades
* Used bar plots, pie charts, and correlation heatmaps

### 3. **Insights Extraction**

* Identified key patterns affecting student performance
* Grouped by lifestyle categories and analyzed average grade

---

## 🏆 Key Insights

* Students who studied **3+ hours per day** were more likely to score A or B.
* **Excessive screen time (>4 hrs/day)** correlated with lower performance.
* **Taking breakfast daily** had a positive effect on academic outcomes.
* Balanced **sleep hours (6–8 hrs)** aligned with higher grades.

---

## 🛠 Tools Used

* `pandas`, `numpy` – data handling
* `matplotlib`, `seaborn` – visualizations
* `Jupyter Notebook` – analysis and documentation

---

## ✅ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/student-performance-analysis.git
   ```
2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Launch the notebook:

   ```bash
   jupyter notebook student-data-analysis.ipynb
   ```

---

## 🤝 Contributing

Contributions are welcome! Submit a pull request or open an issue for enhancements.

---
