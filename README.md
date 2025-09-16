Internshala Data Analyst Job Scraper & Analysis

Overview

This Jupyter Notebook (Scrape_and_Analyze_Job.ipynb) demonstrates web scraping, data analysis, and visualization using Python. It collects Data Analyst internship listings from Internshala, processes the data, and generates insights such as top locations and most in-demand skills.

The project provides hands-on experience with BeautifulSoup, pandas, and matplotlib, and is suitable for beginners learning data scraping and analysis.

Features

Scrapes Job Title, Company, Location, Skills, and Stipend from Internshala internships.

Handles missing or dynamically loaded data safely.

Saves the data as a CSV file (internshala_data_analyst_jobs.csv) for further analysis.

Performs analysis:

Total number of jobs scraped

Top locations

Most in-demand skills

Generates visualizations:

Bar chart of top 5 job locations

Pie chart of top skills

Tools & Libraries

Python 3.x

Libraries:

requests – sending HTTP requests

BeautifulSoup (bs4) – HTML parsing

pandas – data manipulation

matplotlib – visualizations

collections.Counter – counting skills frequency

re – text processing

How to Use

Clone this repository:

git clone https://github.com/satishsat1/internshala-job-scraper.git


Install required libraries:

pip install requests beautifulsoup4 pandas matplotlib


Open the notebook Scrape_and_Analyze_Job.ipynb in Jupyter Notebook or VS Code.

Run all cells.

Outputs include:

internshala_data_analyst_jobs.csv – scraped internship data

Bar chart of top 5 locations

Pie chart of top skills

Insights & Deliverables

Total jobs scraped – number of internships collected.

Top locations – cities with the most internship opportunities.

Most in-demand skills – key skills required for Data Analyst roles.

Visual charts – help understand data trends quickly.

Challenges

Internshala sometimes loads elements dynamically with JavaScript, making scraping tricky.

HTML structure may change, requiring adjustments in the code.

Skills extraction uses keyword search to ensure reliable results.

Future Improvements

Use Selenium to scrape multiple pages and dynamically loaded content.

Implement NLP-based skill extraction for more accurate results.

Create an interactive dashboard for visualization.
