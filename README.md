# Walmart Sales Data Analysis Dashboard

## Project Overview
This repository contains a comprehensive data analysis and visualization project focused on Walmart's retail performance. [span_0](start_span)[span_1](start_span)The project utilizes a multi-page Power BI dashboard to explore the relationships between total sales and various socio-economic factors such as fuel prices, unemployment rates, Consumer Price Index (CPI), and temperature[span_0](end_span)[span_1](end_span).

## Key Insights & Metrics
[span_2](start_span)The analysis covers 45 store locations with a combined total sales volume of **6,737M**[span_2](end_span). 

### High-Level KPIs
* **[span_3](start_span)Total Sales:** 6,737M[span_3](end_span)
* **[span_4](start_span)Store Count:** 45[span_4](end_span)
* **[span_5](start_span)Average Fuel Price:** $3.36[span_5](end_span)
* **[span_6](start_span)Average Unemployment Rate:** 8.00%[span_6](end_span)
* **[span_7](start_span)Average Temperature:** 61°F[span_7](end_span)
* **[span_8](start_span)Average CPI:** $171.58[span_8](end_span)

---

## Dashboard Features

### 1. Sales Performance Analysis
* **[span_9](start_span)Time Series Trends:** Analysis of sales by Year, Quarter, and Month[span_9](end_span). [span_10](start_span)2011 showed a peak in annual sales at **2.45bn** compared to 2010 (**2.29bn**) and 2012 (**2.00bn**)[span_10](end_span).
* **Store Rankings:** Identification of top-performing stores. [span_11](start_span)[span_12](start_span)Store 20, Store 4, and Store 14 are among the highest contributors, with Store 20 leading at approximately **301M** in total sales[span_11](end_span)[span_12](end_span).
* **[span_13](start_span)Holiday Impact:** Comparison of sales during "Vacation" vs. "No Vacation" periods, showing that the vast majority of sales (**92.5%** or 6.23bn) occur during non-vacation periods[span_13](end_span).

### 2. External Factor Correlation
The dashboard tracks how sales fluctuate alongside quarterly changes in:
* **[span_14](start_span)Fuel Prices:** Monitored from a low of $2.74 to a high of $3.85[span_14](end_span).
* **[span_15](start_span)Unemployment:** Trends showing a general decrease from 8.62% in early 2010 to 6.95% by late 2012[span_15](end_span).
* **[span_16](start_span)CPI:** Observation of steady growth in the Consumer Price Index from $167.77 to $176.61[span_16](end_span).
* **[span_17](start_span)Temperature:** Seasonal impacts on sales volume across different quarters[span_17](end_span).

---

## Data Structure
The analysis is based on a granular dataset including:
* **[span_18](start_span)Store Metrics:** Sales, Rank, and Average Sales per store[span_18](end_span).
* **[span_19](start_span)Temporal Data:** Year, Quarter, and Month[span_19](end_span).
* **[span_20](start_span)Environmental Data:** Temperature and Fuel Prices[span_20](end_span).

| Store ID | Total Sales | Avg. Sales | Rank | Avg. Unemployment |
| :--- | :--- | :--- | :--- | :--- |
| 20 | ~$301M | - | 1 | 7.37% |
| 4 | ~$299M | ~$2.09M | 2 | 5.96% |
| 14 | ~$289M | ~$2.02M | 3 | 8.65% |

---

## Technical Implementation
* **Tool:** Power BI
* **Visualizations Used:**
    * **[span_21](start_span)Cards:** For high-level KPI tracking[span_21](end_span).
    * **[span_22](start_span)Donut Charts:** For vacancy vs. non-vacancy sales distribution[span_22](end_span).
    * **[span_23](start_span)Treemaps:** To visualize top 15 store contributions[span_23](end_span).
    * **[span_24](start_span)Line & Bar Charts:** For monthly and quarterly trend analysis[span_24](end_span).
    * **[span_25](start_span)Slicers:** Interactive filtering by Year, Month, and Store ID[span_25](end_span).

## How to Use
1. Clone the repository.
2. Open the `.pbix` file (if provided) in Power BI Desktop.
3. [span_26](start_span)Use the **Year** and **Store** slicers on Page 1 to filter the entire report context[span_26](end_span).
4. [span_27](start_span)Navigate through pages to view specific correlation analyses (Fuel, CPI, Unemployment)[span_27](end_span).
