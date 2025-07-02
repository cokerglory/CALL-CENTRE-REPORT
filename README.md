
# Exploratory-Call Centre Data Analysis in Excel

Call centre performance analysis with excel.

This project explores the performance of a call centre using historical call records.


## Dataset description
source : Youtube (https://chandoo.org/wp/free-call-centre-dashboard/)

Columns :15,
Rows:1000+
### 🔑 Key Columns

| Column Name         | Description |
|---------------------|-------------|
| `Customer ID`           | Unique identifier for each call |
| `Agent_ID`          | ID of the call agent |
| `Call_Start_Time`   | Timestamp of when the call started |
| `Call_End_Time`     | Timestamp of when the call ended |
| `Call_Duration`     | Duration of call in minutes |
| `Issue_Type`        | Category of customer issue |
| `Resolution_Status` | Resolved or Unresolved |
| `Customer_Satisfaction_Score` | Rating from 1 t

## 🔍 Exploratory Steps

1. **Initial Data Exploration**
   - Conducted a preliminary review of the dataset structure and fields
   - Identified relevant columns and cleaned inconsistent entries
   - Assessed available dashboard assets (images, logos, etc.)

2. **Design Setup**
   - Defined a consistent color scheme and selected appropriate fonts for a clean, readable layout
   - Chose a layout grid and visual hierarchy for dashboard elements

3. **Data Modeling**
   - Created pivot tables to summarize key metrics
   - Structured the data model and established relationships between tables (e.g., calls, agents, customers)

4. **DAX Measures Creation**
   - Developed calculated measures for key performance indicators such as:
     - Total Calls
     - Resolution Rate
     - Average Call Duration
     - Customer Satisfaction Score
     - Revenue per Customer

5. **Dashboard Construction**
   - Built interactive KPI tiles to highlight headline stats
   - Plotted a **Calls Trend Line Chart** to visualize volume over time
   - Added a **Weekday Trend Bar Chart** to show daily traffic patterns
   - Created a **Dynamic Chart for Calls & Revenue by Agent**
   - Integrated demographic-based insights using:
     - **Calls by Customer Demographics**
     - **Rating Distribution Histogram**
     - **Customer Revenue Table**

6. **Dashboard Polishing**
   - Styled slicers and applied conditional formatting (e.g., data bars)
   - Enabled row highlighting for selected agents
   - Displayed the selected agent’s profile picture dynamically for a personalized touch






