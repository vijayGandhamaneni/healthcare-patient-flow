# 🏥 Healthcare Patient Flow Optimization

**Short summary:**  
End-to-end data analysis project using **Python (Pandas, Matplotlib, Seaborn)** and **Power BI** to analyze hospital patient flow, identify bottlenecks (wait times, peak hours), and provide actionable recommendations to improve efficiency.

---

## 📌 Project Goal
Analyze hospital patient records to:
- Find departments with high waiting times
- Identify peak admission hours
- Measure average patient stay duration
- Provide recommendations to improve patient throughput and resource allocation

---

## 🛠️ Tools & Technologies
- Python — Pandas, NumPy, Matplotlib, Seaborn  
- Jupyter Notebook (runable in VS Code)  
- Power BI Desktop (for dashboard visualizations)  
- Git & GitHub (project hosting)

---

## 📁 Project Structure
healthcare-patient-flow/
│
├── data/
│ ├── data.csv # Raw synthetic dataset (500 patients)
│ └── cleaned_hospital_data.csv # Cleaned dataset used for dashboard
│
├── notebooks/
│ └── healthcare_analysis.ipynb # Jupyter Notebook: cleaning, EDA, charts
│
├── dashboard/
│ └── dashboard.png # Power BI dashboard screenshot
│
└── README.md


---

## 🔎 What I did (workflow)
1. **Data creation / collection** — created a synthetic hospital dataset (500 records) to simulate admissions, wait times, discharge times, departments, doctors, and ages.  
2. **Data cleaning** — converted date/time columns, removed duplicates, handled missing values, normalized text fields.  
3. **Exploratory Data Analysis (EDA)** — computed average wait times by department, admissions by hour, stay duration, doctor workloads, and other aggregates.  
4. **Visualization** — produced charts (barplot, boxplot, histogram) using Matplotlib/Seaborn; built a Power BI dashboard for stakeholders.  
5. **Insights & recommendations** — summarized findings and suggested operational improvements.

---

## 📊 Key Findings (example)
- **Cardiology** and **Emergency** departments show the highest average wait times.  
- Peak admission hours are **9 AM – 11 AM** (morning rush).  
- Average patient stay duration is around **~6–7 hours** (depends on generated data).  
- Some doctors see more patients than others — balance staffing where needed.

---

## ✅ Recommendations
- Add extra staff (doctors/nurses) during morning peak hours in high-wait departments.  
- Improve registration triage during 9–11 AM to reduce queues.  
- Schedule non-urgent appointments in off-peak times.  
- Monitor wait-time KPIs and run periodic EDA to track changes.

---

## ▶️ How to run this project locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/vijayGandhamaneni/healthcare-patient-flow.git
   cd healthcare-patient-flow
(Optional) Create virtual environment & install dependencies

bash
Copy code
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

pip install pandas numpy matplotlib seaborn jupyter
Open the notebook

Open notebooks/healthcare_analysis.ipynb in VS Code (or Jupyter).

Run cells top-to-bottom to reproduce data creation, cleaning, EDA, and charts.

Power BI dashboard

Use data/cleaned_hospital_data.csv as the data source in Power BI Desktop to build the dashboard (or open the .pbix if available).

Export a screenshot (dashboard/dashboard.png) to show in the repo.

🧾 Files to check
notebooks/healthcare_analysis.ipynb — the main notebook with code and explanations.

data/data.csv — original synthetic data (500 rows).

data/cleaned_hospital_data.csv — cleaned dataset exported from the notebook.

dashboard/dashboard.png — Power BI screenshot for quick preview.

✍️ How to cite / use
You can reuse the notebooks and CSV files for learning or as a template — please give credit if you reuse substantial parts in public projects.

👤 Author

Vijay Kiran Chowdary Gandhamaneni