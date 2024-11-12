**Day:** 5  
**Date:** 2024-11-12  
**Tools Used:** Microsoft Excel for Dashboard Creation  
**Dataset:** [Most Streamed Spotify Songs 2023](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)

### Challenge Overview:
Today, I set out to build my first dashboard using the "Most Streamed Spotify Songs 2023" dataset. Given that I’m new to dashboarding, I approached it as a "simple challenge" and took things slowly. I followed along with this [YouTube tutorial](https://www.youtube.com/watch?v=MTlQvyNQ3PM), which provided a helpful guide. This experience has motivated me to dedicate the next few days to Excel dashboard practice so that I can master creating professional, visually appealing dashboards before transitioning to Power BI. 

My initial dashboard focused on two key insights:  
1. **Top 10 Streamed Artists**  
2. **Top 10 Streamed Songs**  

Here's a snapshot of my progress from raw data to a clean dashboard:  
![Before and After](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayFiveScreenshots/BEFORE%20(1).jpg)

### How I Built This Dashboard:
Creating dashboards in Excel relies heavily on understanding PivotTables, which allow you to organize data and add PivotCharts directly to your dashboard sheet, optimizing the layout for a clean, professional look.

#### **Step 1: Data Preparation**
I started by verifying and cleaning the dataset to ensure no errors were present. After this, I converted the data into a table, enabling easier sorting, filtering, and dynamic referencing for calculations like sums, averages, and counts.

![Dataset as Table](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayFiveScreenshots/SPTable.jpg)

#### **Step 2: Creating the PivotTable**
After converting to a table, I inserted a PivotTable in a new workbook to help organize and summarize the data effectively.

![Pivot Table](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayFiveScreenshots/SPPivotTable.jpg)

#### **Step 3: Filtering Top 10 Streamed Songs**
Using the PivotTable, I filtered the data to show only the top 10 most-streamed songs. This involved selecting "Track Name" and "Streams" and applying a filter for the top 10 songs.

![Filter Top 10 Songs](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayFiveScreenshots/SPFilterTop10.jpg)

#### **Step 4: Chart Selection**
Given the data I wanted to display, I selected a Bar Chart, which visually highlights the top 10 streamed songs effectively. To add this chart, I clicked on the PivotTable, went to "Pivot Table Analyze," and then chose a Bar Chart format.

![Choosing Chart Type](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayFiveScreenshots/SPAnalyzePivotTable.jpg)

#### **Step 5: Dashboard Creation**
I copied my newly created Bar Chart into a dedicated "Dashboard" sheet. I repeated these steps for the "Top Streamed Artists" to complete the dashboard, giving it a cohesive and user-friendly design.

### **Learning Outcome:**
Today’s practice gave me foundational experience in creating Excel dashboards using PivotTables and PivotCharts. I am now more confident in Excel’s dashboarding capabilities and excited to refine my skills in the coming days!
