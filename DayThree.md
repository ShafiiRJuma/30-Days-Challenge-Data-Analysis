**Day:** 3  
**Date:** 2024-11-09  
**Tools:** Microsoft Excel Pivot Table
**Dataset:** [Leading Causes Of Death from In United States](https://catalog.data.gov/dataset/nchs-leading-causes-of-death-united-states)

**Challenge Overview:**  
After learning how to perform Data Cleaning using Microsoft Excel from removing duplicates, blank rows, to creating consistent formatting from the
previous days today i embarked on a journey to practice Pivot Table which is another tool within Microsoft Excel can help us to summarize the data
we have and get a snapshot of what the data is all about and get answers to some of our questions from the data.

**Description of the dataset**
This dataset presents the age-adjusted death rates for the 10 leading causes of death in the United States beginning in 1999. This dataset from [data.gov](https://catalog.data.gov/dataset/nchs-leading-causes-of-death-united-states) gives us the top leading causes with number of death recorded per disease from that year. As a curious person i was interested to know What are the leading causes of death in the United States? What are the leading causes of death per state? and what is the trend of death in the United States from 1999? i picked this data due to those questions in my head.


**Challenge Steps:**
I downloaded the data in excel and opened it using Microsoft Excel and started to explore it to get an understanding of the data, analyze columns to understand datatypes, number of columns, total rows, and overall look of the data.

![Raw Data](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayThreeScreenshots/DRraw.jpg)

**1. Data Cleaning with Excel**  
As usual after knowing how the data is, the next thing is to clean the data in order to get sound, and complete dataset which can be used for analysis. I checked for Duplicates, Blank cells, inconsistent formatting, and others but i found none as this data was cleaned already and placed for analysis purpose only.

**2. Opening Pivot Table**
Go to the Insert Tab -> Click Pivot Table -> then from Table/Range

![Pivot Table](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayThreeScreenshots/DRPivotTable.jpg)

Pivot Table usually select all the rows and columns you have then i clicked okay.

![Pivot Table Data Selection](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayThreeScreenshots/DRPVSelection.jpg)

Here is the interface of the Pivot Table:

![Pivot Table](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayThreeScreenshots/DRPVInterface.jpg)

**Leading Causes of Death In The United States**
From the dataset, to know th leading causes of death in the United States on the Pivot Table Field select Cause Name, Death (Pivot table will automatically calculate SUM of death per cause name) but this can be changed depending on the purpose whether to count, get average, Maximum or Minimum.

![Leading Cause of Death In The United States](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayThreeScreenshots/DRPVCausesOverAll.jpg)
This is the total number of death occured from 1999 per each cause of death in The United States. From the Data we can see Heart Disease has been the leading cause of death in The United States.

**Leading Causes of Death per State**
Now after knowing that Heart Disease has been the leading cause of death in the US we go down to understand the leading causes of death per state. To do this we go to Pivot Table Field then selecting State, Cause Name, and Deaths.
With these data we can see on each state top 10 causes of death per number of deaths from 1999.

![Leading Causes of Death Per State](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayThreeScreenshots/DRLeadingCausesPerState1.jpg)

**Leading Causes of Death Per Year**
After knowing the leading cause of death in The United States and per each State now i wanted to know the leading cause of death on each year frmo 1999. To do this from the Pivot Table Fields i cleared all the previous selections, selected year, cause name, and death. This Pivot table will give out SUM of death per each death on each year and present the top leading causes on each year.

![Leading Causes Of Death On Each Year](https://github.com/ShafiiRJuma/30-Days-Challenge-Data-Analysis/blob/main/DayThreeScreenshots/DRPVLeadingDeathCausesPerYear.jpg)

**Trend of Heart Disease's Death Over the Years**
Now from the previous data i realised that Heart Disease has been the major causes of death in the US over the years, i wanted to see the trend if deaths are increasing or dicreasing. To do this i had to clear my selections on Pivot Table Field, selected Year, cause name (i filtered all diseases to remain with heart disease), then i selected Deaths to get sum of heart disease's death per year.
From this i inserted a Chart which showed the trend as seen below here:

**Conclusion:**  



**Learning Outcome:**  
