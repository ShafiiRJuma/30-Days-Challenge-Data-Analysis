**Day:** 6  
**Date:** 2024-11-13  
**Tools Used:** Microsoft Excel Pivot Table  
**Dataset:** [Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)

### Challenge Overview
Yesterday, I created a simple dashboard with two charts. Today, I aimed to make the challenge more realistic by building a dashboard that could be useful in a real-world scenario. This was challenging and required watching some YouTube videos to understand how to bring all the shapes and data together. I believe consistency is key, and each day, adding to my knowledge will improve my skills in creating visually compelling dashboards.

The dataset contained sales data for a company but provided no guidance on what kind of dashboard to create. This required figuring out what data to display and which charts to use to best communicate the information.

![Sales Data](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DaySixScreenshots/SalesDataRaw.jpg)

### Steps

**Step 01: Dataset Exploration**  
I started by exploring the dataset in Excel, viewing all columns to understand the data. I created a copy to preserve the original and identified objectives for my dashboard:
1. Show total sales.
2. Show the total number of products shipped.
3. Display the current number of clients.
4. Track yearly sales growth (sales data is from 2003, 2004, and 2005).
5. Highlight top customers by sales.
6. Display top countries by sales.
7. Identify top products by sales.
8. Show product status (e.g., canceled, on hold, disputed, resolved, in process).

**Step 02: Data Cleaning**  
With objectives in mind, I focused on relevant columns and identified issues to address:
1. **Inconsistent phone number formatting**: Although phone numbers weren’t crucial for the dashboard, I standardized them by removing characters like “.”, “-”, “()” and formatting them in the U.S. phone number style.

   ![Phone Number Format](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DaySixScreenshots/SalesDataPhoneNumberFormat1.jpg)

2. **Concatenating customer names**: To avoid confusion where customers might share the same first name, I created a "Full Name" column by combining first and last names.
3. **Territory adjustments**: EMEA and APAC regions were clearly labeled, but AMER was indicated as "NA." I updated this to "AMER" for consistency.

   ![Territory Formatting](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DaySixScreenshots/SalesDataTerritoryFormatting.jpg)

4. **Checking for duplicates or blanks**: There were no duplicate entries or empty cells in key columns.
5. **Removing irrelevant columns**: I deleted the "Address Line 2" column as it had little data and wasn’t useful for the dashboard.

**Step 03: Dashboard Interface Design**  
With the cleaned data, I planned the dashboard layout by sketching it on paper, then recreating it in Excel using shapes. I refined the design to make it visually appealing and functional.

   ![Dashboard Interface](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DaySixScreenshots/SalesDataDashBoardInterface1.jpg)

**Step 04: Summarizing Data with Pivot Tables**  
Next, I used PivotTables to summarize key metrics for the dashboard and created PivotCharts for data visualization.

**Step 05: Linking PivotTables to the Dashboard**  
Linking data from PivotTables to the dashboard proved challenging, requiring several YouTube tutorials to understand the process. Ultimately, I succeeded in building the dashboard. Going forward, I aim to focus on creating visually stunning and creatively designed dashboard interfaces.

   ![Final Excel Dashboard](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DaySixScreenshots/SalesDataDashboard.jpg)

### Learning Outcome
This experience taught me a lot about building dashboards in Excel and creating visual layouts. I learned to think critically about the data and understand how it can communicate valuable business insights, which is essential in data analytics. Tomorrow’s challenge will focus on creating an interactive dashboard with dynamic, linked data.
