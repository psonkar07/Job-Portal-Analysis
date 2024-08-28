![Naukri Logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRWHWhFLV-_ViPivF0ucuLW7UQlM5QF4zvtgA&s)
# EDA on Job-Portal-Analysis

## Goal of the Project
The purpose of this project is to conduct a comprehensive data cleaning and exploratory analysis on a job portal dataset. Initially, the focus was on cleaning the dataset and understanding the structure of the data. This project demonstrates the iterative and exploratory nature of data analytics, where initial data preparation is essential for gaining deeper insights. Unlike the common approach where problems and questions are defined beforehand, this project started with a dataset that posed significant challenges, allowing for a hands-on experience in transforming the data. The final objective was to perform a thorough analysis and present the findings through visualizations.

## Power BI Dashboard
The Job Market Insights Dashboard provides an overview of job roles, salary transparency, and location-based job distribution. The dashboard was designed to offer a comprehensive view of the job market trends in 2024.Here's the company insights dashboard.

![Job Portal Dashboard](https://github.com/psonkar07/Job-Portal-Analysis/raw/main/4-Job%20portal%20dashboard.png)

## Analysis Approach

### 1. Data Quality Assessment and Data Cleaning
The first step was to prepare the dataset by assessing its quality and performing necessary cleaning operations. The goal was to ensure that the data was accurate, consistent, and ready for analysis. The following steps were taken:

**Job Portal Data Cleaning:**
- Dropped irrelevant columns that did not contribute to the analysis.
- Handled missing values through appropriate methods.
- Standardized and normalized data to remove inconsistencies.
- Created new features by extracting and transforming existing columns.
- Separated and categorized various attributes for easier analysis.

### 2. Exploratory Data Analysis
After the data was cleaned, exploratory analysis was conducted to extract insights and understand the dataset better. The following insights were derived:

- **Top Job Roles by Job Openings**: Analyzed the most in-demand job roles based on the number of postings.
![Top Job Roles](https://github.com/psonkar07/Job-Portal-Analysis/blob/main/Insights/Top%20Job%20Roles.png)
- **Top Companies by Job Openings**: Identified companies with the highest number of job listings, highlighting active employers.
 ![Top Companies](https://github.com/psonkar07/Job-Portal-Analysis/blob/main/Insights/Top%20Companies.png)
- **Top Locations for Job Openings**: Examined the geographic distribution of job opportunities, revealing key job markets.
- **Remote vs. Onsite Work in 2024**: Investigated the balance between remote and onsite job opportunities.
- **Experience Levels in Job Roles**: Categorized jobs based on required experience levels, offering insights into demand for different experience ranges.
- **Salary Disclosure vs. Undisclosed Salary**: Explored the transparency of salary information across job postings.
- **Top 5 Skills Overall**: Identified the most frequently required skills across all job postings.
- **Top 10 Skills for Specific Roles**: Detailed the most important skills for specific job roles.
- **Top Job Roles by Salary Disclosure**: Highlighted roles with the most transparent salary disclosures.
- **Salary Transparency by Job Role**: Analyzed which job roles were most upfront about pay, providing clarity on salary expectations.

### 3. Visualization and Dashboard Creation
A comprehensive dashboard was created using Power BI to visualize the key findings from the analysis. The dashboard includes:

- **Top Companies by Job Openings**: Showcases the companies with the highest number of job postings.
- **Companies by Average Rating**: Displays the companies with the highest average ratings from employees.
- **Remote vs. Onsite Work**: Illustrates the proportion of remote versus onsite jobs.
- **Top Locations with Maximum Job Postings**: Highlights the locations with the highest number of job postings.


## Datasets Used
- `job.csv.zip`: This dataset included detailed information about job listings such as roles, locations, salaries, and required skills.
- [https://github.com/psonkar07/Job-Portal-Analysis/blob/main/jobs.csv.zip] (link to dataset source)

## Tools and Technologies Used
- **Python**: For Data Quality Assessment, Data Cleaning, and Exploratory Data Analysis using libraries like pandas, matplotlib, and seaborn.
- **Power BI**: For creating the Job Market Insights Dashboard to visualize the analysis.
- **Google Colab**: For detailed data cleaning and exploratory analysis.

## Conclusion
The analysis of the job portal dataset provided valuable insights into the current job market, including trends in job roles, salary transparency, and the demand for specific skills. The findings can help job seekers and employers alike to navigate the job market more effectively, making informed decisions based on data-driven insights.
