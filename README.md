Markdown
# 🌍 World Inequality in Education - UNESCO Studies

## 📌 Project Overview
This project is a data analysis ("Fil Rouge") study investigating global educational inequalities using UNESCO datasets. It explores how education completion and transition rates are impacted by geographic regions, household wealth, and how they have evolved over the last two decades (2000–2022).

## 📊 Key Areas of Analysis
- **Regional Disparities:** Comparing primary, lower secondary, and upper secondary completion rates across regions like Northern America, Sub-Saharan Africa, and Southern Asia.
- **Wealth Inequality:** Analyzing the steady correlation between household wealth quintiles and education completion rates.
- **Time Trends (2000-2022):** Tracking global transition rates and historical spikes in education milestones.
- **Statistical Testing:** Applying statistical methods (e.g., ANOVA) to find significant differences between various data groups.

## 📂 Project Structure
```text
├── Dashboard/                 # Application files for the interactive dashboard
├── Notebooks/                 # Jupyter Notebooks for data cleaning, EDA, and statistics
├── Reports and dashboards/    # Exported reports and presentation visuals
├── SQL serveur/               # SQL scripts for database querying and management
├── generated_data/            # Cleaned and processed datasets ready for analysis
├── raw data/                  # Original raw UNESCO datasets
├── requirement.txt            # Python dependencies required to run the project
└── README.md                  # Project documentation
🛠️ Tools & Technologies
Language: Python, SQL

Data Manipulation: Pandas, NumPy

Statistical Analysis: SciPy (scipy.stats)

Data Visualization: Matplotlib, Seaborn

Environment: Jupyter Notebooks, VS Code

🚀 How to Run the Project Locally
1. Clone the repository:

Bash
git clone [https://github.com/Oussama-33v/World-inequality-on-education-UNESCO-studies-fill-rouge-project-.git](https://github.com/Oussama-33v/World-inequality-on-education-UNESCO-studies-fill-rouge-project-.git)
cd World-inequality-on-education-UNESCO-studies-fill-rouge-project-
2. Create and activate a virtual environment:

On Windows:

Bash
python -m venv venv
venv\Scripts\activate
On Mac/Linux:

Bash
python3 -m venv venv
source venv/bin/activate
3. Install required dependencies:

Bash
pip install -r requirement.txt
4. Explore the Analysis:

Open the Notebooks/ directory to view the Exploratory Data Analysis (EDA).

Check the Dashboard/ folder to launch the interactive visualizations.