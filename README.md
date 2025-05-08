
# COVID-19 Global Data Tracker

A Python-based data analysis project to visualize and explore global COVID-19 trends.

## 📊 Features
- Time series analysis of total cases, deaths, and vaccinations
- Comparison of selected countries
- Choropleth map for global case density
- Markdown summaries for insights

## 🛠️ Tools & Libraries
- pandas
- matplotlib
- seaborn
- plotly
- Jupyter Notebook

## 📁 Project Structure
```
covid19-global-data-tracker/
├── data/                    # Raw COVID-19 dataset (e.g. owid-covid-data.csv)
├── notebooks/              # Jupyter Notebooks for analysis
│   └── covid19_analysis.ipynb
├── outputs/                # Generated plots and map HTML
├── reports/                # Optional PDF or Markdown summary reports
├── requirements.txt        # Python packages
├── README.md               # Project overview and instructions
└── .gitignore              # Ignore virtual envs, data cache, etc.
```

## 🚀 How to Run
1. Clone this repository
2. Download the dataset from [Our World In Data](https://github.com/owid/covid-19-data/tree/master/public/data) and save as `owid-covid-data.csv` in `/data`
3. Run the Jupyter Notebook in `notebooks/covid19_analysis.ipynb`

## 📌 Insights
- The US experienced the most total COVID-19 cases.
- India's vaccine rollout picked up strongly mid-2021.
- Kenya maintained a relatively low death rate.

## 📜 License
MIT

