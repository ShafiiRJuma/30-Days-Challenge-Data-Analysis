**Day:** 3  
**Date:** 2024-11-09  
**Tools:** Microsoft Excel Pivot Table  
**Dataset:** [Leading Causes Of Death in the United States](https://catalog.data.gov/dataset/nchs-leading-causes-of-death-united-states)

**Challenge Overview:**  
Today, I practiced using Pivot Tables in Microsoft Excel to analyze a dataset on leading causes of death in the United States. Building on the data cleaning skills I developed in previous challenges, I focused on using Pivot Tables to summarize the data, uncover patterns, and answer specific questions, such as identifying top causes of death nationally, per state, and over time. Pivot Tables provided an efficient way to explore key insights and trends directly from the data.

**Dataset Description**  
This dataset covers the age-adjusted death rates for the 10 leading causes of death in the United States, starting from 1999. It details each cause of death along with the recorded number of deaths per year. I chose this dataset to explore questions like: "What are the leading causes of death in the U.S.? Which causes are predominant by state? And what is the trend of each cause over time?"

**Challenge Steps:**
1. **Data Exploration and Preparation**  
   I began by downloading the data, loading it into Excel, and examining its structure. I reviewed columns, data types, row counts, and general formatting to gain an initial understanding of the data.

   ![Raw Data](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayThreeScreenshots/DRraw.jpg)

2. **Data Cleaning with Excel**  
   After familiarizing myself with the data, I proceeded to clean it. I checked for duplicates, blank cells, and inconsistent formatting. Since this dataset was pre-cleaned for analysis, it required minimal modification.

3. **Setting Up the Pivot Table**  
   I created a Pivot Table by navigating to **Insert > Pivot Table** and selecting my data range.

   ![Pivot Table](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayThreeScreenshots/DRPivotTable.jpg)

   With the table set, I could easily summarize data fields, analyze totals, and view key patterns by organizing fields in the Pivot Table interface.

4. **Analysis with Pivot Tables**  
   - **Leading Causes of Death in the United States**: I placed "Cause Name" in the rows and "Deaths" in the values, automatically calculating the total deaths by cause. This revealed that heart disease has consistently been the leading cause of death across the dataset.

     ![Leading Cause of Death](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayThreeScreenshots/DRPVCausesOverAll.jpg)

   - **Leading Causes of Death by State**: To explore this, I added "State," "Cause Name," and "Deaths" in the fields, allowing me to view the top causes of death for each state.

     ![Leading Causes of Death Per State](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayThreeScreenshots/DRLeadingCausesPerState1.jpg)

   - **Leading Causes of Death by Year**: I cleared previous selections and added "Year," "Cause Name," and "Deaths" to see the primary causes of death each year from 1999 onwards.

     ![Leading Causes of Death Per Year](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayThreeScreenshots/DRPVLeadingDeathCausesPerYear.jpg)

5. **Trend Analysis of Heart Disease Deaths**  
   Observing that heart disease was a major cause of death, I examined its trend over the years. By filtering for "Heart Disease" in "Cause Name" and plotting "Year" and "Deaths," I created a chart that displayed this trend.

   ![Heart Disease Trend](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayThreeScreenshots/DRPVDeathHearDisease.jpg)

**Conclusion:**  
Pivot Tables proved invaluable in summarizing and visualizing complex datasets. By allowing dynamic field manipulation, they enabled me to explore meaningful insights about health trends in the U.S. Moving forward, Pivot Tables will be a key tool in my data analysis toolkit for efficiently answering questions and highlighting patterns.

**Learning Outcome:**  
Through this challenge, I strengthened my ability to use Pivot Tables to analyze real-world data effectively. I gained practical experience in summarizing datasets, identifying trends, and visualizing data to derive insights—all essential skills on my path to becoming a proficient Data Analyst.
