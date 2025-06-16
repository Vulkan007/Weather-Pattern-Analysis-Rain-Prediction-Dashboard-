
# 🌦️ Weather Pattern Analysis & Rain Prediction Dashboard

This project performs exploratory data analysis (EDA) and data quality assessment on historical weather datasets to uncover patterns influencing rainfall. The outputs are used to generate analytical tables for Power BI dashboards, enabling insights into rainfall trends, regional variations, and environmental risk factors.

---

## 📁 Project Overview

**Objectives:**
- Analyze historical weather data to identify patterns and predictors of rainfall.
- Segment locations based on average temperatures, rainfall levels, and sunshine exposure.
- Prepare clean and insightful summary tables for dashboard reporting in Power BI.

**Key Features:**
- EDA using Python (Pandas, NumPy)
- Cleaned and bucketed weather features (rainfall levels, wind directions)
- Multiple summary outputs:
  - Location-wise weather metrics
  - Rain prediction breakdown
  - Wind impact analysis
  - Missing data heatmap-ready table
- Exportable outputs in Excel and CSV for dashboard integration

---

## 🛠️ Tools Used

- **Python**: Data processing and summarization
- **Pandas**: Aggregation and transformation
- **Power BI**: Dashboard creation
- **Jupyter Notebook / VS Code**: Development environment

---

## 📊 Outputs

Generated data summary files:
- `location_summary.csv`: Average temperatures and rainfall by location
- `rain_tomorrow_distribution.csv`: Rain occurrence distribution
- `rainfall_vs_sunshine.csv`: Sunshine levels segmented by rainfall amount
- `wind_impact_on_rain.csv`: Wind gust direction vs rain probability
- `missing_data_summary.csv`: Percentage of missing data for quality control
- ![image](https://github.com/user-attachments/assets/b4a03480-ab3a-4cfb-9df2-a24f2681778a)


---

## 🚀 How to Use

1. Clone this repository:
   
   git clone https://github.com/Vulkan007/weather-dashboard-analysis.git
   cd weather-dashboard-analysis


2. Install dependencies:

   
   pip install pandas numpy xlsxwriter


3. Run the script:


   python weather_summary.py
 

4. Import the generated CSVs or Excel into Power BI for visualization.

---

## 📈 Sample Dashboards

* Regional weather trends by location
* Rainfall and sunshine correlation visual
* Wind pattern impact on rain likelihood
* Missing data heatmap for data quality review

---

## 📬 Contact

For questions or collaboration opportunities:
Suryansh – suryansh9566@gmail.com


---

## 📄 License

This project is licensed under the MIT License.
