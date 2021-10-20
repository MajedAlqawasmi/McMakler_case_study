# Supestore Case Study
by [Majed Alqawasmi](https://github.com/MajedAlqawasmi) August 2021
<br/><br/>
##  SQL queries & Tableau visualisations/dashboards to answer business [questions](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/BI%20Case%20Study.pdf) & provide insights for Superstore management

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

- **Github:** set up Github repo to use for this project. <br/>
- **Project management:** Using Trello
- **WorldWideWeb:** find datasets<br/>
- **Querying:** providing [answers](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/SQL_Challenge/SQL_challenge_answered.txt) using MySQL<br/>
- **Web Scraping:** historical currency converter using Python/BeautifulSoup in a [Jupyter notebook](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/web_scraping/web_scraping_currency.ipynb)<br/>
- **Data cleaning & wrangling in Python:** using Pandas / numpy to prepare the historical currency converter dataset to be merged with the manin dataset<br/>
- **Answering questions with Visualization & dashboards:** using [Tableau](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/MostProfitableCategory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)<br/>

## Key Take Aways

The answer to the three SQL challenges is [here](https://github.com/MajedAlqawasmi/McMakler_case_study/blob/main/SQL_Challenge/SQL_challenge_answered.txt)

The answer to Tableau challenge, Part 1:
- **What is the most profitable category?** [here](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/MostProfitableCategory?:language=en-US&:retry=yes&:display_count=n&:origin=viz_share_link) is the answer
- **In which State share “furniture/office supplies” will be biggest?** [here](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/BiggestShareofFurnitureOfficeSuppliesperstate?:language=en-US&:retry=yes&:display_count=n&:origin=viz_share_link) is the answer
- **What is the most “profitable” customers’ first name?** [here](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/ShipModesSegmentsProfitabilityperCity?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) is the answer
- **How many days it take to ship all product with negative profit?** [here](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/MedianDaystoShipNegativeProducts?:language=en-US&:retry=yes&:display_count=n&:origin=viz_share_link) is the answer
- **In general, which modes, segments and cities are more profitable than other?** [here](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/ShipModesSegmentsProfitabilityperCity?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) is the dashboard

The answer to Tableau challenge, Part 2:
- **Should they close some branches or ways of shipping?** Yes, indeed all branched with a negative profit ratio and a downward trendline shall be closed as shown [here](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/BadBranchesDashboard?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
- **Should they put some restriction on products/?** [here](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/ProductsProfitCustomerServicewise?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) is the a list of the worst products in terms of profit ration and customer service combined
- **Other advices to Superstore strategy** This [chart](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/ShipModeProfitabilityTimeline?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) shows an issue with the profitability of two of the ship modes (First class & Same day), and this [chart](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/TheDiscountProblem?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) and more accurately [this interactive scatter plot](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/ShipModediscountscatterplot?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) show that profit ratio and discounts offered negatively correlate so the reason for prfot stagnation in those two ship modes is the increased discount offers. **Therefore I'd like to recommend a restriction on discounts offered for First class & Same day ship modes and an increase of the overall price.**  

The answer to Tableau challenge, Part 3:
- **Daily profit in Euros:** intergrated in [this dashboard](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/ProfitabilityinperCityShipModesSegmentCustomeroverTime?:language=en-US&:display_count=n&:origin=viz_share_link) or single days since 2016 tabled [here](https://public.tableau.com/views/SuperstoreCaseStudy_16293384908960/DailyProfitinEuro?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
