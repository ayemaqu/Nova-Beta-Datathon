# DATATHON: Analyzing the Effectiveness and Equity of NYC’s Automated Camera Enforcement (ACE) Program

## Introduction
### What is the project about?
- This project analyzes data from the MTA's Automated Camera Enforcement (ACE) program to understand its impact on New York City’s bus system. Using MTA Open Data, we explored questions related to bus speeds, violations, and route efficiency through an equity lens. The goal is to evaluate the program’s effectiveness and highlight areas for improvement.
### Why does it matter?
- This matters because ACE is designed to improve bus speeds and service reliability. At the same time, it raises questions about fairness: are its benefits distributed equitably across different routes and neighborhoods? By answering these questions with data, we can provide insights that inform more effective and inclusive transportation strategies.
### Who are the stakeholders?
- The stakeholders include the MTA Open Data Team and other transportation-related groups invested in service efficiency, policy design, and community impact.
### Business Question
- Are the benefits of the ACE program being effectively and fairly distributed across NYC bus routes?


## Process
1. Exploration – What we noticed first when looking at the data.
- At first glance, ACE appeared ineffective because violations consistently increased from 2019 through 2025. If more tickets were being issued year after year, how could the program be considered successful? However, when we looked more closely, we found that this interpretation was misleading.
- In the neighborhoods where ACE was first introduced (between 2019 and June 2024), violations eventually decreased after a period of adjustment. By 2024, the data showed a clear decline in violations, suggesting that the program was working. It simply required time before its effectiveness became visible.

2. Analysis – How we broke down the data 
- We began by gathering data from MTA Open Data and converting the larger datasets into databases to make them easier to query. From there, we performed joins between datasets, aggregated data to identify trends, and grouped values by borough, year, and route to generate filtered insights. This allowed us to compare ACE versus non-ACE routes, examine speed changes over time, and analyze violation trends across different neighborhoods.

3. Visualizations – Which types of charts/maps/tables we used and why.
 - We used a combination of visualization techniques to understand and communicate our findings:
   - Line charts to track trends in bus speeds and violations over time.
   - Bar charts to compare bus routes and boroughs on metrics such as average speed and violation counts.
   - Maps to visualize geographic differences and highlight which areas were most impacted.
   - Scatterplots to explore the relationship between bus speed and violations, revealing clusters of routes where ACE was more or less effective.
 - These visualizations allowed us to identify not just overall trends but also neighborhood-level differences in how ACE was working.

4. Team Roles - This was a group project with three members:
- **Thomas** focused on violations, showing that while older ACE routes eventually saw decreases, the 2024 expansion caused an overall spike due to new violation types.
- **Thierno** analyzed bus speeds, confirming that ACE improves travel times overall, but unevenly across the city.
- **Ayema** focused on equity, demonstrating that high-poverty areas—especially in the Bronx—were disproportionately impacted by higher violation counts without equivalent improvements in speed.



