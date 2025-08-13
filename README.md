# COVID-19 Global Data – Data Analysis Project

## 📄 Project Overview

This project is a data analysis case study performed in a **Jupyter Notebook** for portfolio purposes. 
The dataset contains detailed information on COVID-19 cases, deaths, vaccinations, and demographic data for countries worldwide. 
The objective was to clean, analyze, and visualize the data to uncover key trends and create interactive dashboards for exploration.

---

## 📂 Project Structure

* **Jupyter Notebook** - Contains all Python code for data cleaning, analysis, and visualization.
* **Raw Data** - A single CSV file (`COVID_19_Data.csv`) containing the raw dataset.
* **Visualizations & Dashboards** - Interactive elements are generated directly within the notebook using Plotly and Dash.

---

## 🛠 Data Cleaning and Preparation

The following steps were performed to prepare the dataset for analysis:

| Step | Action                       | Description                                                                                           |
| ---- | ---------------------------- | ----------------------------------------------------------------------------------------------------- |
| 1    | **Data Loading**             | Loaded the initial dataset from the `COVID_19_Data.csv` file.                                           |
| 2    | **Formatting Verification**  | Standardized data types, converting the date column to datetime objects and population to integers.   |
| 3    | **Handling Missing Data**    | Inspected the dataset for NaN values to understand data completeness.                                 |
| 4    | **Data Integrity Check**     | Checked for and handled any duplicate rows to ensure data accuracy.                                   |
| 5    | **Final Dataset Creation**   | The cleaned and prepared DataFrame was used for all subsequent analysis and visualization.            |

---

## 📊 Analysis & Findings

Used Pandas for data aggregation and Plotly/Seaborn for visualization to explore the data.

* Identified population trends by visualizing the top 10 most populous countries.
* Examined the correlation between population and life expectancy for the top 20 most populous nations.
* Analyzed the geographical distribution of COVID-19 cases with a world map showing cases per 1,000 people.
* Compared the pandemic's progression by plotting the timeline of new cases in Poland versus Germany.

---

## 🔍 Interactive Dashboards

Three interactive dashboards were developed using Dash to provide deeper, dynamic insights:

**Dashboard 1 – Cumulative Data by Country**

* **Summary** - An interactive dashboard that displays the cumulative cases and deaths for any selected country over time.
* **Conclusion** - Allows for a clear, direct comparison of the pandemic's overall trajectory in different nations.

**Dashboard 2 – Global Statistics Map**

* **Summary** - A world map that visualizes key statistics (e.g., total cases, deaths, vaccinations) and can be filtered by continent.
* **Conclusion** - This tool effectively highlights regional differences and hotspots for various COVID-19 metrics.

**Dashboard 3 – Top Countries by Vaccination**

* **Summary** - This dashboard presents two bar charts showing the top N countries (selectable via a slider) by total vaccinations and by the ratio of vaccinations to population.
* **Conclusion** - Illustrates the difference between the sheer volume of vaccinations administered and the per-capita effectiveness of vaccination campaigns.

---

## ✅ Summary & Conclusions

* **Clean Data is Key** - Standardizing formats and handling inconsistencies made the dataset reliable and ready for robust analysis.
* **Feature Engineering Added Value** - Creating new columns, such as a formatted month-year date, enabled more effective time-series analysis.
* **Dynamic Visualizations Provide Clarity** - The interactive dashboards successfully translate complex data into understandable insights, allowing users to explore the data on their own terms.
* **Key Insights Highlighted** - The analysis revealed significant global disparities in case progression and vaccination efforts, and it demonstrated that population size alone does not determine life expectancy.

---

## 📎 Files in Repository

* `Project_2_COVID_19_Data.ipynb` – Complete project file with all Python code.
* `README.md` – Project description and methodology (this file).

---

## 💡 Tools Used

* **Python** - Primary language for data analysis.
* **Pandas** - For data cleaning, manipulation, and preparation.
* **Matplotlib & Seaborn** - For initial static visualizations.
* **Plotly & Dash** - For creating interactive charts and dashboards.

---
