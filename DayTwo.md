### Day 2 Challenge Log

**Day:** 2  
**Date:** 2024-11-08  
**Tools:** ParseHub, Microsoft Excel  


**Challenge Overview:**  
Today, I expanded my data analyst skill set by adding a new tool to my arsenal—**web scraping**. While data cleaning remains a core skill for analysts, data collection is equally essential, especially when pulling information from online sources for analysis. Some data analysts use Python scripts for web scraping, but I used ParseHub, a tool that simplifies the process without requiring code.

For this challenge, I focused on gathering and preparing data from a job listing website. My goal was to analyze hiring trends, popular roles, top hiring companies, job locations, and common job requirements. The process covered web scraping and data cleaning, while the data analysis and visualization will follow on another day.


**Challenge Steps:**

**1. Web Scraping with ParseHub**  
ParseHub offers an intuitive interface with built-in tutorials that make scraping relatively straightforward (although the free plan is limited to 5 projects and 200 pages per project).  
- I set up a project using the target job site’s URL and configured ParseHub to capture specific data: Job Title, Employer, Location, and Job Requirements for each position.  
- The tool then scraped the site’s nine pages of listings (totaling 83 open positions), extracting and saving the information to an XLS file.

**2. Data Cleaning with Excel**  
After downloading the data, I began the cleaning process to ensure the dataset was accurate and complete for future analysis.

- **Create a Backup:** To protect the original data, I created a copy to work from in case any errors occurred during cleaning.  
- **Consolidate Columns:** Some of the scraped data ended up split across multiple columns. I combined fragmented job titles, locations, and other fields into their respective primary columns for consistency.  
- **Remove Unnecessary Columns:** The scrape had captured links alongside job titles, which I didn’t need, so I deleted these extra columns.  
- **Location Formatting:** Since all jobs were based in Tanzania, I separated the city name from “Tanzania” using Excel’s “Text to Columns” function and removed the now-redundant “Tanzania” column.  
- **Standardize Naming Conventions:** For consistency, I edited location names to ensure they matched, as some had variations like "Dae Es Salaam," "Dar es Salaam," and "Dar-es-salaam."  
- **Refine Job Descriptions:** The job descriptions included extraneous words, so I trimmed them down to focus on education and experience requirements.  
- **Standardize Terms in Job Descriptions:** Different cells used varying terminology for degrees, like "MSc" vs. "Master’s" or "Bachelor" vs. "Bachelors." I standardized these terms for uniformity.

**Conclusion:**  
With this cleaning process, I created a reliable, ready-for-analysis dataset. Tomorrow’s challenge will involve scraping data from multiple job listing sites, merging the information, and tackling the complexities that come with unifying data from various sources.

**Learning Outcome:**  
Today, I gained hands-on experience in web scraping using ParseHub and applied essential data cleaning techniques in Microsoft Excel—valuable steps for any data analyst in training.  

Let’s connect! I’d love to hear from other data professionals about your favorite data collection tools and any tips for efficient data cleaning. For those just getting started in data science, feel free to share your questions and ideas! 
