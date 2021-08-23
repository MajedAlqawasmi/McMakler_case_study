# Supestore Case Study For McMakler
by [Majed Alqawasmi](https://github.com/MajedAlqawasmi) August 2021
<br/><br/>
##  SQL queries & Tableau visualisations/dashboards to answer business [questions](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/BI%20Case%20Study.pdf) & provide insights for McMakler 
![McMakler](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/mcmakler-logo-700x513.jpg)

## Table of content

- [Project Description](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/README.md#project-Description)
- [Data](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/README.md#data)
- [Process & Tools](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/README.md#process--tools)
- [Key Take Aways](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/README.md#key-take-aways)

## Project Description
This project shall: 
- answer specific questions through SQL querying
- visualise certain queries
- provide business insights based on findings in historical data   

## Data
Two datasets: 
- [U.S Superstore data published in 2019](https://data.world/annjackson/2019-superstore) 
- [Open source historical currency converter](https://www.currency-converter.org.uk/currency-rates/historical/table/EUR-USD.html)

## Process & Tools

**Process**
An iterative/agile approach circled through the following steps:

- **Github:** set up our Github repo to use for this project. <br/>
- **Project management:** Using Trello
- **WorldWideWeb:** find datasets<br/>
- **Querying:** providing [answers](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/SQL_Challenge/SQL_challenge_answered.txt) using MySQL<br/>
- **Web Scraping:** historical currency converter using Python/BeautifulSoup in a [Jupyter notebook](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/web_scraping/web_scraping_currency.ipynb)<br/>
- **Data cleaning & wrangling in Python:** using Pandas / numpy to prepare the historical currency converter dataset to be merged with the manin dataset<br/>
- **Answering questions & Visualization:** using [Tableau](https://public.tableau.com/app/profile/majed6120/viz/SuperstoreCaseStudy_16293384908960/VisualisingDailyProfitinEuro)<br/>

## Key Take Aways & Final Product

- **Complaints trend over last 7 years:** ![Trend](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/complaints_over_years.PNG) Trend is pointing upward therefore some action might be needed
- **Top 5 products in terms of numbers of complaints in top 20 banks:** ![Top 5 products](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/top5product20banks.PNG) Number of complaints for each product is proportionate to companies' sizes
- **Top Companies Compaints Wise & Their Bank Rank (Assets):** ![Top Companies Compaints Wise](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/top_bank_compliants-wise.PNG) Some organisations that might need some scrutiny
- **Consumer's sentiment:** ![Consumer's sentiment](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/consumer_sentiment.PNG) American cunsumer seems to mainatain objectivity and lack of polarity over the years
- **Map & Cultural Considerations:** ![Cultural Considerations](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/sentiment_map.PNG) Extra training may be provided to employees in the hightlighted states
- **Products Susceptible to Fraud Related:** ![Fraud](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/products_susceptible_fraud.PNG) From 2013 to 2019, we see a sharp increase in cryptocurrency related activity comparing to previous years. This can be of interest to Federal AML regulatory body
- **Products with Response Tardiness:** ![Tardiness](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/products_tardiness.PNG) To customers to whom it may concern and a direct communication with chief compliance officer from the regulator might be needed 

- **Dashboard:** For many more insight, please do check out [this dashboard](https://public.tableau.com/shared/H28TMMJNF?:display_count=n&:origin=viz_share_link)<br/>
