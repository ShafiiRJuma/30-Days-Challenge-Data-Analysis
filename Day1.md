Date: 2024-11-07
Tool: Microsoft Excel
Dataset: Crime Data from 2020 to Present
Dataset Description: This dataset contains records of reported crimes in Los Angeles from 2020 onward, encompassing 28 columns and 525,963 rows. It’s a large dataset that presents an excellent opportunity for data cleaning.

Project Overview:
In data analysis, every dataset must have a defined purpose to guide the analysis process and support confident decision-making. For this project, my primary goal is to master data cleaning techniques using Microsoft Excel. However, I’ve also set specific objectives to make this analysis meaningful.

Key Objectives:

Crime Frequency Analysis by Location and Time – Identify high-crime areas and determine times with elevated crime rates to assess risk patterns.
Demographic Analysis of Victimization – Examine if specific age groups, genders, or ethnicities are disproportionately affected by particular crimes, which can help inform targeted community outreach and support services.
Note: These are the overall objectives for the analysis. Today's focus is on preparing a clean and organized dataset for further exploration, EDA, and visualization in later stages.

Cleaning Process:
1. Dataset Backup
Created a copy of the original dataset to safeguard against accidental data loss during the cleaning process.

2. Column Renaming
Renamed columns from short-form labels to full descriptions for clarity and consistency, a useful practice when preparing data for database integration.

3. Handling Blank Fields
I examined core columns critical to my objectives, such as Crime Description, Victim Age, Sex, Descent, Area, Street Address, and Time Occurred.

Procedure: Filtered columns to view blank cells.
Decision: For columns like Victim Sex and Descent, where blanks would impact analysis, I filled blanks with “Not Specified” to retain the data for analysis without compromising completeness.

4. Addressing Outliers
Detected and addressed outliers in the Victim Age column, where negative values indicated erroneous data.

Procedure: Filtered ages below 0.
Decision: Removed rows with negative ages to maintain data integrity, especially important when calculating age-based trends.

5. Calculating Time Difference
Created a new column to calculate the time lag (in days) between the occurrence and reporting of each crime, a critical metric for understanding reporting behavior across different locations.

Procedure: Inserted a formula to calculate the difference between Date Reported and Date Occurred.

6. Decoding Victim Descent Codes
Translated coded ethnicity values (e.g., “B” for Black, “C” for Chinese) into full names for better readability during analysis.

Procedure: Used VLOOKUP with a reference table mapping each code to its corresponding ethnicity name.

7. Formatting Time Data
Ensured the “Time Occurred” column was consistently formatted as numbers, aligning data entries to facilitate time-based analysis.

Procedure: Converted the entire column to the correct number format.

8. Removing Unnecessary Columns
Removed columns that would not contribute to my objectives, reducing the dataset from 28 to 14 columns for a more streamlined analysis.

Columns Removed: Crime Code (redundant due to Crime Description), Premis Code, Crime Codes 1-4, Status, Status Description, Area Code, and Mocodes.

9. Trimming Excess White Space
Cleaned up the Street Address column by removing unnecessary spaces between words, enhancing readability.

Procedure: Split and trimmed each component of the address, then concatenated without extra spaces.

10. Consistent Text Formatting
Standardized text formats across all columns (e.g., proper case for text fields) and ensured date and numeric formats were consistent for easier analysis. Adjusted date formats to yyyy-mm-dd for uniformity.

Reflection
With these data cleaning steps completed, the dataset is ready for analysis. Today’s focus on thorough data preparation has set the foundation for my upcoming exploration and visualization tasks in this challenge.

Lesson Learned:
During data import, I mistakenly removed trailing zeros from the Time Occurred column, which altered the data's accuracy. After identifying the error, I reloaded the dataset and corrected this step, 
reinforcing the importance of careful handling at every stage of data import.
