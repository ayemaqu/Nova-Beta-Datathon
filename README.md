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


## Visulizations & Insights 
Our analysis revealed several important insights about the ACE program’s effectiveness and fairness across NYC bus routes:
1. Violations appeared to increase overall, but context matters.
- From 2019 to 2023, routes where ABLE was originally implemented eventually saw a decline in violations, showing that the program became effective after an adjustment period.

- In 2024, total violations spiked dramatically. This was not a failure of the program itself, but rather the result of new violation types being added (double parking and bus stop standing) from the ACE program, which expanded the scope of enforcement.
 - <img src="https://github.com/user-attachments/assets/e324e79c-f7b9-4850-a0a8-6b24d50d0f3f" alt="vioovertime" width="450">

2. Effectiveness varies by borough.
- Staten Island and Queens dominated the top 10 fastest routes, suggesting ACE is less necessary in those areas since buses already move relatively quickly.
 - <img src="https://github.com/user-attachments/assets/2172774f-6787-40c2-8c97-058837dd0493" alt="avg_speed_top" width="400">
- The Bronx, by contrast, contained the slowest routes and also the highest violation counts. This means residents there are experiencing more enforcement without seeing equivalent improvements in speed.
 - <img src="https://github.com/user-attachments/assets/bd0ef422-e870-4371-9868-b49c825c5a71" alt="bottom_10_avg" width="400">

3. Equity concerns are most visible in high-poverty areas.
- Geographic rollout:
 - [Tableau Visual Link](https://public.tableau.com/app/profile/ayema.qureshi/viz/please_save_imbegging/Sheet1?publish=yes)
   - <img src="https://github.com/user-attachments/assets/60bd857a-35b7-422a-ae5f-75e566ebee24" alt="ace_map" width="500">
- **Equity context:** By comparing this with poverty or income maps, you can see whether high-poverty areas (e.g., parts of the Bronx or Brooklyn) were more heavily targeted for ACE expansion. This directly ties into your fairness question.
- In the Bronx, violations rose sharply after 2024, especially with the addition of new violation types. Yet bus speeds in these neighborhoods did not improve significantly
- The chart below shows violations in the Bronx broken down by type. Bus lane violations began to decrease after 2023, but the introduction of new violation types in 2024 (such as double parking and standing at bus stops) led to a sharp increase in total violations. This highlights an important issue: while ACE is designed to improve bus service, in some neighborhoods it has primarily resulted in more tickets rather than better outcomes.
- [Tableau Visual Link](https://public.tableau.com/app/profile/ayema.qureshi/viz/please_save_imbegging/Sheet12?publish=yes)
- <img src="https://github.com/user-attachments/assets/368b32da-adb7-4fd9-8961-f6cd195d081b" alt="poverty_map" width="500">
 - This raises questions about fairness: if ACE is meant to improve bus service, but in certain neighborhoods it results mostly in tickets, then the program’s benefits are not being evenly distributed.
 - We focus on the Bronx because it is one of the boroughs with the highest poverty rates and also experienced the largest increase in violations after ACE expanded in 2024. This raises questions about fairness. If residents in high-poverty areas are receiving more violations without seeing meaningful improvements in bus speed or service, then the benefits of ACE are not being distributed evenly across the city.
 - Looking back, when the program was still ABLE and focused only on bus lane violations, we saw violations decrease over time as drivers adjusted to the enforcement. But when ABLE transitioned to ACE and two new categories of violations were added, the number of tickets rose again. This outcome makes sense, expanding the scope of enforcement naturally creates more opportunities for violations but it also shows why local infrastructure matters. In areas like the Bronx, where congestion and street design make compliance harder, the expansion has meant more violations and more financial strain for residents.
 - This suggests that ACE is not equally effective everywhere. Some routes benefit from faster bus service, while others—especially in high-poverty neighborhoods—are weighed down by higher violation counts. This uneven impact raises important equity concerns and shows why not every area is equally suited for ACE implementation.


 
