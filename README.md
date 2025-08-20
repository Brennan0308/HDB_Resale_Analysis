# HDB_Resale_Analysis (Singapore)

This project analyzes the trends of **HDB resale flat prices based on registration date from Jan 2017 onwards** using data from [Data.gov.sg](https://data.gov.sg/datasets/d_8b84c4ee58e3cfc0ece0d773c8ca6abc/view).  
The goal is to uncover insights about pricing patterns across towns, flat types, and lease years, and present findings through **Python, SQL, and Power BI**.

Objectives
- Clean and prepare resale flat transaction data for analysis.
- Perform exploratory data analysis (EDA) to identify trends and correlations.
- Build SQL queries to answer business questions.
- Create an interactive Power BI dashboard for visualization.
- Summarize findings and provide insights for stakeholders.

Key Analysis
1. Transaction Counts
- Identified towns with the most and least transactions per flat type
- Example: 4-ROOM flats had the most transactions in Sengkang Town(2019 and 2022)

2. Resale Price
- Compared towns with the highest and lowest resale prices
- Example: For 4-ROOM and 5-ROOM flats, Central Area led in high resale prices, while non-Central(Woodlands, Sembawang, Yishun and Jurong West) stayed at the lower end

3. Remaming Lease(>=95 years)
- Focused on the resale price of flat types that sell immediately after the MOP (Minimum Occupation Period)
- Central Area(Bukit Merah and Queenstown) topped in prices, while Sembawang, Woodlands & Choa Chu Kang were the lowest
