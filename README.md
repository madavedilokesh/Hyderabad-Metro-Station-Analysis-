# 🚇 Hyderabad Metro Station Analysis

## 📌 Project Overview

The **Hyderabad Metro Station Analysis** project focuses on analyzing station-level metro data to understand **ticket revenue, passenger movement, operational performance, and customer experience**.

The project follows a complete data analytics workflow:

**Raw Data → Data Cleaning → Exploratory Data Analysis → Power BI Dashboard → Business Insights & Recommendations**

The main objective is to transform raw metro data into meaningful insights that can support better **revenue planning, resource allocation, operational efficiency, infrastructure planning, and passenger experience**.

---

## 🎯 Business Problem

Hyderabad Metro needs to efficiently manage passenger demand, ticket revenue, station infrastructure, and customer experience.

This project aims to answer questions such as:

- Which stations generate higher or lower ticket revenue?
- Which stations have higher passenger movement?
- How does ticket revenue vary across different periods?
- Which stations have higher customer complaints?
- How does waiting time vary across stations?
- What operational areas may require improvement?
- Where should management focus resources and infrastructure?

---

## 📂 Dataset

The dataset contains station-level information related to:

- Station Name / Address
- Ticket Revenue
- Passenger Entries
- Passenger Exits
- Total Passenger Movement
- Complaints
- Average Waiting Time
- Average Trip Time
- Train Delays
- Station Rating
- Day Type
- Direction
- Observation Date
- Station Facilities
- Other operational and environmental attributes

---

## 🧹 Data Cleaning

Python was used to clean and prepare the raw dataset.

### Major Data Cleaning Steps

1. Imported the required Python libraries.
2. Loaded the raw CSV dataset.
3. Checked dataset shape, columns, data types, and basic information.
4. Checked unique values for categorical variables.
5. Standardized column names.
6. Cleaned unwanted Unicode characters.
7. Converted date columns into proper datetime format.
8. Identified missing values using counts and percentages.
9. Checked and removed duplicate records.
10. Identified potential numerical outliers using box plots.
11. Used **station-wise median imputation** for selected numerical variables.
12. Used **station-wise mean imputation** for continuous numerical variables.
13. Used **station-wise mode imputation** for categorical variables.
14. Converted Ticket Revenue into the appropriate numerical format.
15. Used the **IQR method** to identify and filter extreme Ticket Revenue values.
16. Performed a final null-value and dataset-shape check.

### Why Station-Wise Imputation?

Different metro stations can have different passenger patterns and operating conditions.

Therefore, station-wise mean, median, or mode was used where appropriate instead of applying one value across the entire dataset.

---

## 📊 Exploratory Data Analysis

After data cleaning, Exploratory Data Analysis (EDA) was performed to understand patterns, relationships, and trends in the dataset.

### Key EDA Areas

- Passenger movement by station
- Passenger movement by day type
- Passenger movement over time
- Ticket revenue analysis
- Passenger movement vs ticket revenue
- Train delay analysis
- Weather vs passenger movement
- Passenger entries vs exits
- Complaints analysis
- Waiting time analysis
- Trip time analysis
- Hourly revenue and passenger patterns

EDA helped identify important business patterns that were later represented through the Power BI dashboard.

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was developed using the cleaned dataset.

### Dashboard Pages

#### 1. Hyderabad Metro Overview

Provides an overall view of:

- Total Stations
- Total Ticket Revenue
- Total Passenger Movement
- Total Complaints
- Average Waiting Time
- Average Trip Time

It also includes station, day type, direction, year, and month filters.

#### 2. Revenue Analysis

Focuses on:

- Total Ticket Revenue
- Average Ticket Revenue
- Highest Station Revenue
- Revenue per Station
- Monthly Revenue
- Station-wise Revenue
- Revenue by Day Type
- Revenue by Direction
- Revenue vs Passenger Movement

#### 3. Operational / Passenger Analysis

Focuses on:

- Passenger movement
- Station-wise demand
- Day-wise passenger patterns
- Direction-wise passenger movement
- Waiting time
- Trip time
- Operational performance

#### 4. Customer Experience & Station Performance

Focuses on:

- Customer complaints
- Complaints per station
- Average waiting time
- Average trip time
- Passenger movement vs complaints
- Station performance

---

## 💡 Key Business Insights

The analysis helps management understand:

- Passenger demand is not equally distributed across all stations.
- Revenue contribution varies from station to station.
- High passenger activity can require better crowd and resource management.
- Stations with higher complaints may require further operational investigation.
- Waiting time and trip time can help identify areas for operational improvement.
- Station-level facility information can support infrastructure planning.

---

## 🚀 Business Recommendations

Based on the analysis:

- Prioritize high-demand stations for better crowd and staff management.
- Investigate stations with comparatively higher customer complaints.
- Monitor station-wise ticket revenue to identify revenue gaps.
- Review waiting-time performance and improve operational efficiency.
- Plan infrastructure based on passenger demand.
- Improve facilities such as parking, bus connectivity, lifts, escalators, and gates where required.
- Use the Power BI dashboard for continuous performance monitoring.

---

## 🔮 Future Improvements

The project can be further improved by:

- Integrating real-time metro data.
- Adding automated alerts for high passenger demand and complaints.
- Adding advanced forecasting for passenger movement and ticket revenue.
- Integrating weather, holidays, events, and traffic data.
- Developing a mobile-friendly dashboard.
- Implementing continuous data refresh for real-time monitoring.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Python** | Data Cleaning & EDA |
| **Pandas** | Data Manipulation |
| **NumPy** | Numerical Operations |
| **Matplotlib** | Data Visualization |
| **Seaborn** | Statistical Visualization |
| **Power BI** | Interactive Dashboard |
| **DAX** | Measures & Calculations |
| **Power Query** | Data Transformation |

---

## 📁 Project Structure

```text
Hyderabad-Metro-Station-Analysis/
│
├── Data/
│   ├── Raw Dataset
│   └── Cleaned Dataset
│
├── Python/
│   ├── Data Cleaning Notebook
│   └── EDA Notebook
│
├── Power BI/
│   └── Hyderabad Metro Dashboard.pbix
│
├── Documentation/
│   └── Project Documentation.pdf
│
└── README.md
```

---

## 📌 Project Outcome

This project demonstrates how raw metro data can be transformed into actionable business insights through **data cleaning, exploratory data analysis, and interactive visualization**.

The final dashboard provides management with a clear view of **revenue, passenger demand, operational performance, customer complaints, and station performance**, supporting data-driven decision-making.

---

## 👤 Author

**Lokesh Madavedi**

**Aspiring Data Analyst | Data & Analytics**

📍 Hyderabad, Telangana, India

🔗 GitHub: [github.com/madavedilokesh](https://github.com/madavedilokesh)

🔗 LinkedIn: [linkedin.com/in/lokesh-madavedi](https://www.linkedin.com/in/lokesh-madavedi)

---

## ⭐ If you find this project useful

Feel free to explore the project, review the analysis, and share your feedback.
