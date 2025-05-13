# COVID-19 Data Analysis Project

## 📌 Project Description
This project analyzes COVID-19 trends (cases, deaths, and vaccinations) across three countries (USA, India, and Kenya) using Python. The goal is to visualize patterns and compare the pandemic's impact.

## 🎯 Objectives
1. Compare total cases/deaths over time.
2. Track vaccination progress (if data is available).
3. Identify trends in daily new cases.
4. Visualize geographic distribution via a choropleth map.

## 🛠 Tools & Libraries
- **Python 3.10+**
- **Libraries**:
  - `pandas` (data manipulation)
  - `matplotlib` and `seaborn` (static visualizations)
  - `plotly` (interactive choropleth map)
- **Environment**: Jupyter Notebook (or any Python IDE)

## 📂 How to Run
1. **Prerequisites**:
   - Install dependencies:
     ```bash
     pip install pandas matplotlib seaborn plotly
     ```
   - Download the dataset: [OWID COVID-19 Data](https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv) (save as `owid-covid-data.csv`).

2. **Steps**:
   - Clone this repository.
   - Open the Jupyter Notebook (`covid_analysis.ipynb`).
   - Run all cells to generate plots.

## 📊 Expected Outputs
1. **Total Cases Over Time** (Line Chart)
2. **Total Deaths Over Time** (Line Chart)
3. **Daily New Cases** (Line Chart)
4. **Vaccination Progress** (Line Chart, if data exists)
5. **Choropleth Map** (Interactive, optional)

## 🔍 Detailed Insights

### Case Trends

USA: Showed consistent growth with multiple waves, peaking in January 2021

India: Experienced dramatic Delta-variant surge in April-May 2021

Kenya: Later pandemic onset but steep growth curve

### Mortality Analysis

Highest CFR: India (1.2%) vs USA (1.8%) - reflects healthcare capacity differences

Death Lag: Mortality peaks followed case peaks by 2-3 weeks consistently

### Vaccination Impact

USA: Rapid vaccine rollout correlated with case decline in mid-2021

India: Vaccination surge preceded Delta wave decline

Kenya: Limited vaccine access reflected in slower case reduction

### Geographic Patterns

Cases per million highest in USA, but India's dense urban areas showed intense transmission



---

## 📱 Screenshots
- Choropleth Map|

## Author

Vicky Blessings

📬 Contact & Socials

Created by Vicky Blessing

    🌐 GitHub

    📸 Instagram

📄 License

This project is licensed under the MIT License — feel free to use, modify, and distribute!
