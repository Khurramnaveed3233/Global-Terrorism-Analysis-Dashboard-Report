#  Global Terrorism Analysis Dashboard Report


![global](https://github.com/user-attachments/assets/f98b090d-ba6b-4b64-8f1b-4e7d1d401dc2)

##  About the Project

Terrorism remains a persistent global threat, with complex patterns and varying impacts across regions. This project analyzes historical terrorism data from 1970 to 2017 to uncover patterns in attack types, regional distribution, terrorist groups, and weapon usage. The interactive Power BI dashboard transforms raw data into meaningful insights that support informed decision-making by security professionals, policymakers, and researchers.

---

##  Problem Statement

Terrorism intelligence is often trapped in large, unstructured datasets, making it difficult to detect trends, identify high-risk regions, and allocate resources effectively. This project aims to address the following challenges:

- Lack of visibility into regional terrorism hotspots
- Limited understanding of successful attack methods and target types
- Difficulty identifying the most lethal terrorist groups
- Inadequate year-over-year trend tracking

---

##  Problems Solved

This project answers several critical business and security-related questions using SQL and Power BI:

- Which terrorist groups are most active and deadly?
- What are the most frequently used weapons and methods of attack?
- Which regions and countries have the highest number and success rate of attacks?
- How have terrorist attacks evolved over the years?
- What types of targets are most commonly attacked?
- Which years experienced the highest number of terrorist incidents?

---

##  Key Insights

1. **Most Deadly Group**: The Taliban is identified as the most deadly group based on the number and success rate of attacks.
2. **Peak Year**: The year 2017 recorded the highest number of global terrorist attacks.
3. **Weapon Preference**: Explosives are the most commonly used weapon, indicating a preference for high-impact attacks.
4. **Attack Methods**: Bombings and armed assaults have the highest success rates.
5. **Target Types**: Civilians and government entities are the most targeted.
6. **Regional Impact**: South Asia experiences the most frequent and successful attacks, followed by the Middle East & North Africa.
7. **Group-Based Success**: Besides the Taliban, ISIS and Boko Haram also show high success rates in attacks.

---

##  Recommendations

- **Strengthen Intelligence in South Asia**: Allocate more resources for monitoring and prevention in South Asia, the most affected region.
- **Enhance Explosive Detection**: Given the high usage of explosives, invest in advanced explosive detection systems at vulnerable sites.
- **Civic and Government Protection**: Reinforce security around frequently targeted groups such as civilians, police, and government officials.
- **Historical Data Modeling**: Use past trends (especially post-2010) to predict potential hotspots and develop proactive measures.
- **Terrorist Group Profiling**: Develop detailed profiles of high-activity groups to support targeted counter-terrorism strategies.

---

##  Impact of the Project

This analysis can be used to:

- Support **data-driven counterterrorism strategies** at national and international levels.
- Aid in **policy formulation** for resource allocation in high-risk regions.
- Enable **predictive modeling** to anticipate future threats.
- Help **journalists, researchers, and analysts** understand global terrorism dynamics.
- Improve **public safety** measures in vulnerable target categories (e.g., civilians, transportation).

---

##  Solution Overview

###  Tools Used

- **SQL Server**: For data cleaning, transformation, and querying
- **Power BI**: For creating interactive and insightful visual dashboards
- **Excel**: For initial data review and formatting

###  SQL Logic Applied

- **Aggregations**: Count of attacks, average success rates, and total targets
- **Group By**: Region, year, weapon type, attack type, terrorist group
- **Filters**: Cleaned null values, filtered non-relevant entries
- **Date-Based Trends**: Yearly attack patterns and peak period identification
- **Joins**: Combined region and attack metadata to enrich visuals

---

##  Challenges Faced

- **Data Imbalance**: High attack frequency in certain countries skewed results; addressed through normalization techniques.
- **Categorical Inconsistency**: Inconsistent naming for weapon types and attack types; solved by standardizing category labels.
- **Missing Coordinates**: Incomplete location data impacted map visuals; only complete entries were used for accuracy.
- **Data Volume**: Over 96,000 records required efficient query optimization and aggregation strategies to maintain performance.

---

##  Conclusion

The **Global Terrorism Analysis Dashboard** serves as a strategic tool for understanding four decades of terrorism patterns. By combining robust SQL querying with dynamic Power BI visualizations, this project transforms static historical data into actionable intelligence. It not only provides a snapshot of global terrorism but also supports smarter, data-driven decisions in the fight against violent extremism.





