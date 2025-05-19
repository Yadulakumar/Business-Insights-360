# BI-360-PBI — Business Insights 360

## Project summary
AtliQ Hardware lost money in Latin America because managers relied on intuition instead of data. **Business Insights 360** is a single Power BI dashboard that gathers every key metric so decisions are based on facts, not guesses.

## Dashboard views and the questions they answer
- **Finance View** – How are sales, costs, and profit moving for any product, customer, or country? (https://github.com/Yadulakumar/Business-Insights-360/blob/main/Screenshot%202025-05-15%20104544%20-%20Copy.png)
- **Sales View** – Which regions, customers, and products drive growth or drag it down? (https://github.com/Yadulakumar/Business-Insights-360/blob/main/Screenshot%202025-05-15%20104605%20-%20Copy.png)
- **Marketing View** – Which products and areas give the best balance of profit and growth?  
- **Supply-Chain View** – How accurate are our demand forecasts? Where are the biggest errors?  
- **Executive View** – What is the 30-second health check of the entire company?

## Data sources
- **MySQL** database for core sales, finance, and forecast facts and dimensions  
- **Excel / CSV** files for targets, market-share figures, and other reference data

## Data model
Clean star schema with **9 fact tables** (Sales, Finance, Forecast, etc.) and **7 dimension tables** (Customer, Product, Region, Calendar, Channel, Category, Benchmark)

## Key business terms
Gross Sales • Net Invoice Sales • Net Sales • Cost of Goods Sold • Gross Margin • Gross Margin % • Forecast Accuracy % • Net Error • Absolute Error

## Typical insights revealed
- APAC delivers **55 % of Net Sales** but its Gross-Margin % fell 2.9 points → pricing needs review  
- Forecast Accuracy climbed to **73 %**, yet three major customers still create large Net Errors → adjust product mix  
- “Notebook” product line sells the most units but loses money → promotional spend too high
