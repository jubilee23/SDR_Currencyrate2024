# SDR_Currencyrate2024
## Introduction to SDR Currency Analysis
In today's global economy, currency is the fundamental medium that enables international trade, business transactions, and profit generation. Without currency, the seamless exchange of goods and services across borders would be impossible. The ability to track and analyze currency performance is essential for making informed financial and business decisions.

 ![](foreign_notes.jpg)


This dataset, sourced from Yahoo Finance for the year 2024, provides a detailed look at currency exchange rates over a series of dates. The dataset consists of 8 columns, including:
1.	Currency
2.	November 04
3.	November 05
4.	November 06
5.	November 07
6.	November 08
7.	November 11
8.	November 12
9.	November 13
Each row represents a currency, and the columns corresponding to the dates show how the exchange rate fluctuated over the specified days. This allows for a clear understanding of whether a currency's value increased or decreased over time.
________________________________________
## Purpose of the Dataset

•	Track Exchange Rate Trends: Identify how currency rates fluctuate over different dates.

•	Performance Analysis: Evaluate which currencies are appreciating or depreciating.

•	Business Insights: Help businesses and investors make strategic decisions based on currency performance.

•	Volatility Measurement: Assess the stability or volatility of different currencies over the period

## DATA CLEANING
### Data Cleaning Process
o	The dataset was originally in XML format. It was converted to XLSX for easier data handling and analysis.

o	The first row, which did not add value to the dataset, was removed to ensure data quality.

o	The first meaningful row was used as the header to label the columns appropriately.

o	Columns 2 to 7 were unpivoted to transforming the dataset into a longer format, creating two new columns:

	Date: Representing the original attribute (e.g., dates or categories).

	Rate: Containing the corresponding values.

o	The resulting columns were renamed to "Date" and "Rate" for clarity and consistency with the dataset's intended use.

o	The data types were adjusted accordingly to ensure correct formatting and compatibility for analysis.

## Project Objectives:
o	Identify and focus investments on high-performing currencies (e.g., U.K. Pound, Swiss Franc) while reducing exposure to low-performing currencies (e.g., Mexican Peso, Czech Koruna).

o	Achieve volatility levels closer to the target (6.32%) to maximize potential returns while maintaining manageable risk.

o	Develop a systematic approach to monitor and adjust currency positions based on trends identified in the top and bottom 10 currencies by rate.

o	Broaden the currency portfolio to mitigate risks associated with dependence on a few strong currencies.

o	Use data-driven insights (e.g., rate totals, currency totals, and performance spikes) to inform strategic decisions and improve overall investment outcomes.

## Key Observations:

1.	Top 10 Currencies by Rate:
   
o	The U.K. Pound and Swiss Franc have the highest rates.

o	Other strong currencies include the Euro, U.S. Dollar, and Brunei Dollar.

2.	Bottom 10 Currencies by Rate:
   
o	The Mexican Peso and Czech Koruna have the lowest rates.

o	Other weak performers include the Thai Baht, Uruguayan Peso, and Mauritian Rupee.

3.	Volatility:
   
o	The volatility change is 0.31 (Goal: 6.32%), indicating relatively low volatility compared to the goal.

4.	Rate Total and Currency Total:
   
o	The Rate Total is 54.83, and the Currency Total is 25, suggesting a moderate range of currencies in consideration.

o	The Max Rate is 0.98, highlighting a cap on performance.

5.	Sum of Rates by Currency:
   
o	There are noticeable spikes in rates for specific currencies like the U.K. Pound, Swiss France, and Euro.
________________________________________
## Recommendations:
1.	Focus on High-Performing Currencies:
   
o	Continue monitoring and investing in stable, high-performing currencies such as the U.K. Pound, Swiss Franc, and Euro for better returns.

2.	Mitigate Risks with Low-Performing Currencies:
   
o	Consider hedging strategies or limiting exposure to the Mexican Peso, Czech Koruna, and Thai Baht, which show consistently low rates.

3.	Address Volatility Goals:
   
o	Since the current volatility change (0.31) is far below the goal (6.32%), explore strategies to achieve optimal volatility, such as diversifying investments or leveraging market opportunities.

4.	Monitor Currency Trends:
   
o	The Sum of Rates by Currency chart shows significant fluctuations; closely track these trends to adjust positions accordingly and take advantage of peaks and troughs.

5.	Optimize for Max Rate:
   
o	With a Max Rate of 0.98, identify potential opportunities to increase rate performance through diversified portfolios or new currency markets.

For a more comprehensive explanation of the dataset, click here.https://app.powerbi.com/view?r=eyJrIjoiMzlhNTMxOTQtZjI1Ni00M2Y3LTg1NTctYzAzYWIzODNiZWNmIiwidCI6ImRkNDg0OTZkLWE3ZDEtNDhmOS05ZGRiLTA4MTJiY2Q1ZTlkNCIsImMiOjZ9
