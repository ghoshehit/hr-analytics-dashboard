# 🚀 HR Analytics: Predictive Flight Risk Engine

### 📊 Overview
This project is a specialized Data Analytics tool designed to identify potential "Flight Risks" within an organization. By analyzing employee performance and engagement metrics, the engine flags individuals who are statistically likely to resign, allowing HR to move from reactive hiring to proactive talent retention.

### 🧠 The Risk Scoring Model
The system uses a weighted logic algorithm built in Python to calculate a risk score (0-100) based on three primary corporate triggers:

* **Burnout Trigger (40 pts):** Flagged for employees exceeding **200 monthly hours**.
* **Stagnation Trigger (35 pts):** Flagged for employees with **>24 months** since their last promotion.
* **Disengagement Trigger (25 pts):** Flagged for employees with an **Engagement Score below 50%**.

### 🛠️ Tech Stack
* **Language:** Python 3.14
* **Data Library:** Pandas (for high-speed data frame manipulation)
* **Environment:** Visual Studio Code
* **Version Control:** Git & GitHub

### 📂 Project Structure
* `data/`: Contains `employees.csv` (The raw employee dataset).
* `Scripts/`: Contains `predict_risk.py` (The Python analytical engine).
* `web/`: (Future Scope) React-based dashboard for visualizing risk trends.

### 🚀 How to Execute
1. Clone the repository to your local machine.
2. Ensure the `pandas` library is installed via terminal: `pip install pandas`.
3. Run the analysis: `python Scripts/predict_risk.py`.
4. Review the **Risk Status** column in the terminal output.
