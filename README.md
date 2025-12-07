# ✈️ US Flight Delay Analysis (Tableau)

![Project Banner](images/dashboard_preview.png)

**Short description:**  
Tableau data visualization project analyzing the main causes of flight delays in the United States. The cleaned dataset comes from Kaggle and the visualizations were created in Tableau Desktop.

---

## 🔎 Project Overview
This project explores the drivers of flight delays in the US (2017–2022), focusing on categories such as: Arrival Delay, Carrier Delay, Late Aircraft, NAS, Security, and Weather. The goal is to identify dominant causes and temporal trends and present actionable insights for stakeholders.

---

## 📊 Dataset
- **Source:** Kaggle — `https://www.kaggle.com/datasets/jawadkhattak/us-flight-delay-from-january-2017-july-2022`  
- **File in this repo:** `data/Airline_Delay_Cause.xlsx`  
- **Time range:** 2017 – 2022  
- **Notes on cleaning:**  
  - Cleaned using Microsoft Excel (removed NA, standardized column names, aggregated monthly totals).  
  - No Python or external scripting used. Full cleaning steps are described below.

---

## 🧹 Data Cleaning Summary
(brief steps you performed — fill in)
1. Removed rows with missing key identifiers (flight_id, date)  
2. Standardized date format to YYYY-MM-DD and aggregated by month  
3. Converted delay columns to numeric and handled outliers by capping at 99th percentile  
4. Renamed columns to: `date`, `carrier`, `airport`, `arr_delay`, `carrier_delay`, `weather_delay`, `security_delay`, `late_aircraft_delay`, `nas_delay`  

---

## 🛠 Tools & Files
- **Tableau Desktop** — workbook: `Visualisasi Tableau/US_Flight_Delay.twb`  
- **Microsoft Excel** — cleaned dataset: `data/Airline_Delay_Cause.xlsx`  
- **Images (for README):** `images/dashboard_preview.png` (dashboard screenshot)

---

## 📈 Key Visuals & Insights
- **Arrival Delay** is the largest contributor to total delay across years.  
- **Carrier Delays** show seasonal peaks (holiday months).  
- **Weather Delays** smaller in magnitude but spike in extreme events.  
*(Add 2–3 bullet points with your actual findings; reference charts by screenshot names.)*

---

## 🖼 Dashboard Preview
![Dashboard Preview](dashboard-overview.png)

**If you want to view interactive version:**  
- (Recommended) Publish your workbook to Tableau Public and paste the public URL here: `<paste Tableau Public URL here>`  
  Example: `https://public.tableau.com/views/yourworkbookname`

---

## 📂 Repository Structure
