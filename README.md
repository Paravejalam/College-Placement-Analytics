📊 Dashboards (Power BI)
📌 Page 1 — Placement Insights Dashboard

Includes:

Total Students, Placement Rate, Average CGPA

Placement by Domain

CGPA Distribution

Internships Distribution

Skills & Projects stats

Interactive filters (Domain, CGPA Range, Skills, Internships)

📌 Page 2 — Resume Insights Dashboard

Includes:

Predicted Placement Rate

Resume Strength Score

Average Skills / Average Projects

Skills vs CGPA Scatter Visualization

Skill Strength Distribution

Actual vs Predicted Placement

Overall Resume Readiness Gauge

Resume Insights Summary

🧠 Machine Learning Workflow
1️⃣ Data Preprocessing

Null value handling

String → Numeric conversion

Feature engineering

Outlier removal

Scaling & cleaning

2️⃣ Model Training

Algorithm used:

✔ Logistic Regression solver='liblinear'
✔ Stratified train-test split (80/20)

3️⃣ Evaluation Metrics

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

4️⃣ Predictions Export

Final dataset created:

➡️ placement_with_predictions.csv
Contains:

Original student data

Predicted placement (0/1)

Resume strength score

ML readiness score

This file is used by Power BI dashboards.

🛠️ Tech Stack
Python & ML

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Business Intelligence

Power BI

DAX Measures

Interactive Visualizations

📥 How to Run Locally
1️⃣ Clone Repository
git clone https://github.com/your-username/college-placement-prediction.git
cd college-placement-prediction

2️⃣ Install Requirements
pip install -r requirements.txt

3️⃣ Open Jupyter Notebooks
jupyter notebook


Run:

EDA_Notebook.ipynb → explore data

ML_Model_Notebook.ipynb → train & export predictions

4️⃣ Open Power BI File

Open:

powerbi/Placement_Dashboard.pbix


You will see both dashboards with full interactivity.

📈 Key Insights From the Model

🔹 Higher skills strongly increase placement probability
🔹 Students with 2+ internships show better outcomes
🔹 CGPA between 7.0–9.0 corresponds to highest placement
🔹 Resume strength score impacts ML prediction accuracy
🔹 Domain specialization produces different placement trends

🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first to discuss what you'd like to improve.

📜 License

This project is licensed under the MIT License.

⭐ If you liked this project

Please star ⭐ the repository!
It motivates me to build more end-to-end projects.