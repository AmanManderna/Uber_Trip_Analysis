# 🚕 Uber Trips Dashboard (January–February)

This project presents an interactive Tableau dashboard that analyzes Uber trip data for the months of January and February. The goal is to explore trends in trip frequency, vehicle activity, and base performance to derive actionable insights.

## 📊 Dashboard Overview

The dashboard includes multiple visualizations such as:

- **Total Trips Over Time** (line chart)
- **Trips by Weekday and Base** (heatmap)
- **Active Vehicles Trend** (line chart)
- **Trips per Base** (bar chart)
- **Average Trips per Vehicle** (calculated line chart)
- **Monthly and Weekday Comparisons**
- **Interactive filters for Base, Date, and Weekday**

The dashboard is built using Tableau and can be opened with Tableau Public or Tableau Desktop.

## 📁 Files Included

| File | Description |
|------|-------------|
| `Uber_Trips_Dashboard.twbx` | Tableau packaged workbook with all visualizations |
| `Uber-Jan-Feb-Cleaned.xlsx` | Cleaned data used in Tableau |
| `uber_eda_cleaning.ipynb` | Jupyter Notebook for EDA and data cleaning |
| `README.md` | Project overview and documentation |

## 🧹 Data Cleaning & EDA (Jupyter Notebook)

Initial data exploration and cleaning were done using **Python** in a Jupyter Notebook. Key steps included:

- Loading raw Uber trip data (CSV format)
- Parsing `Date/Time` column into structured `Date`, `Day`, `Month`, and `Weekday` fields
- Handling missing values and ensuring numeric formats for `Trips` and `Active Vehicles`
- Aggregating trip data for exploratory analysis
- Saving the cleaned dataset to `Uber-Jan-Feb-Cleaned.xlsx` for use in Tableau

Python libraries used:
- `pandas`
- `numpy`
- `matplotlib` and `seaborn` for EDA plots

## 📈 Tableau Visualizations

Tableau was used to visualize and analyze the cleaned data. Key features include:

- **Interactivity**: Filters for Base, Date, and Weekday
- **Calculated Fields**: Average trips per vehicle
- **Dual-axis charts** and **highlight tables**
- **Custom color schemes** and **dashboard layout**
  
## 📊 Insights

Some interesting findings from the dashboard:

- **Weekdays** tend to have higher trip volumes than weekends
- Certain **dispatch bases** dominate trip activity
- **Trips per vehicle** tend to dip slightly on weekends
- Clear growth in trip volume from January to February

## 📂 How to Use

1. Download `Uber_Trips_Dashboard.twbx`
2. Open it in Tableau Desktop or Tableau Public
3. Use filters and interact with charts for custom views

## 🧠 Future Improvements

- Integrate March–April data for extended trend analysis
- Incorporate map-based geo visualizations (if coordinates are available)
- Predictive modeling for trip forecasting in Python

## 🛠 Tools Used

- **Python (Jupyter Notebook)** – Data cleaning & EDA
- **Tableau** – Data visualization and dashboarding
- **GitHub** – Project version control and sharing

## 📬 Contact

For questions or collaboration, feel free to reach out via GitHub Issues or open a pull request.

