# DATATHON: ACE Program Equity & Effectiveness Analysis

Link to video: [Brief Overview](https://youtu.be/2fcA3dohn8M)

Link to presentation: [Presentation By Nova Beta](https://www.canva.com/design/DAG0CSB8-uo/IsnAQps1iKK0EM4LO2rPeQ/edit?utm_content=DAG0CSB8-uo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Project team (NOVA BETA): [Ayema Qureshi](https://www.linkedin.com/in/ayema-qureshi-901287187), [Thierno Barry](https://www.linkedin.com/in/thierno-barry-333288284/?lipi=urn%3Ali%3Apage%3Ad_flagship3_people_connections%3BP%2BbOZbM9QwCkyPoYBv9k3g%3D%3D), [Thomas Segal](https://www.linkedin.com/in/thomas-segal-093370369) 


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
1. **Violations appeared to increase overall, but context matters**
- From 2019 to 2023, routes where ABLE was originally implemented eventually saw a decline in violations, showing that the program became effective after an adjustment period.

- In 2024, total violations spiked dramatically. This was not a failure of the program itself, but rather the result of new violation types being added (double parking and bus stop standing) from the ACE program, which expanded the scope of enforcement.
 - [Tableau Visual Link](https://public.tableau.com/app/profile/thomas.segal/viz/BookMTA/Dashboard1?publish=yes)
 - <img src="https://github.com/user-attachments/assets/e324e79c-f7b9-4850-a0a8-6b24d50d0f3f" alt="vioovertime" width="450">

2. **Effectiveness varies by borough**
- Staten Island and Queens dominated the top 10 fastest routes, suggesting ACE is less necessary in those areas since buses already move relatively quickly.
 - <img src="https://github.com/user-attachments/assets/2172774f-6787-40c2-8c97-058837dd0493" alt="avg_speed_top" width="400">
- The Bronx, by contrast, contained the slowest routes and also the highest violation counts. This means residents there are experiencing more enforcement without seeing equivalent improvements in speed.
 - <img src="https://github.com/user-attachments/assets/bd0ef422-e870-4371-9868-b49c825c5a71" alt="bottom_10_avg" width="400">

3. **Equity concerns are most visible in high-poverty areas**
- Geographic rollout:
 - ABLE (blue) was concentrated in parts of Manhattan, Brooklyn, and the Bronx, suggesting those were the earliest focus areas.
 - ACE (orange) expanded coverage into new areas across all boroughs, including Staten Island and Queens.
 - Non-ACE/Non-ABLE (red) areas show where enforcement was never implemented, which helps highlight gaps in coverage.
 - [Tableau Visual Link](https://public.tableau.com/app/profile/ayema.qureshi/viz/please_save_imbegging/Sheet1?publish=yes)
   - <img src="https://github.com/user-attachments/assets/60bd857a-35b7-422a-ae5f-75e566ebee24" alt="ace_map" width="550">
- **Equity context:** By comparing this with poverty or income maps, you can see whether high-poverty areas (e.g., parts of the Bronx or Brooklyn) were more heavily targeted for ACE expansion. 
- In the Bronx, violations rose sharply after 2024, especially with the addition of new violation types. Yet bus speeds in these neighborhoods did not improve significantly
- The chart below shows violations in the Bronx broken down by type. Bus lane violations began to decrease after 2023, but the introduction of new violation types in 2024 (such as double parking and standing at bus stops) led to a sharp increase in total violations. This highlights an important issue: while ACE is designed to improve bus service, in some neighborhoods it has primarily resulted in more tickets rather than better outcomes.
- [Tableau Visual Link](https://public.tableau.com/app/profile/ayema.qureshi/viz/please_save_imbegging/Sheet12?publish=yes)
- <img src="https://github.com/user-attachments/assets/368b32da-adb7-4fd9-8961-f6cd195d081b" alt="poverty_map" width="550">
 - This raises questions about fairness: if ACE is meant to improve bus service, but in certain neighborhoods it results mostly in tickets, then the program’s benefits are not being evenly distributed.
 - We focus on the Bronx because it is one of the boroughs with the highest poverty rates and also experienced the largest increase in violations after ACE expanded in 2024. This raises questions about fairness. If residents in high-poverty areas are receiving more violations without seeing meaningful improvements in bus speed or service, then the benefits of ACE are not being distributed evenly across the city.
 - Looking back, when the program was still ABLE and focused only on bus lane violations, we saw violations decrease over time as drivers adjusted to the enforcement. But when ABLE transitioned to ACE and two new categories of violations were added, the number of tickets rose again. This outcome makes sense, expanding the scope of enforcement naturally creates more opportunities for violations but it also shows why local infrastructure matters. In areas like the Bronx, where congestion and street design make compliance harder, the expansion has meant more violations and more financial strain for residents.
 - This suggests that ACE is not equally effective everywhere. Some routes benefit from faster bus service, while others—especially in high-poverty neighborhoods—are weighed down by higher violation counts. This uneven impact raises important equity concerns and shows why not every area is equally suited for ACE implementation.

4. **Route-level differences matter**
- Some routes with ACE showed the intended outcome: faster buses and fewer violations over time. Others, particularly in congested areas, showed the opposite: high violation counts with little improvement in speed. This suggests that infrastructure and route design play a critical role in whether ACE works as intended. 
 - This visualization below of Bronx routes shows how violation counts vary significantly from one route to another, highlighting that the impact of ACE is not uniform across the borough
 - <img src="https://github.com/user-attachments/assets/b8760c0e-0158-4467-b695-9816465af405" alt="poverty_map" width="450">

- This visualization below is a sample of random 15 ACE bus routes, we found no strong correlation between average speed and total violation count. Some routes with higher speeds still had large violation counts, while others with slower speeds had relatively few violations. This suggests that local conditions, such as congestion and street design, may play a larger role than speed in determining how ACE functions on a given route.
- <img src="https://github.com/user-attachments/assets/8507e4d3-b056-4b1e-89d6-c4fe37085d1a" alt="scatter_plot" width="450">

- This scattor plots reveals the following:

a. No clear linear relationship:
  - Some routes with higher speeds (7–9 mph) still have very high violation counts (e.g., BX41+, BX6+).
  - Other routes with lower speeds (5–6 mph) also have high violations (e.g., BX19).
  - This means speed alone does not predict whether violations will be high or low.

b. Clusters of concern
 - The Bronx routes (BX19, BX36, BX41+) stand out with both high violations and slower-to-moderate speeds, suggesting ACE may not be producing benefits in those areas.
 - Manhattan routes like M15+ also appear with very high violations despite higher speeds, which may indicate heavy congestion or enforcement challenges.

c. Positive examples
 - A few routes (like Q69 or M42) show relatively higher speeds and low violations, which suggests ACE is working more effectively there.

5. Correlation, not causation.
- We observed a correlation between speed and violations (e.g., some routes that saw reduced violations also slowed down slightly). However, this does not mean slower speeds cause fewer violations, or vice versa. Instead , Infrastructure and geography likely matter more than speed - since ACE’s purpose is to improve service by enforcing clear lanes, the data suggests that violation counts are influenced by local conditions (congestion, design, density) rather than speed itself.


## Conclusion
_Was the program effective?_

 * Yes, the ACE program has been effective overall in improving bus service, but its effectiveness is not uniform across the city. On some routes, ACE is less necessary because buses already move quickly, while in other areas with slower speeds, ACE has not always delivered its intended benefits. In fact, in certain neighborhoods—particularly those with high congestion and limited infrastructure—the program may create more challenges than improvements.

_Was it fair?_

 * We defined fairness as whether the benefits of ACE were distributed equitably across NYC. In some areas, the program has achieved this balance by reducing violations over time and improving speeds. However, in high-poverty areas such as the Bronx, the program has often meant more violations without corresponding improvements in service. This raises concerns about whether ACE is fairly serving all communities.
   
_Did effectiveness vary across groups, areas, or time periods?_

 * Yes, effectiveness varied significantly depending on borough, route design, and the timeline of implementation. Factors such as congestion, street infrastructure, and the 2024 expansion of violation types all influenced outcomes. For our project, we defined effectiveness as whether ACE improved bus speeds, but we also evaluated it through an equity lens. This revealed that while ACE works well in some contexts, it is not universally effective or fair across all neighborhoods in NYC.

## Recommendations
_What should they keep doing?_

* The ACE program should continue to be implemented across NYC, as it has shown improvements in reducing violations and supporting bus service over time. While the progress can be slow, the data demonstrates that the program becomes more effective once drivers adjust to enforcement.

_What should they change or reconsider?_

* The MTA should evaluate new routes through an equity lens before expanding ACE further. In particular, poverty and income levels should be considered when assessing the impact of violations. In areas like the Bronx and high poverty, where speeds remain low but violations are high, implementing ACE without additional infrastructure changes may create more harm than benefit.
 
_Where is further research needed?_

* Future research should explore how the MTA decides which routes to equip with ACE. Understanding their decision-making process—such as whether they account for infrastructure design, congestion, or community demographics—would help ensure that ACE is deployed more effectively and fairly across the city.

## Limitations/challenges
**Missing Data**

- Some fields in the datasets were incomplete. In those cases, we either labeled the values as missing or counted them as zero. This may have affected some of our calculations. We also had to correct some datatypes 


**Assumptions Made**

- We assumed that some of the MTA’s choices about where to implement ACE routes could be linked to factors such as past bus speeds or congestion levels. Since we did not have access to internal decision-making data, these assumptions were based on external patterns in the data.

**Implementation logic:**

- We assumed the MTA chose routes for ACE based on measurable factors like past bus speeds, congestion, or ridership, since we did not have access to their internal decision-making process.

**Equity lens:** 

- We assumed that poverty and income levels are relevant when evaluating fairness, even though MTA data does not explicitly track socioeconomic demographics.

**Scope of the Analysis**

- The project required narrowing down the focus, but there were many different approaches we could have taken. With more time, we could have explored additional angles such as ridership data, environmental impact, or longer-term outcomes.


## Next Steps
**With more time and resources, future analysis could:**

- Conduct more _statistical testing_ to strengthen claims about the relationship between bus speeds and violations.
- _Long-term impact_: Look at whether violations eventually decline on the 2024 expansion routes (like they did on the original routes) — it may just take more years of data.
- _Decision-making transparency_: Research MTA reports, policy documents, or public hearings to better understand how they choose which routes to implement ACE on, and whether equity is a consideration. What factors do they prioritize when deciding where to implement ACE? Is it congestion, infrastructure, income, or other variables?


## Connect with us!  <p align="center">
  <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMWIyZGE3b3FzejZucmJ0NXJyZ3Bkb3dwN3lnNW40cGl0MXVua2ljdyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/tHIRLHtNwxpjIFqPdV/giphy.gif" 
       alt="ACE Project Funny Gif" 
       width="120" height="120"/>
</p>

- [Thierno Barry_](https://www.linkedin.com/in/thierno-barry-333288284/?lipi=urn%3Ali%3Apage%3Ad_flagship3_people_connections%3BP%2BbOZbM9QwCkyPoYBv9k3g%3D%3D)  
- [Thomas Segal](https://www.linkedin.com/in/thomas-segal-093370369)  
- [Ayema Qureshi](https://www.linkedin.com/in/ayema-qureshi-901287187)  

✨ This project was a true team effort — each of us brought unique perspectives and skills that made the analysis stronger.  

---

**Note:** I apologize — I accidentally git forced all my datasets and resources... so they got deleted T_T
