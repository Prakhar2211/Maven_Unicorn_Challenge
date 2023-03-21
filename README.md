# Maven_Unicorn_Challenge

## 📚 About Data

A unicorn company is a private company with a valuation of more than $1 billion, and today there are over 1,000 unicorn companies around the world! 
This dataset[Unicorn_Companies.csv](https://github.com/Prakhar2211/Maven_Unicorn_Challenge/blob/main/Unicorn_Companies.csv) contains a csv table with 1,074 records, one for each company 
Each record contains details on the company's current valuation, total funding, country of origin, industry, select investors, and the years they were founded and became unicorns

## 💡 Highlights

- Valuations in year 2021 makes up one-third of total valuations since the beginning of time.
- Unicorns in United States and China outperformed the rest of the world with 72% overall valuations.
- Bytedance, SpaceX, SHEIN and Stripe are the most successful unicorns which performed better than an average unicorn at $71 billion.
- Unicorns in AI, E-Commerce, Fintech and Edtech industries are valued higher than the average unicorn at $3.5 billion. 
- A unicorn takes an average of 7 years to attain valuation of $1billion and become a unicorn.

## ✏️ Data Wrangling

Conducted simple data wrangling and data cleaning:
- Removed rows with missing values
- Cleaned `Valuation` and `Funding` columns and cast as float
- Exclude rows with "Unknown" `Funding` values
- Explode `Select Investors` column into individual rows for categorical analysis

📍 Jupyter script: [Notebook](https://github.com/Prakhar2211/Maven_Unicorn_Challenge/blob/main/Unicorn%20Challenge.ipynb)

📍 Clean Data: [unicorn_companies_clean.csv](https://github.com/Prakhar2211/Maven_Unicorn_Challenge/blob/main/unicorn_companies_clean.csv)

## 📊 Visualization

Produced a 1-pager dashboard using Tableau.

Tableau: [Link](https://public.tableau.com/app/profile/prakhar.bundela/viz/UnicornCompanies_16794231051250/Unicorns)


