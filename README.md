# Used iPhone 13 Pricing Analysis

This project analyzes the prices of used iPhone 13 (128 GB, unlocked) devices across eBay, Back Market, and Amazon.

## Goals

- How does the price vary based on the phone's condition?
- Does the price depend on the sales platform?
- Does the price vary by country?
- Is there a correlation between price and review score (on Amazon)?

## Data Collection

- Data was collected on **May 4, 2025**
- Platforms: **Amazon**, **eBay**, and **Back Market**
- Search term used: `"iPhone 13 128GB unlocked"`
- Geographic markets: **Germany**, **United Kingdom**, and **Spain**
- Data sources:
  - **Amazon**: manually collected
  - **Back Market**: manually collected
  - **eBay**: collected via API

## Tools Used

- **Power Query** was used to collect data via API and to combine tables with data from different platforms
- **VLOOKUP** was used to add classification codes to the data
- **Pivot Tables** and **Pivot Charts** were used to analyze and visualize the results

## Summary of Results

- Phone prices **decrease with poorer condition**
- **Amazon** has the highest prices, followed by **Back Market**, then **eBay**
- Prices in **Germany** and the **UK** are similar, while **Spain** tends to have **lower prices**
- There's only a **weak correlation** between **Amazon review score** and **price**

## License

This project is open-source and available under the MIT License.
