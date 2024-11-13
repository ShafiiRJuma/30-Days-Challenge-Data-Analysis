**Day:** 6  
**Date:** 2024-11-13  
**Tools Used:** Microsoft Excel Pivot Table  
**Dataset:** [Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)

### Challenge Overview:
Yesterday i tried creating a simple dashboard with only two charts, today i tried to make the challenge a little bit realistic to make a dashaboard that can be used in real-world. This was kinda challenging as it took me to watch some YT Videos to get all the shapes and data come together, i believe consistency is key and everyday to add something into my knowledge will improve my skills in creating stunning dashboard.
Dataset contained sales data for a company and there is no hint of what kind of dashboard to create, everything has to come out figuring out what Data to out on dashboard, and what type of chart to use if necessary.

**Step 01**
I opened my dataset in excel and started to explore it seeing all the columns and get a general understanding of what the dataset is all about. I created a copy of my dataset to preserve the original file and started working with the copy. With the purpose to create a sales dashaboard i had to figure with data i have what can i get from it, and here were my dashboard objectives:
1. A dashboard to show total sales.
2. A dashboard to show total number of products Shipped.
3. A dashboard to show current number of Clients the business has.
4. Yearly sales growth (sales data is from 2003, 2004, and 2005)
5. Top customers by sales
6. Top countries by Sales
7. Top Products by Sales, and.
8. Show product status (How many product cancelled, on hold, disputed, resolved, and in process)

**Step 02**
Data Cleaning:
With these objectives in mind now i know what columns to focus on, what column to remove and data that will need adjustments if not complete. Here are issues i found while cleaning the data:
1. Phone number inconsistent formatting: Phone numbers were not consistent as they were in differnt formats, despite the fact that phone numbers were not going to be used in any of the items in my dashboard but it was necessary to put them in a proper format. I cleaned this my first removing all (.,-,(),) and other characters, then formatted text into phone number following US Phone number format.
2. On my dashboard i needed to present Top 10 Customers by Sales but dataset only gave me two columns first name and last name, to avoid any confussion where two customers have a similar first name, i created another column with fullname and concatenated first and last name to get fullname.
3. In the territory column EMEA, and APAC where well identified but AMER was not and it was indicated as NA for countries in that territory. I had to change all NA to AMER for Countries in that territory.
4. There was no duplicate, and no black cell for all necessary columns.
5. I removed Address Line 2 column as few rows had the data and it was not useful

**Step 03**
After cleaning my dataset, my second task was to figure out the interface of my dashboard and using shapes on excel to create this interface first without putting any data within. I started by drawing it on Paper, then transferred it on Excel then refined it as i thought best for that time making it look okay and useful.

**Step 04**
After creating an interface, then i had to use pivot table and get useful data summarized in pivot table, and pivot charts.

**Step 05**
Linking my pivot tables to the dashboard now was kinda a challenging part which needed a lot of back and forth on YouTube to grab some concepts and finally i managed to create this dashboard. After clearly understanding on how to create a dashaboard and linking dashboard data with pivot tables, now i want to focus on creating stunnign and creative dashaboard interface to make better Dashboard. (On My Excel Journey i remained with only 3 days to work on before i move on into PowerBI)

### Learning Outcome:
It was really a good lesson to build a dashboard on Microsoxft Excel and trying to make visual look on excel which i never tried before. But this challenge helped me a lot first is how to think about the data, figuring about what the data can communicate in business perspective which is very necessary in Data Analytics. On to the next challenge tommorrow to create an interactive dashboard linking all the data and making them dynamic.
