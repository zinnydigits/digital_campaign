### Project Overview
The project aims to analyze the performance of a digital campaign by examining key metrics like conversion rates, bounce rates, and channels. Through thorough data analysis, insights were derived to optimize future campaign strategies and enhance overall marketing efficiencies.

![digitalcampaign_dashboard](https://github.com/zinnydigits/digital_campaign/assets/53875635/c7b101c4-8f1a-43ba-b394-d4d46fd3f70d)

### Data Source
The data was obtained from [absentdata.com](https://absentdata.com/data-analysis/where-to-find-data/).

### Tools
- **Microsoft Excel:** Used for data preprocessing and initial analysis.
- **Power Query:** Part of the Microsoft Power BI suite, Power Query is used for data cleaning, transformation, and integration.
- **Power BI for Visualization:** Power BI is a powerful data visualization tool that enables the creation of interactive dashboards and reports. It's used here to visualize the analyzed data in a clear and insightful manner.

### Code
```  Total Conversion =
                        IF (SUM(full_web[Conversions]) >= 1000,
                        FORMAT(SUM(full_web[Conversions])/1000, "0.00") & "K",
                        FORMAT(SUM(full_web[Conversions]), "0"))
```

### Visualization
- **Charts used:** Bar charts, column charts, funnel charts, line charts, and a pie chart was used as a tooltip for the funnel chart.
- **Tool Tips:** All charts have a tooltip. The funnel chart has a pie chart tooltip indicating bounce rate per month.
- **Alternate Text:** All charts have alternate text for the visually impaired.

### Explanatory Data Analysis
- Majority of the users, around 91%, are Organic Searchers.
- 46% of the Bouncing Sessions were from Paid Channels.
- The peak session occurred in September.
- The highest conversion rate was in March, slightly above May.
- The channels had comparable conversion rates.

### Recommendation
- Efforts should be made to attract users from paid channels.
- Page optimization is crucial to reduce bounce rates from paid channels.
- Organic growth of the page is encouraged.

### References
- [absentdata.com](https://absentdata.com)
- Chandoo Youtube Channel
