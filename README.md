

# Rapido-Bangalore-RideSharing-Analysis

![Rapido Data Analysis & Business Intelligence Dashboard](https://github.com/sumitgaikwad01/Rapido-Bangalore-RideSharing-Analysis/raw/main/Executive%20Overview.png)

This project involves a comprehensive end-to-end data analysis of Rapido’s ride-sharing operations in Bangalore. Using Power BI, I transformed raw transactional data into five specialized dashboard pages to monitor KPIs, optimize route efficiency, and analyze revenue streams.

The goal was to provide actionable insights into service demand, driver efficiency, and payment trends to help stakeholders make data-driven decisions.

## 📊 Key Insights & Features

1. **Executive Overview**
    * **KPI Tracking:** Real-time visibility into Total Revenue (₹24.61M), Average Fare (₹547), and Gross Bookings (50K).
    * **Revenue Growth:** A time-series analysis showing a steady upward trajectory from June to August 2024.
    * **Top Performers:** Identified **Kothanur Landing** as the highest revenue-generating source (₹11K).

---

![Service](https://github.com/sumitgaikwad01/Rapido-Bangalore-RideSharing-Analysis/raw/main/Service%20Performance.png)

2. **Service Performance**
    * **Volume Leader:** The **Bike service** leads ride volume (~15K rides), followed by Auto.
    * **Cancellation Analysis:** Identified that Bikes experience the highest cancellation volume, signaling a need for better driver-partner retention or incentive structures in that segment.
    * **Fare Consistency:** Analyzed fare premiums across services, showing a stable average across Auto, Bike, and Cab Economy.

---

![Geographical Analysis](https://github.com/sumitgaikwad01/Rapido-Bangalore-RideSharing-Analysis/raw/main/Geographical%20Analysis.png)

3. **Geographical & Route Analysis**
    * **Demand Hotspots:** Mapped leading demand sources vs. top destinations. **Gottigere Landing** emerged as the top destination for completed rides.
    * **Network Scale:** Managed analysis for over 13K unique destinations and sources.

---

## 💡 Strategic Business Recommendations

Based on the data patterns identified in the dashboard, the following actions are recommended:

* **Incentivize High-Demand Zones:** Implement "Peak Hour Incentives" for drivers in high-cancellation zones like **Rajarajeshwari Nagar 5th Block** to reduce ETAs and improve fulfillment rates.
* **Optimize Vehicle Distribution:** Launch a "Return Journey" promotion for drivers ending trips in **Gottigere** to encourage them to head back toward high-demand hubs like **Kothanur**.
* **Payment Partnership:** Since revenue is evenly split across GPay, Paytm, and Amazon Pay, Rapido could negotiate lower transaction fees by consolidating volume through exclusive cashback partnerships.

## 🛠️ Tech Stack
* **Data Visualization:** Power BI Desktop
* **Data Processing:** Power Query 
* **Calculations:** DAX (Data Analysis Expressions) for complex measures like Revenue Growth Trajectory and Average Fare Premium.
* **Design:** Custom UI/UX layout with a consistent color theory for professional reporting.

## 🚀 How to Use
1. Clone this repository.
2. Download and install [Power BI Desktop](https://powerbi.microsoft.com/).
3. Open the `.pbix` file to interact with the filters (Slicers) for Date, Service Type, and Ride Status.
