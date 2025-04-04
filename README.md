# 🚀 Mars Web Scraping & Weather Analysis

In this project, I tackled a full web scraping and data analysis challenge using automated browsing with Splinter and HTML parsing with BeautifulSoup. The goal was to collect Mars news headlines and analyze weather data collected by NASA's Curiosity rover, demonstrating core data skills: scraping, organizing, analyzing, and visualizing data.

# 🧪 Technologies Used
- Python

- Jupyter Notebook

- BeautifulSoup (HTML parsing)

- Splinter (browser automation)

- Pandas (data analysis)

- Matplotlib (visualization)

# 📥 Deliverables
 Deliverable 1: Mars News Scraping

Objective:
Scrape the latest articles from the Mars NASA news website and extract their titles and preview text.

Steps Taken:

- Visited the Mars News Site using Splinter

- Parsed HTML with BeautifulSoup to extract:

  - title (article headline)

  - preview (article summary)

- Stored each article in a Python dictionary

- Compiled all dictionaries into a list and printed it

- Optionally exported the data to a .json file

 Deliverable 2: Mars Weather Data Scraping and Analysis

Objective:
Scrape and analyze historical Martian weather data from a static HTML page.

Steps Taken:

- Visited Mars Weather Table with Splinter

- Parsed the temperature data table using BeautifulSoup

- Constructed a Pandas DataFrame with columns:

   - id, terrestrial_date, sol, ls, month, min_temp, pressure

- Cast data types to appropriate formats (datetime, float, int)

# 🔍 Data Analysis
Using Pandas and Matplotlib, I explored key weather patterns:

📅 How many months exist on Mars?

  - Answer: 12 Martian months

📊 How many Martian days (sols) were recorded?

  - Counted unique sol values in the dataset

🧊 Coldest and Warmest Months

  - Calculated average min_temp per month
  
  -Plotted: Bar chart showing temperature trends by month

🌬️ Atmospheric Pressure Trends

  - Calculated average pressure per month

  - Plotted: Bar chart showing pressure levels by month

📆 Estimating Earth Days in a Martian Year

  - Plotted all terrestrial_date entries vs min_temp
  
  - Estimated about 687 Earth days in one Martian year (based on temperature cycle)

# 💾 Final Output

Exported the cleaned and processed weather DataFrame to mars_weather.csv

# 💡 Takeaways

This project gave me hands-on experience with real-world web scraping techniques and exploratory data analysis. I improved my ability to:

- Work with automated browsers
- Parse dynamic and static websites
- Structure and clean data for insights
- Visualize trends and present findings clearly
