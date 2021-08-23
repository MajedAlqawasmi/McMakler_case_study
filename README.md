# Supestore Case Study For McMakler
by [Majed Alqawasmi](https://github.com/MajedAlqawasmi) August 2021
<br/><br/>
##  SQL queries & Tableau visualisations/dashboards to answer business [questions](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/BI%20Case%20Study.pdf)<br/> & provide insights for McMakler 
![McMakler](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/mcmakler-logo-700x513.jpg)

## Table of content

- [Project Description](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/README.md#project-Description)
- [Data](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/README.md#data)
- [Process & Tools](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/README.md#process--tools)
- [Key Take Aways & Final Product](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/README.md#key-take-aways)

## Project Description
This project shall aim to both, highlight important findings, and provided Data analysis with a comprehensive dashboard on consumer complaint about banking products in the U.S from 2013 to 2019. It aims to raise consumer awareness, helps the regulator in decision making and prompts financial institutions to optimize their both their complaint handling process as well as their products. 

## Data
Four datasets: 
- [Consumer Complaints database from Consumer Financial Protection Bureau, USA](https://www.consumerfinance.gov/data-research/consumer-complaints/) 
- [Consumer Complaints database from data.world](https://data.world/cfpb/consumer-complaints/workspace/file?filename=complaint_data.csv)
- [U.S bank rank according to total assets](https://www.usbanklocations.com/bank-rank/total-assets.html?d=2021-03-31)
- [U.S Zipcode database](https://simplemaps.com/data/us-zips)

## Process & Tools

**Process**
My ways of working included an iterative/agile approach circling through the following steps:

- **Github:** set up our Github repo to collaborate on or to simply use for this project. <br/>
- **Project management:** [Trello](https://trello.com/b/UOn2CIdn/ironhack-final-project)
- **WorldWideWeb:** find datasets<br/>
- **Coding:** [Jupyter notebook](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/final_project.ipynb)
- **EDA:** assessment of dataframe to prepare for cleaning<br/>
- **Data cleaning & wrangling in Python:** using Pandas / numpy to drop columns, join tables, drop null values, convert some uppercase to lower<br/>
- **Web Scraping:** using BeautifulSoup<br/>
- **Text Analysis:** NLP using TextBlob to achieve a Sentiment score for each customer narrative<br/>
- **Querying:** using MySQL & Tableau<br/>
- **Answering question & Visualization:** using [Tableau](https://public.tableau.com/views/Happiness_16250058634520/Top5CorrelationDive?:language=en-US&:display_count=n&:origin=viz_share_link)<br/>
- **Finalizing a full dashboard:** using [Tableau](https://public.tableau.com/views/Happiness_16250058634520/Top5CorrelationDive?:language=en-US&:display_count=n&:origin=viz_share_link)<br/>
- **Presentation:** [google slides](https://docs.google.com/presentation/d/1rhUcAz9iLyuiL-HABICM4ZkHcmgFSo7NMqwrWDgCZaU/edit?usp=sharing)

## Key Take Aways & Final Product

- **Complaints trend over last 7 years:** ![Trend](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/complaints_over_years.PNG) Trend is pointing upward therefore some action might be needed
- **Top 5 products in terms of numbers of complaints in top 20 banks:** ![Top 5 products](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/top5product20banks.PNG) Number of complaints for each product is proportionate to companies' sizes
- **Top Companies Compaints Wise & Their Bank Rank (Assets):** ![Top Companies Compaints Wise](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/top_bank_compliants-wise.PNG) Some organisations that might need some scrutiny
- **Consumer's sentiment:** ![Consumer's sentiment](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/consumer_sentiment.PNG) American cunsumer seems to mainatain objectivity and lack of polarity over the years
- **Map & Cultural Considerations:** ![Cultural Considerations](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/sentiment_map.PNG) Extra training may be provided to employees in the hightlighted states
- **Products Susceptible to Fraud Related:** ![Fraud](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/products_susceptible_fraud.PNG) From 2013 to 2019, we see a sharp increase in cryptocurrency related activity comparing to previous years. This can be of interest to Federal AML regulatory body
- **Products with Response Tardiness:** ![Tardiness](https://github.com/MajedAlqawasmi/final_project_ironhac/blob/main/products_tardiness.PNG) To customers to whom it may concern and a direct communication with chief compliance officer from the regulator might be needed 

- **Dashboard:** For many more insight, please do check out [this dashboard](https://public.tableau.com/shared/H28TMMJNF?:display_count=n&:origin=viz_share_link)<br/>
